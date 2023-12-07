# **VILT Starter Kit**

I've created this repository to allow for a quick start at the development of the VILT stack apps.

To get started just clone this repository, change *.env.example* to *.env* and then run the following commands:

`php artisan key:generate`

`npm install`

`composer install`

`npm run dev`

`php artisan serve`

## Technologies:

-   Vue 3
-   InertiaJS
-   Laravel 10
-   TailwindCSS
-   _Others_:
    -   Ziggy (So you can call your Laravel routes inside Javascript)
    -   Laravel Auditing (To keep track of changes in your app Models)
    -   Laravel Precognition (For live validation of your Frontend)
