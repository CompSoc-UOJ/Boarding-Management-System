# Boarding Management System

## About Project

<p>System developed for managed boardings in jaffna area for university students. University Students in Jaffna Area can contact boarding owners and find their appropiate boarding. Boarding owners can advertise their boarding by putting in them our system. System includes functionalities for</p>

- Register As Boarding Owner
- Add Boarding to our system
- Select your appropiate boarding
- Rate Boarding
- Comment on boarding
- Complain about boarding
- Give Suggestions for the system
- Add Admins
- Remove boardings or boarding owners
- Email messages Send through the system
- Manage comments and complaints

<p>All details include in the FinalReport2019.pdf</p>

## Setup the project

- Clone the project
- Go inside the project directory **( cd Boarding-Management-System )**
- Install the Laravel Composer **( composer install )**
- Generate the key for laravel project **( php artisan key:generate )**
- import the database file to mysql(BMS.sql)
- Setup Configurations in .env file(database configurations and Email configurations). 

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications.

## Further Development

- You can develop according project to add university official boardings to the system. (You may need to introduce catergory information and some other new attribute to maintain those boardings)
- You can maintain those university boarding through the system. ( Cleanings, Arrangings, Assigning roooms to students, other student details )
- Improve the security of the system. (Only show partial information for the person who looking for boarding, add more secure ways to login register )
- Adding payment method (Through this, Boarding owner can receive the advance through system )
- Develop this project combining all sri lankan universities. ( Any university student in sri lanka will be able to find their approapiate boarding )
- Upadate the system into **Laravel 6.0** and Change the views to **vue js**.