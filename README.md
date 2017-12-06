# Moodle Sanitize
This is a simple SQL script to sanitize data of a Moodle installation.

## How to skip specific users
To prevent certain user data from sanitization in the users table, in the user.sql file add the user IDs that you would like to skip within the brackets. By default, this will skip users with ID 1 and 2.