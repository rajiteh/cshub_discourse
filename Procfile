web: bundle exec unicorn -p $PORT -E $RACK_ENV -c ./config/unicorn.conf.rb
worker: bundle exec sidekiq -e $RAILS_ENV