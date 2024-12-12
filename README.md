# UnstopChallenge
## How to run application

- Download the project zip from the github [https://github.com/KousthubhaK28/UnstopChallenge]
- Install all project dependencies by running command

```bash
  composer install
```
- Set up the environment file Copy the ***.env.example** file to **.env** in the project root.
- Update the **.env** file with the appropriate configuration details (database settings etc.) for your local environment.
- Generate an application key:
```bash
  php artisan key:generate
```
- Start the Xampp server. [MYSQL]
- Run database migrations:

```bash
  php artisan migrate:fresh
```
- ***Very Important :** database seeder which inserts the string with length of 80 in the table.
 
```bash
  php artisan db:seed
```
- Run the application:
```bash
  php artisan serve
```

## Files used in project


`app/Http/Controllers/TicketBookingController`

`database/migrations/`

`database/seeders/TicketbookingSeeder`

`resources/views/welcome.blade.php`

`resources/views/ticket-info.blade.php`

`routes/web.php`
