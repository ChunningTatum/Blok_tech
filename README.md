# READ ME

## What am I looking at?
This is a dating application for the project Tech I am following. The application is build in Node and the server is written with Express with an template engine 'Ejs'. The database that I am using with the application is MongoDB.

## Job story:
As a user of the dating site, I want to be able to tell other's my interests, so other users can get to know me better and result in better matches. To be able to meet these requirements, the user is able to make a account and set their interests in games, these interest will be set in a certain way for others to see. 

## Wiki

Check my wiki for all the documentation. (FYI wiki is written in Dutch)

## Database

Currently I am using a MongoDB database which uses Json structure.
![database](https://user-images.githubusercontent.com/45426792/77068100-50f74b80-69e6-11ea-8fe3-4d412ae415f3.PNG)


## Packages used

### ejs
The template engine u have used to server server side html is EJS.

https://www.npmjs.com/package/ejs

### express         
I build this application with the framework express

https://expressjs.com/en/starter/installing.html

### mongodb
In my application I also use a database. I use mongodb to connect with the database, where all my users are saved in a Json format

https://docs.atlas.mongodb.com/getting-started/

### passport        
For sessions and authentication, I have used passport with epress session. 
http://www.passportjs.org/docs/authenticate/

For the full list of packages, look in the package.json file.


## How to install

1. Open a terminal

2. Clone this repo
```
git clone https://github.com/ChunningTatum/Blok_tech
```

3. Install node modules
```
npm install
```

4. Run the application
```
npm start
```

## License

[MIT](https://github.com/ChunningTatum/Blok_tech/blob/master/LICENSE)
