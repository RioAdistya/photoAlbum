# Photo Album

## DOCUMENTATION RESTFULL API

<p> Dokumentasi untuk RESTFULL API photoAlbum </p>

<p> membuat rest API menggunakan NodeJS, ExpressJS dengan database postgres dan juga mengimplementasikan autentikasi dengan JWT </p>

## CLONE REPOSITORY

```bash
$ git clone <remote_repo> (ex: git clone https://github.com/RioAdistya/photoAlbum.git)
```

## HOW TO SETUP

```bash
$ npm install (to install dependencies on the project stored in package.json)
# step pertama : rename .env.example to .env
# step kedua : konfigrasi file .env isi PORT dan SECRET_TOKEN
# step ketiga : konfigurasi direktori config dan sesuaikan dengan konfigurasi postgre pada device masing-masing
```

## HOW TO SETUPDATABASE

<p>Buat database postgre menggunakan ORM Sequelize</p>

```bash
create name dataase postgre dan sesuaikan nama pada database sama config kalian
$ npx sequelize db:create (to create database)
```

```bash
$ npx sequelize db:migrate (to migration table on database)
```

## HOW TO RUN

```bash
$ npm run dev
```
