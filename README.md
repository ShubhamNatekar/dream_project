# citystore App

## Introduction
This is online shopping app which the provides products from the nearest shop.

## Tech Stack

- Golang - backend language
- ReactJS - UI technology
- Postgres - DB to store data
- Mysql 
- GORM (A Golang ORM)
- JWT - user authentication
- Gorilla Mux (For HTTP routing and URL matcher)

## Abilities

- Signup (Register)
- Edit his account 
- Shutdown (Delete his account)
- View all Products 
- Buy Product & Add to cart
- Owner can add a products
- Edit Products created by him

## Steps to run

1. Clone the repo
2. Stop host machine services (postgresql/mysql/nginx)
  
  eg.sudo service postgresql stop
3. Run the app 
  
  a. cd citystore
  
  b. docker-compose up
