# dockerPHP-slimtest
sample php-slim framework with docker


FROM your docker terminal run the container :

RUN --rm -v $(pwd):/var/www/html/ -v /var/www/html/vendor -p 80:80 eoponda/phpslim-tut:1.0
