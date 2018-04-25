# NodeJS-api-generator

Easy generation of API using NodeJS and Express

## Getting Started

NodeJS-api-generator is a bash script. All you have to do is just to execute it in Root and that's all !

### Prerequisites

You'll need NodeJs to make this script functionnal (and bash of course)


## Let's start

You're now ready to generate your API
Go to the directory where you want your API

### Generation

To generate your NodeJS project you can just type this command

```
sudo ./api-generate
```
Now the script is installing all the packages that you'll need to make it work !
You can launch the server to see if it works
```
node app.js
```

### Routes

Api-generate can generate your own route file

```
sudo ./api-generate -route "name of route" "endpoint (/user for example)"
```
Your routes file are in "/lib" and you can edit it to add some functionnalities.

### Example
Imagine that I want a route file for my users.\n
Now you have your "users.js" route file

```

sudo ./api-generate -route users /users
```
Go to "127.0.0.1:8000/users" to see the result

## Authors

* **Romain Kania** - *Initial work* - (https://github.com/Kaniar)

See also the list of [contributors](https://github.com/kaniar/node-api-generator/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## TODO Features

* Link with MySQL Database to generate automatic request
* Build an entire Rest API with the script
