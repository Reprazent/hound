web: bin/unicorn -p $PORT -c ./config/unicorn.rb
redis: redis-server
resque: env TERM_CHILD=1 RESQUE_TERM_TIMEOUT=8 bin/rake resque:work
