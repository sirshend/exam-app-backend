made the serialisers correct
mongod
mongosh
brew services start mongodb-community
mysql -u root -p
mysql.server start
brew services restart mysql
correct the mongod line: mongod --dbpath .
python manage.py runserver
python manage.py migrate
brew services stop mongodb-community
brew services stop mysql
alternatively mysql can be stopped using by first logging inside the mysql server with mysql -u username -p
mysql -u root -p
mysql.server stop
