bot dlya svyazki bota s kanalom
pri otpravke posta s bota post publikuetsa na kanale
rabota s knopkoy
takje yest soxranenie i poluchenie ssilki
/setlink v link.txt
/getlink iz link.txt



deploying:
skachat heroku cli
ustanovit git
heroku login v cmd
runtime.txt :versiya pitona
Procfile : worker: python bot.py
requirements.txt : lspisok libov
v cmd:
git init
git add .
git commit -m ""
heroku create nazvanibota
git remote-v
git push heroku master
heroku ps
yesli ne srabotalo to:
heroku ps:scale worker=1
zanovo heroku ps

