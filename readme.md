#installation

if you have rvm installed it will use ruby-1.9.2 and create a gemset called ruby-1.9.2@$(basename $(pwd)).

1. bundle install
1. showoff serve

browse to http://localhost:9090/

## MacOs x
if you are having trouble with rmagick try disabling openmp
when compiling imagemagick. If you are using brew try this.

    brew install imagemagick --disable-openmp
