# Express docker starter

## What does it containts

- Nginx server (Available on port 80)
- Node
- Mysql 
- Mongodb (Available on port 27017) 
- Phpmyadmin (Available on port 8080)
- Maildev (Available on port 8001)

## Mysql credentials

- Database : express
- Login : express
- Password : express

## Mongo credentials

- Database : express
- Login : express
- Password : express

## Starting node project

To start node project run this command :
- docker-compose up

This command will install your packages and run the server

Your can then go to localhost or any other domain you have configured

You can now change your code, it will reload your files directly in the server

!> Be careful, server does not recognise the `bin/www` file, you have to save another file for it to be taken into account

## Activating debug mode on express

To use debug mode, open `docker-compose.yml`, go to the `node` section and uncomment this line : `DEBUG=express:*`

Then run you project has regulary

