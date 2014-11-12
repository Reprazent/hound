web: sh -c "bundle exec unicorn -p $PORT -c ./config/unicorn.rb"
redis: sh -c "bundle exec redis-server"
resque: sh -c "env TERM_CHILD=1 RESQUE_TERM_TIMEOUT=8 bundle exec rake resque:work"
