# Cross Domain Local Storage Test

### Set up
```bash
npm install
bower install
```

### Run
```bash
# on default port 5000
npm start

# on custome port 3000
PORT=3000 npm start
```

### Check functionality

* [Hub](https://cross-domain-localstorage-hub.herokuapp.com/hub.html) - **host for local storage**


* [Client on origin host](https://cross-domain-localstorage-hub.herokuapp.com/index.html) - **All are actions allowed - [get, set, del, clear]**
* [Client One on heroku](https://cross-domain-localstorage-one.herokuapp.com/index.html) - **Allowed actions are [get, set, del]**
* [Client Two on heroku](https://cross-domain-localstorage-two.herokuapp.com/index.html) - **Allowed actions are [get, set, del]**
* [Client on localhost](http://localhost:5000/index.html) - **Allowed actions are [get, set]** -- **Note:** *need to be run by* ```npm start```
