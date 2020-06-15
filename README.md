Здравствуйте!

Репо клонирован:
https://git.heroku.com/starher.git
https://dashboard.heroku.com/apps/starher 

для развертывания приложения на Heroku, скачать и разорхивировать данные, правая кнопка мыши по папке с проектом, нажимаем "Git Bash Here" и вводим:
git init
git add .
git commit -m "init"
heroku create
git push heroku master
heroku config:set APP_LOCATION=heroku
heroku config:set SENTRY_DSN=https:// Ваша ссылка Sentry
