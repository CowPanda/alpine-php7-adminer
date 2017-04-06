# alpine-php7-adminer

adminer of mysql web management.

# run 

    docker run -d --name adminer --link yourMySqlContainer:mysql -p 8080:80 cowpanda/alpine-php7-adminer:php7
