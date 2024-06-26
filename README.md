<p align="center"><img src="https://sia.ubd.ac.id/images/asset/h_.png"  alt="Logo Buddhi Dharma University"></p>
<p align="center"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="500" alt="Laravel Logo"></p>

# Kelompok 3

Repository ini dibuat bertujuan untuk memenuhi tugas besar mata kuliah Cloud Computing

# Tentang Build With Arya

📚 Build With Arya Course adalah sebuah website pembelajaran untuk siswa-siswi Indonesia terutama siswa-siswi sekolah SD, SMP, SMA, SMK sederajat. Build With Arya Course menyediakan berbagai macam materi dan video pembelajaran yang dapat diakses secara gratis!

# Anggota Kelompok

| No  | Nama                                                            | NIM        | Role            |
| --- | --------------------------------------------------------------- | ---------- | --------------- |
| 1   | [Meiliana]                                                      | 20210700022| Designer 1      |
| 2   | [Rhehuel]                                                       | 20210700021| Programmer      |
| 3   | [Dharta]                                                        | 20210700010| Implementator   |
| 4   | [Paulus]                                                        | 20210700001| Ketua pelaksana |
| 5   | [Arya]                                                          | 20210700026| Designer 2      |
| 6   | [Williams]                                                      | 20210700033| Programmer      |

# Cara Menjalankan Aplikasi

**_Salin perintah ini di terminal :_**

-   Clone project dari github ini

```bash
git clone https://github.com/Dartagtm/web_bwa.git
```

-   Copy file `.env.example` dan rename menjadi `.env`

```bash
cp .env.example .env
```

-   Ubah database masing-masing di file `.env` yang sudah di copy tadi

```bash
DB_PORT=mysql_port
DB_DATABASE=nama_database
```

-   Install Composer

```bash
composer install
```

-   Generate Key

```bash
php artisan key:generate
```

-   Lakukan migrasi database

```bash
php artisan migrate:fresh --seed
```

-   Jalankan server

```bash
php artisan serve
```

# Beberapa preview tampilan website kami :

## Landing Page

![Landing Page](https://raw.githubusercontent.com/SI-RPL-2023/SI4406_A_BidjiCourse/wisnu/public/img/screenshots/landing-page.png)

## Login

![Login](https://raw.githubusercontent.com/SI-RPL-2023/SI4406_A_BidjiCourse/wisnu/public/img/screenshots/login.png)

## Register

![Register](https://raw.githubusercontent.com/SI-RPL-2023/SI4406_A_BidjiCourse/wisnu/public/img/screenshots/register.png)

## Course

![Course](https://raw.githubusercontent.com/SI-RPL-2023/SI4406_A_BidjiCourse/wisnu/public/img/screenshots/course.png)

## Quiz

![Quiz](https://raw.githubusercontent.com/SI-RPL-2023/SI4406_A_BidjiCourse/wisnu/public/img/screenshots/quiz.png)

## Admin Dashboard: Home

![Admin Dashboard: Home](https://raw.githubusercontent.com/SI-RPL-2023/SI4406_A_BidjiCourse/wisnu/public/img/screenshots/admin-dashboard.png)

## Admin Dashboard: Category

![Admin Dashboard: Category](https://raw.githubusercontent.com/SI-RPL-2023/SI4406_A_BidjiCourse/wisnu/public/img/screenshots/categories-admin.png)

## Admin Dashboard: Course

![Admin Dashboard: Course](https://raw.githubusercontent.com/SI-RPL-2023/SI4406_A_BidjiCourse/wisnu/public/img/screenshots/courses-admin.png)

## Admin Dashboard: Quiz

![Admin Dashboard: Quiz](https://raw.githubusercontent.com/SI-RPL-2023/SI4406_A_BidjiCourse/wisnu/public/img/screenshots/quizzes-admin.png)

## Admin Dashboard: User

![Admin Dashboard: User](https://raw.githubusercontent.com/SI-RPL-2023/SI4406_A_BidjiCourse/wisnu/public/img/screenshots/users-admin.png)
![Admin Dashboard: User's Detail](https://raw.githubusercontent.com/SI-RPL-2023/SI4406_A_BidjiCourse/wisnu/public/img/screenshots/users-detail.png)

## Admin Dashboard: Add Category

![Admin Dashboard: Add Category](https://raw.githubusercontent.com/SI-RPL-2023/SI4406_A_BidjiCourse/wisnu/public/img/screenshots/add-category.png)

## Admin Dashboard: Add Course

![Admin Dashboard: Add Course](https://raw.githubusercontent.com/SI-RPL-2023/SI4406_A_BidjiCourse/wisnu/public/img/screenshots/add-course.png)

## Admin Dashboard: Add Quiz

![Admin Dashboard: Add Quiz](https://raw.githubusercontent.com/SI-RPL-2023/SI4406_A_BidjiCourse/wisnu/public/img/screenshots/add-quiz.png)
![Admin Dashboard: Quiz Question](https://raw.githubusercontent.com/SI-RPL-2023/SI4406_A_BidjiCourse/wisnu/public/img/screenshots/quiz-questions.png)
![Admin Dashboard: Add Question](https://raw.githubusercontent.com/SI-RPL-2023/SI4406_A_BidjiCourse/wisnu/public/img/screenshots/add-quiz-questions.png)
