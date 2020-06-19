# Laravel Enso



**Hit the ground running when building your new Laravel SPA project with boilerplate and extra functionality out of the box!**

&nbsp;

[![Watch the demo](https://laravel-enso.github.io/enso/screenshots/bulma_cap000_thumb.png)](https://laravel-enso.github.io/enso/videos/bulma_quick_walkthrough.webm)

<sup>click on the photo to view a short demo in compatible browsers</sup>

### Important

If you are using this project please consult the **[changelog](https://github.com/laravel-enso/Enso/blob/master/CHANGELOG.md)** on every update.

For the v1.x / adminlte version, take a look at the **[adminlte](https://github.com/laravel-enso/Enso/tree/adminlte)** branch.

### Official Documentation

The documentation is available [here](https://docs.laravel-enso.com) split into backend and frontend.
Note that most sections have short demo clips.

### Take It For A Spin

You may try out a live demo installation by visiting [laravel-enso.com](https://www.laravel-enso.com) 
and logging in with `admin@laravel-enso.com` and `password`. 

### Installation Steps

1. Download the project with `git clone https://gitlab.com/hastech/pos-sector.git --depth 1`

2. Within the project folder run `composer install`

3. Create a database for your site (see the [Laravel database documentation](https://laravel.com/docs/6.x/database)), 
copy or rename the `.env.example` file to `.env`, 
edit the database configuration information, and run `php artisan key:generate`

4. In order to serve the back-end API, take a look at the Local Development Server section of the [Laravel installation documentation](https://laravel.com/docs/6.x/#installation)
and consider using [Valet](https://laravel.com/docs/6.x/valet) for a better experience

5. Run `php artisan migrate --seed`

6. Open the `client` folder, copy the `.env.example` file, save it as `.env` and set the URL 
for the back-end API (which you've configured at step 4)

7. Run `yarn && yarn build`

8. Launch the site and log into the project with user: `admin@laravel-enso.com`, password: `password`

9. For live reload / hot module replacement functionality run `yarn serve`

10. (optional) Setup the configuration files as needed, in `config/enso/*.php`


Enjoy!
