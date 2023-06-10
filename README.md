# PHP Laravel Example - Pagination

[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://www.codehafeez.com/)

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/codehafeez/)

[![whatsapp](https://img.shields.io/badge/whatsapp-GREEN?style=for-the-badge&logo=whatsapp&logoColor=white)](https://api.whatsapp.com/send?phone=923123349398)



```bash
CMD => composer create-project laravel/laravel --prefer-dist laravel-pagination
CMD => cd laravel-pagination


.env (update db-name) => hafeez_db


CMD => php artisan make:model Employee -m
CMD => php artisan migrate
CMD => php artisan make:controller EmployeeController


Add these 2 lines => (app/Providers/AppServiceProvider.php)
    use Illuminate\Support\ServiceProvider;
    Paginator::useBootstrap();


CMD => php artisan serve
```    


## Screenshots
![](https://raw.githubusercontent.com/codehafeez/Laravel-MultiLanguages/main/Screenshots/Output-01.png)


## 🔗 www.codehafeez.com
