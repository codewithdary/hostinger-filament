# Mastering FilamentPHP v3 for Beginners

This repository is a collection of code that accompanies a [video series](https://www.youtube.com/watch?v=fOEpPhztORo&list=PLFHz2csJcgk_M6tg-f589Myy-lbLyACKi) on YouTube about FilamentPHP, a modern, open-source, and community-driven PHP framework. The video series covers various aspects of the framework, including installation, configuration, and usage. <br>
•	Twitter: [@codewithdary](https://twitter.com/codewithdary) <br>
•	Instagram: [@codewithdary](https://www.instagram.com/codewithdary/) <br>
•	TikTok: [@codewithdary](https://tiktok.com/@codewithdary) <br>
•	Blog: [@codewithdary](https://blog.codewithdary.com) <br>
•	Patreon: [@codewithdary](https://www.patreon.com/user?u=30307830) <br>
<br>

## Video Chapters

| Chapter | Title |
|---------| --- |
| 1       | Introduction & Setup FilamentPHP |
| 2       | How to Customize FilamentPHP its Theme to Your Own |
| 3       | Building Our Ecommerce Migrations & Models  |
| 4       | How to Build Resources in FilamentPHP  |
| 5       | Resource Modifiers & Resource Filters in FilamentPHP |
| 6       | What are Actions & How to Use Them in FilamentPHP |
| 7       | Building Our Customer, Order & Category Resources in Filamentphp |
| 8       | How to Setup The Global Search in FilamentPHP |
| 9       | How to Customize The Navbar in FilamentPHP |
| 10      | How to Define Relationships in FilamentPHP |
| 11      | How to Create a Dashboard Using Widgets, Charts & Tables |
| 12      | Configure Plugins from FilamentPHP |
| 13      | How to Deploy a FilamentPHP Project on Hostinger  |

## Simple Deploy Script
```
git pull
cp .env.example .env
php artisan key:generate
composer install --no-dev --optimize-autoloader
php artisan optimize
php artisan route:cache
php artisan cache:clear
php artisan migrate
```

## .htaccess script
```
<IfModule mod_rewrite.c>
  RewriteEngine On
  RewriteRule ^(.*)$ public/$1 [L]
</IfModule>
```

For more information about FilamentPHP, please visit the [official website](https://filamentphp.com/).
