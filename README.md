<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## Laravel Migration

Passo a passo de como realizar uma migration em laravel

Primeiro você deve:

- Instalar o composer e o xampp
- Acessar o xampp/php/php.ini e pesquisar por ;extension=ftp/ffi/zip, e depois retirar o “;”.
- Criar uma pasta no xampp/htdocs.

## Instalação do Laravel

Abra o terminal e siga a sequência de comandos:

<img width="540" height="306" alt="OhYeah" src="https://github.com/user-attachments/assets/016a1baa-8dd3-4146-b60f-7c0cbae51034" />



<img width="410" height="32" alt="new" src="https://github.com/user-attachments/assets/12850fe3-d78a-4e24-b00f-47891ac6a9e0" />



<img width="420" height="245" alt="laravel" src="https://github.com/user-attachments/assets/8ff44956-05c0-44ec-8402-2cd3fb909999" />



<img width="395" height="142" alt="sql" src="https://github.com/user-attachments/assets/3bac06db-5892-49d4-b74c-b534c882c952" />



<img width="343" height="84" alt="OhYeah02" src="https://github.com/user-attachments/assets/57c744d1-9b20-456c-9264-289e8ac63572" />



<img width="1098" height="315" alt="OhYeah03" src="https://github.com/user-attachments/assets/14acc152-0b4b-4552-91a8-e2a928d83a70" />



<img width="516" height="53" alt="OhYeah04" src="https://github.com/user-attachments/assets/a9061cf6-f385-47c6-b922-5f4c321dd9a6" />




Agora, vamos executar o processo de migração: esse comando aplica as alterações definidas no projeto ao banco de dados configurado. Ele utiliza as informações de conexão especificadas no arquivo .env para localizar o banco.
Crie uma tabela chamada alunos.

<img width="1048" height="76" alt="OhYeah07" src="https://github.com/user-attachments/assets/b2c359ad-8730-404c-9c5a-d6d151f3af98" />




Podemos notar a criação da tabela alunos na pasta MigrationPW\database\migrations:

<img width="332" height="342" alt="tabela" src="https://github.com/user-attachments/assets/936645fd-645c-436a-87b2-2421f5f83170" />




No arquivo referente a tabela, deve-se fazer as alterações para acrescentar as informações e dados desejados:

<img width="574" height="649" alt="codigo" src="https://github.com/user-attachments/assets/98cf3bae-3285-4ccb-948a-97182a48fb5a" />




Para publicar as alterações devemos rodar esse comando:

<img width="1060" height="277" alt="OhYeah08" src="https://github.com/user-attachments/assets/fa252eb9-5d01-4df3-9285-43c2c44aa284" />


No  phpMyAdmin, visualizamos a tabela que foi criada com os campos definidos:

<img width="642" height="276" alt="OhYeah09" src="https://github.com/user-attachments/assets/3c1c1b35-4f71-4979-af78-1029cc9eba23" />
