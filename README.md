1.composer create-project laravel/laravel:^8.0 CHAT

2 composer require laravel/ui

3.php artisan ui vue

4.php artisan ui vue --auth

5.npm install && npm run dev

Go to Package.json edit script edit 

  "scripts": {
        "dev": "npm run development",
        "development": "mix",
        "watch": "mix watch",
        "watch-poll": "mix watch -- --watch-options-poll=1000",
        "hot": "mix watch --hot",
        "prod": "npm run production",
        "production": "mix --production"
    },

then npm run dev run

6.npm install laravel-mix@latest --save-dev
 
7.composer require beyondcode/laravel-websockets

8.php artisan vendor:publish --provider="BeyondCode\LaravelWebSockets\WebSocketsServiceProvider" --tag="migrations"

9.php artisan migrate

10.php artisan vendor:publish --provider="BeyondCode\LaravelWebSockets\WebSocketsServiceProvider" --tag="config"

11.composer require pusher/pusher-php-server

12.Go to CHAT/env random pusher information Set

13. npm install --save laravel-echo pusher-js

BROADCAST_DRIVER=pusher
PUSHER_APP_ID=12345
PUSHER_APP_KEY=ABCDEFGH
PUSHER_APP_SECRET=IGKLMNOP
PUSHER_APP_CLUSTER=mt1

14.Go to CHAT/Resources/js/app.js file paste them echo.txt all script.

15.Go to CHAT/Resources/js/Component/ paste them ChatComponent.zip to unzip all File.

16.Go to CHAT/Resources/view/ paste them Chat.blade.php.zip to unzip all File

17.Go to CHAT/database\migrations/view/ paste them table.zip to unzip all File

18.Go to CHAT/router/web.php file paste them route.txt all script.

19.Go to CHAT/app/Http/Controllers paste them HomeController.zip to unzip all File 

20.Go to CHAT/router/channels.php file paste them broadcast.txt all script.

if laravel echo not working must br uses

21.Go to CHAT/Resources/view/Layouts/app.blade.php paste them  head tag under

22 . php artisan websocket:serve

23. your_domain/websockets url hit this and connect websocket

<link href="{{ asset('css/app.css') }}" rel="stylesheet">
<script src="{{ asset('js/app.js') }}" defer></script>

**** Note 

Laravel 9 does not support this package


