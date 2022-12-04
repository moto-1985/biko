やったこと
composer require laravel/breeze --dev
php artisan breeze:install
npm install
npm run dev
composer require barryvdh/laravel-debugbar --dev
'locale' => 'ja',
'timezone' => 'Asia/Tokyo',
https://github.com/askdkc/breezejp // 日本語化　メールの設定や日本語化も書いてある！！
ここまで初期設定
---
php artisan make:model Admin -m
php artisan make:migration create_admin_password_resets
