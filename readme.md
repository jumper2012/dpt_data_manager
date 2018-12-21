# Sampoerna Conference

## Description
This application is created based on **LIST of DPT Data**. It will search data with several filter listed as below:
- Nama(Multiple)
- Provinsi
- Kota/Kabupaten
- Kecamatan(Multiple)
- Desa/Kelurahan(Multiple)
- TPS(Multiple)
- Jenis Kelamin

## Access
To access the backend, go to this link [http://your-domain.set.up/](localhost:8000)

## Requirement
The required services for this application are:
1. PHP 5.* (Please don't forget to install these:)
3. MySql 5.*

## Installation
After installing all of the required services, you can start run these commands to start installation

Create your database first in mysql and don't forget to set the .env file based on the .env.example

```sh
$ cd to/the/path/of/your/application
$ composer install
$ php artisan migrate
$ php artisan user:new-admin username email password
$ composer dump-autoload
$ mkdir path/to/storage/backup
```

Please also look after your permission in the server to access the application, whether it's bootstrap directory, or the storage. In times of need, this command will possibly do the rescue

```sh
$ sudo chmod -R 777 path/to/storage
```

Now it's already set up and you can access the application deployed