# paradise_restaurant_order_management_system

#Clone the repository

git clone https://github.com/Sujaany/paradise_restaurant_oms

#Switch to the repository folder

cd paradise_restaurant_oms

#Install all the dependencies using composer

composer install

#Copy the example env file and make the required configuration changes in the .env file

cp .env.example .env

#Generate a new application key

php artisan key:generate

#Generate a new JWT authentication secret key

php artisan jwt:generate

#Run the database migrations (Set the database connection in .env before migrating) php artisan migrate

#Start the local development server

php artisan serve You can now access the server at http://localhost:8000

###command list

git clone https://github.com/Sujaany/paradise_restaurant_oms

cd paradise_restaurant_oms

composer install

cp .env.example .env

php artisan key:generate

php artisan jwt:generate

#Make sure you set the correct database connection information before running the migrations Environment variables

php artisan migrate

php artisan serve
