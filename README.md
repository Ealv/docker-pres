

 docker run  --label=jekyll --volume=$(pwd):/srv/jekyll   -it -p 127.0.0.1:3000:3000 jekyll/jekyll jekyll serve

http://127.0.0.1:3000/