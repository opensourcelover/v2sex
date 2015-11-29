# yunjianyi

yunjianyi is A high performance open-source forum software written in Yii2.

## Demo Website

[yunjianyi](http://yunjianyi.com/)

## Requirements

* PHP version 5.3.6 or higher.
* MySQL version 5.0 or higher.
* Nginx or apache

## Install
```
git clone http://github.com/chonder/yunjianyi.git yunjianyi
cd yunjianyi
php init
```
Create database yii2advanced

## Database

Edit the file `common/config/db.php` with real data, for example:

```php
return [
    'class' => 'yii\db\Connection',
    'dsn' => 'mysql:host=localhost;dbname=yii2advanced',
    'username' => 'root',
    'password' => 'root',
    'charset' => 'utf8',
];
```

## Usage

* Use the URL `http://www.domain.com` point to `yunjianyi/frontend/web/` to access application frontend.
* Use the URL `http://admin.domain.com` point to `yunjianyi/backend/web/` to access application backend.

## Default admin and password
```
admin
adminadmin
```

##Features

* Theme based bootstrap3, Designed for everyone, everywhere.
* Discussions Node based.
* High performance. 
* The modern Notification Center (currently supported and @ replies). 
* The topic body based markdown.


##License

Copyright 2015 yunjianyi (admin@yunjianyi.com)

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://yunjianyi.com/LICENSE.md

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
