# Laravel Terminal Commands

### 1. Create Project
	composer create-project laravel/laravel 'project name'

### 2. Create Controller with resource funcs
	php artisan make:controller 'Controller name' --resource

### 3. Create Model And Migrate
	php artisan make:model 'Model Name' -m 

### 4. Migrate(Create Tables)
	php artisan migrate

###5. Tinker(Add data to tables)
```bash
php artisan tinker
$var = new App\'ModelName'()
$var->'attribute'='value'
$var->save()
```
###6. Make Authentications
	php artisan make:auth

###7. Link Storage.
	php artisan link:storage