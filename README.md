## About

This is a ChatGPT integration with Laravel, Vue.js and TailwindCss.

## Local Development

To build locally, use the following commands:

```bash
git clone git@github.com:shaunthornburgh/laravel-chatgpt-demo-stream.git
cd laravel-chatgpt-demo-stream
composer install
cp .env.example .env
./vendor/bin/sail artisan key:generate
./vendor/bin/sail up -d
./vendor/bin/sail artisan migrate --seed
./vendor/bin/sail npm i
./vendor/bin/sail npm run dev
```
