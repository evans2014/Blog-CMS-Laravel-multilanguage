# Blog-CMS-Laravel
Translation CMS laravel

$user = \App\User::create( [
            'first_name' => 'Admin',
            'last_name'  => 'admin',
            'email'      => 'admin@app.com',
            'password'   => bcrypt( '123456' ),
        ] );
