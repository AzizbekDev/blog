<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

## Laravel From Scratch Blog Demo Project - **[blog](https://blog.azizbek.dev)**
___
#### First clone this repository, install the dependencies, and setup your .env file.

```phpregexp
git clone https://github.com/AzizbekDev/blog.git

composer install

cp .env.example .env
```

#### Then create the necessary database.

```phpregexp
php artisan db

create database blog
```

#### And run the initial migrations and seeders.

```phpregexp
php artisan migrate --seed
```

#### Further Ideas

Of course we only had time in the Laravel From Scratch series to review the essentials of a blogging platform. You can certainly take this many steps further. Here are some quick ideas that you might play with.

- Add a `status` column to the posts table to allow for posts that are still in a "draft" state. Only when this status is changed to "published" should they show up in the blog feed.
- Update the `Edit Post` page in the admin section to allow for changing the author of a post.
- Add an `RSS` feed that lists all posts in chronological order.
- Record/Track and display the `views_count` for each post.
- Allow registered users to `follow` certain authors. When they publish a new post, an email should be delivered to all followers.
- Allow registered users to `bookmark` certain posts that they enjoyed. Then display their bookmarks in a corresponding settings page.
- Add an account page to update your username and upload an `avatar` for your profile.

## Contributing

Thank you for considering contributing to the Blog Project!

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to AzizbekDev via [azizbek_muzaffarov@mail.ru](mailto:azizbek_muzaffarov@mail.ru). All security vulnerabilities will be promptly addressed.

## License

The Blog Project is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
