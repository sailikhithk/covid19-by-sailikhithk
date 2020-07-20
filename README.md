
<h1 align="center">Welcome to Corona DashBoard 👋</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-1.0.0-blue.svg?cacheSeconds=2592000" />
    <img alt="Version" src="https://img.shields.io/badge/build-passing-brightgreen" />
  <a href="#" target="_blank">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-yellow.svg" />
  </a>
  <a href="https://discord.gg/QFmHc9" target="_blank">
    <img alt="Discord Server" src="https://user-images.githubusercontent.com/7288322/34472039-a19b9ed4-efbc-11e7-8946-c1ff405ae2a6.png" />
  </a>
</p>
<img alt="Covid Stats Live Dashboard" src="https://coronastatistics.live/assets/images/preview.png" />

### 🏠 [Homepage](https://github.com/covid19-by-sailikhithk/)

### Youtube Video
### [![Video Demo](https://img.youtube.com/vi/dnwoDyAaMEA/0.jpg)](https://www.youtube.com/watch?v=dnwoDyAaMEA)]

## Screenshots

<img alt="Covid Stats Live Dashboard Screenshot 1" src="https://coronastatistics.live/screenshots/sc1.png" />
<img alt="Covid Stats Live Dashboard Screenshot 2" src="https://coronastatistics.live/screenshots/sc2.png" />
<img alt="Covid Stats Live Dashboard Screenshot 3" src="https://coronastatistics.live/screenshots/sc3.png" />

## Build the Angular project

```sh
npm install
```

```sh
ng build
```


## Run the Angular Project

```sh
npm install
```

```sh
ng serve
```

## Run the Node.js Project (open server folder)

Rename config.example.json to config.json and fill in the details

```
{
  "redis": {
    "host": "host",
    "password": "1234"
  },
  "keys": {
    "all": "coronastatistics:all",
    "countries": "coronastatistics:countries",
    "timeline": "coronastatistics:timeline",
    "timelineglobal": "coronastatistics:timelineglobal"
  },
  "interval": 600000
}
```

```sh
npm install
```

```sh
node server.js
```
Edit src/app/core/services/getdata.service.ts and replace with your own api url.

```
  private host = "https://api.coronastatistics.live"
```

## Author

👤 **Sai Likhith K**

* Website: https://www.sailikhithk.github.io
* Twitter: [@SaiLikhithK](https://twitter.com/Likhith96)
* Github: [@SaiLikhithK](https://github.com/SaiLikhith7)
* LinkedIn: [@SaiLikhithK](https://linkedin.com/in/SaiLikhith96)
