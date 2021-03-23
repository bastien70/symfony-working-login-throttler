# symfony-working-login-throttler

## Installation

1. composer install
2. update .env with your own database setup
3. php bin/console d:d:c
4. php bin/console d:s:u -f
5. symfony serve
6. Go to /register path and create an account
7. You will be redirected to /login path. Test with bad credentials two times. Next time, login throttler will block you for 1 minute.
