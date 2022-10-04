following https://github.com/AlexUkPC/blackandorange because I forgot to add all needed files



docker-compose run --rm web_blackandorange bin/rails webpacker:install  
in package.json  
    "webpack": "^4.46.0",  
    "webpack-cli": "^3.3.12"  
  "devDependencies": {  
    "webpack-dev-server": "^3"  
  }
docker-compose run --rm web_blackandorange yarn add webpack-cli  
docker-compose run --rm web_blackandorange yarn install  
docker-compose run --rm web_blackandorange yarn upgrade  
