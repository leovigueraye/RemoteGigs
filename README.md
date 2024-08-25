# LaraGigs app

## Introduction

An app for listing Remote gigs/jobs. 

## Features

- Built with Laravel 
- Jetstream (Livewire + blade stack)
- Create job posts
- view job posts
- edit job posts
- Delete job posts

## Installation

- Clone this repo using any method (https, ssh, gh cli)

- Set the configuration file using the command 
``` cp .env.example .env ```

- Install all required packages via composer. ``` composer install ```

- Set up Database configuration inside .env file.

- Run the migration 

```
php artisan migrate 
```

- Install all dependencies via `npm` and Compile all assets based on your deployment environment. 

#### Npm
```bash
#Install all dependencies
npm install

#Development
npm dev

#Production
npm prod
```

- Create symbolic link 
```
php artisan storage:link
```

- Start the local server using the command
```
php artisan serve
```
## Preview

![image](images/Screenshot%20(145).png)

![image](images/Screenshot%20(146).png)