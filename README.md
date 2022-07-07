# react-nginx

環境構築方法<br>
①cloneする<br>
②docker-compose up -d --build  
③docker-compose run --rm react-app sh -c "cd react-app && npm install"  
④docker-compose up -d --build  
⑤localhost:3000にアクセスしてreactが表示されていることを確認  
⑥docker-compose exec react-app bash  
⑦cd react-app && npm run build  
⑧docker-compose down  
⑨docker-compose up -d  
⑩localhost:8000にアクセスしてreactが表示されていることを確認
