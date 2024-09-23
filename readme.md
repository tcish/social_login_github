# Social Login Integration with GitHub and Facebook

## Introduction

This project implements social login functionality, allowing users to authenticate using their GitHub or Facebook accounts.

---

## Installation

**Clone the Repository**

First, clone the project repository from GitHub using the following command:

```bash
git clone https://github.com/tcish/social_login_github_facebook.git
```

**Navigate into the project directory:**
```bash
cd social_login_github_facebook
```

**Install dependencies:**
```bash
composer i
npm i
```

**Copy the .env.example file to create your .env configuration file:**
```bash
cp .env.example .env
```

**Open the .env file and add database name & add github, facebook client id and client secret**
- DB_DATABASE=your_database_name
- GITHUB_CLIENT_ID=client_id_here
- GITHUB_CLIENT_SECRET=client_secret_here
- FACEBOOK_CLIENT_ID=client_id_here
- FACEBOOK_CLIENT_SECRET=client_secret_here

**Generate an application key:**
```bash
php artisan key:generate
```

**Migrate the database:**
```bash
php artisan migrate
```

**Build local frontend assets:**
```bash
npm run dev
```

**Start the Laravel development server:**
```bash
php artisan serve
```

---

## Tech Stack

**Client:** HTML, CSS, TailwindCSS

**Server:** PHP, Laravel

**Package:** Laravel Socialite

**Database:** MySQL