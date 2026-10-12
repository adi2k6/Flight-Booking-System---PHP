# Flight Ticket Booking System

A PHP and MySQL flight-booking application.

## Project files

The original project files are under [`flight-ticket-booking-main/`](./flight-ticket-booking-main/), including the PHP pages and [`flight booking.sql`](./flight-ticket-booking-main/flight%20booking.sql) database schema with sample data.

## Setup

1. Import `flight-ticket-booking-main/flight booking.sql` into MySQL.
2. Configure the MySQL connection values in `flight-ticket-booking-main/db.php` for your environment.
3. Serve the PHP project using a PHP-enabled web server with the required database and include files configured.

Note: the included PHP files reference a sibling `includes/` directory. Check those include paths against your local project layout before running the application.