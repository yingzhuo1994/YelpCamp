# YelpCamp

## How to run it locally

1. Install MongoDB
2. Create a cloudinary account and get API Key and Secret code
3. Create a .env file and add the following:

```

CLOUDINARY_CLOUD_NAME= <name>
CLOUDINARY_API_KEY= <key>
CLOUDINARY_API_SECRET= <secret key>
MAPBOX_TOKEN= <token>
DB_URL=<url>
ADMIN_SECRET=<secret code>

```
4. run
```
nodemon app.js
```

Then visit http://localhost:3000/.

## How to set the NODE_ENV on windows 10
Open terminal in the YelpCamp folder, then run 
```
$env:NODE_ENV="production"
node
process.env.NODE_ENV
```
If you can see 'production", it means you succeed.

## Test account
username: test
password: test