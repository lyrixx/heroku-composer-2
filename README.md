Reproducer

History

```
symfony new --full --version=next heroku-composer-2
cd heroku-composer-2
heroku create heroku-composer-2
echo 'web: heroku-php-apache2 public/' > Procfile
git add Procfile
git commit -m "Heroku Procfile"
git push heroku master
git remote add origin git@github.com:lyrixx/heroku-composer-2.git
git push origin master -u
history
```
