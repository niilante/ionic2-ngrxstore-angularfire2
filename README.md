#Ionic2 + Ngrx/store + AngularFire2

Ionic2 product list app with AngularFire2 (data persistence) and ngrx/store/effets (state management)

### Install
To install:
```bash
git clone https://github.com/gmarcos87/ionic2-ngrxstore-angularfire2
cd ionic2-ngrxstore-angularfire2
npm install
```
### Configure
Add your Firebase configuration in /src/app/app.module.ts
```javascript
export const firebaseConfig = {
    apiKey: "balblabla",
    authDomain: "balbla-11111.firebaseapp.com",
    databaseURL: "https://blalba-11111.firebaseio.com"
};
```

### Debug
Download the [Redux Devtools Extension](http://zalmoxisus.github.io/redux-devtools-extension/) and happy state debug! - See more in [@ngrx/store-devtools](https://github.com/ngrx/store-devtools)

### Use
```bash
ionic serve
```

### ngRx/store generator
Use this generator https://github.com/gmarcos87/generator-firedux

Inspired on [PouchDB+Ionic2](http://gonehybrid.com/a-beginners-guide-to-using-ngrx-in-an-ionic-2-app-part-2/ "A Beginner's Guide To Using ngrx In An Ionic 2")
