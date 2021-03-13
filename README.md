## Pokimond RESTful API with Node.js ##

### Scenario ###
```
In Kanto, kids are turned loose from their home at the age of 10 to travel across an incredibly safe country alone with their Pokemon. Their mission? To catch them all!

As a retired software engineer living in the region, you have been approached by Professor Oak to assist him in building a digital guide to assist these kids in their travels across the land.

Using the API available at ​https://pokeapi.co/​, design a ​terminal application to retrieve data about the Pokemon when queried.

The program must have the following functionality:

● Ability to cache the stored information locally (using a text file)
● Ability to search by Pokemon Name or ID.
● Display​ only​ the following information
    - Pokemon ID
    - Pokemon Name
    - Pokemon Type(s)
    - Pokemon Encounter Location(s) and method(s) in ​Kanto​ only
        - If there are no encounter location in Kanto, display ‘-’ 
    - Pokemon stats (speed, def, etc etc)
The program must also be designed in an object-oriented manner.
If the stored information is over a week old, the data should be retrieved again from the API. If not, the data should be retrieved from the text file.
```
### Getting Started ###

*This project utilize a number of JavaScript packages:*

* [Nodejs] - Nodejs.
* [axios] - axios.
* [lowdb] - lowdb.
* [chalk] - Nodejs.

### Pre-requisites ###

```
Make sure you have node, and npm on your computer.

Node: https://nodejs.org/en. For HomeBrew users, you can install node with brew install nodejs. npm is included with nodejs, so there is no need for additional installation for nodejs.

Ensure everything is working fine by running these three commands:

npm --version

node --version
```

### Running on your local machine ###

```
To run the project locally on your machine:
```
#### 1. unzip file and cd` to the directory in terminal/cmd ####
#### 2. npm install to install all the required dependencies. ####
#### #### 

```
$ npm install

```

#### 3. run in the terminal/cmd program with following instructions ####

```bash
$ chmod +x ./pokeapi
$ ./pokeapi
```
