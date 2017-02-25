web: python aaronbot.py --log-file -
heroku ps:scale worker=0
heroku ps:scale worker=1
web: bundle exec thin start -p $PORT