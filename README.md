# kod_in_docker
deploy kod in docker  
kod version: 3.12 (https://github.com/kalcaddle/KODExplorer)


# run
docker build -t yonh/kod .   
docker run --rm -p 8080:80  yonh/kod   
or  
docker run --rm -p 8080:80 -v ~:/var/www/html/data/User/admin/home yonh/kod
