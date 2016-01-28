#### Instalation

	git clone https://github.com/wojtek77/laravel-5.2.git laravel
	cd laravel
    composer install
    cp .env.example .env
    php artisan key:generate
    php artisan clear-compiled
    php artisan ide-helper:generate
    
    git remote rm origin
    
    <edit database settings in file ".env">
	php artisan migrate
