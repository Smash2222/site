# LaraGigs app

An app for listing Laravel gigs/jobs.

## Usage

### Database Setup
This app uses MySQL.


### Migrations
To create all the necessary tables and columns, run the following
```
php artisan migrate
```

### Seeding The Database
To add the dummy listings with a single user, run the following
```
php artisan db:seed
```

### File Uploading
When uploading listing files, they go to "storage/app/public". Create a symlink with the following command to make them publicly accessible.
```
php artisan storage:link
```
