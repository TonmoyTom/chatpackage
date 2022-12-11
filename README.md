1.composer create-project laravel/laravel:^8.0 CHAT

2.php artisan ui vue

3.php artisan ui vue --auth

4.npm install && npm run dev

5.npm install laravel-mix@latest --save-dev
 
6.composer require beyondcode/laravel-websockets

7.php artisan vendor:publish --provider="BeyondCode\LaravelWebSockets\WebSocketsServiceProvider" --tag="migrations"

8.php artisan migrate

9.php artisan vendor:publish --provider="BeyondCode\LaravelWebSockets\WebSocketsServiceProvider" --tag="config"

11.composer require pusher/pusher-php-server

10.Go to CHAT/env random pusher information Set

BROADCAST_DRIVER=pusher
PUSHER_APP_ID=12345
PUSHER_APP_KEY=ABCDEFGH
PUSHER_APP_SECRET=IGKLMNOP
PUSHER_APP_CLUSTER=mt1

12.Go to CHAT/Resources/js/app.js file paste them echo.txt all script.

13.Go to CHAT/Resources/js/Component/ paste them ChatComponent.zip to unzip all File.

14.Go to CHAT/Resources/view/ paste them Chat.blade.php.zip to unzip all File

15.Go to CHAT/database\migrations/view/ paste them table.zip to unzip all File

16.Go to CHAT/router/web.php file paste them route.txt all script.

17.Go to CHAT/app/Http/Controllers paste them HomeController.zip to unzip all File 

18.Go to CHAT/router/channels.php file paste them broadcast.txt all script.

if laravel echo not working must br uses

19.Go to CHAT/Resources/view/Layouts/app.blade.php paste them  head tag under


<link href="{{ asset('css/app.css') }}" rel="stylesheet">
<script src="{{ asset('js/app.js') }}" defer></script>

**** Note 

Laravel 9 does not support this package


