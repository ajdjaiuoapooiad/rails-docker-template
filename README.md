docker-compose run web rails new . --force --database=mysql  
 docker-compose build  

database.yml 編集　password, host: dbに変更  
db削除　なぜか必要  
docker-compose run web rails db:create migrateと同じ  
docker-compose up　起動  
