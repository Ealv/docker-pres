
A short presentation about Docker focused on dev tools (not production, scaling,...)


# Installation 


## Cloning GIT 
git clone --recursive https://github.com/Ealv/docker-pres.git

If you forget --recusive on cloning process ?
git submodule update --recursive

## Serving Pres 

You can serve with Jekyll.

Or if you has not Jekyll but Docker :

docker run  --label=jekyll --volume=$(pwd):/srv/jekyll   -it -p 3000:3000 jekyll/jekyll jekyll serve


Then go to 
http://127.0.0.1:3000/

# Tuto 

 The presentation use some exemples in

## tests/scala 
use Scala without installing Scala

## tests/node.js
use node.js without installing node.js

## compose
Use node.js and elasticsearch together



