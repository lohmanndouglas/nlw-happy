
### Happy

Happy is web application that aims to map and schedule visits to orphanages all in an spacific cities. 
With Happy you can register orphanages and check available orphanages to visit. Visit an orphanage can make a child very Happy :)

This app is a study case app developed to learn react, typescript, nodejs, sqlite3, database and other related front-end and back-end technologies.


This development is part of next level week 3 programming course. I would like to say thanks to [Rocketseat](https://rocketseat.com.br/) for this course that
gave to me the oportunity of improve my web development skills. 


### Structure 

 - web: typescript and react front-end application
 - backend: nodejs + sqlite3 backend application

### How to run 

 - Frontend (port 3000)

Start the front-end
```sh
$ yarn start
```

 - Backend (port 3333)

Start the server
```sh
$ yarn dev
```

Database migrations:
```sh
$ yarn typeorm migration:create -n create_orphanages
$ yarn typeorm migration:revert
$ yarn typeorm migration:run
```

### Extra 
 - [Insomnia](https://insomnia.rest/)
 - [Beekeeper Studio](https://www.beekeeperstudio.io/)

