
# Supermarket Managemen System | Laravel

This is a supermarket management system you can do CURD operation in (products,
employees, users, categories, supplier company, incoming and out going), and don’t worry if
you enter invalid data, the system will alert you and no invalid data will be sorted.

There is also a cashier page and page to supplying products to supermarket which you can add
product barcode and stock which you will sell it or add it to your supermarket, details of current
order will be saved if you leave page without cancel or complete the order, if you want to
cancel order or remove one or more element from it you can click remove on item you want to
remove it, and if you want to complete the order just click at cash button, you can add any item
form your supermarket to current order without refresh the page because we use AJAX
(request and response) between backend and front end.

There are many features I don’t mention it, I will let you to discover it

## Run Locally

Clone the project

```bash
  git clone https://github.com/Ezz690/Supermarket-management-system.git
```

Go to the project directory

```bash
  cd Supermarket-management-system/Project
```

Install dependencies

```bash
  composer update
  npm install
```
Create new database and import db.sql to it 

Create new file ".env", then copy evrey thing from .env.example and past on ".env"

edit ".env" and put your database name DB_DATABASE=Your databse name

Open terminal and run 
```bash
  npm run dev
```

Open new terminal and run 
```bash
  php artisan key:generate
  php artisan serve
```

