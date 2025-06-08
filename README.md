# docker-amp-template

This is a really simple starter template for setting up AMP (Apache, MariaDB and PHP + phpMyAdmin) using Docker.

I usually use XAMPP for this sort of thing, but updates stopped in 2023, and I needed a more modern solution. 

Docker can be complicated to understand, and for simple projects there is nothing worse than complicated. So this template is as simple as it gets.

## How To Use

1. Make sure Docker is installed.
2. Clone this repo into a folder somewhere on your computer.
3. Launch a terminal in the folder you created, and type `docker-compose up`
4. Visit `http://localhost` and you should see "Hello World!"
5. Visit `http://localhost:8080` to access phpMyAdmin.

## Some Notes

- The `www` folder contains your web files.
- Change things in the `docker-compose.yml` file to suit your needs.
- By default this has PHP 8.2, but you can change that easily.
- The database has a weak password, you may want to change it to stop getting warnings in phpMyAdmin.

## Final Thoughts

Would you make any improvements? To me this fits my use case, but I can imagine an alternative version that also includes Redis, Litespeed etc... 

Thanks for checking this out!

Koda