# CH4-03-28-2024-configPublic-CRUDejs-configConnectflashExpressionsession

Create Data Customer App

Create Data Customer App adalah aplikasi web yang memungkinkan pengguna untuk membuat, mengedit, dan menghapus data customer dengan mudah.

Fitur Utama
Tabel data customer
Tambah data customer
Edit data customer
Delete data customer

Instalasi
npm install
npm install express morgan nodemon pg pg-hstore sequelize sequelize-cli
npx sequelize init
npx sequelize db:create
npx sequelize model:generate --name customer --attributes name:string,age:integer,email:string,password:string,photo:text
npm i connect-flash
npm i express-session

Running server
npm run dev

Server routing
 Homepage : http://localhost:8000/customers
 Add customer : http://localhost:8000/customers/create
 Edit customer : http://localhost:8000/customers/edit/1
 


