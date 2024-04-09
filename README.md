<br/>
<p align="center">
  <h3 align="center">server & website monitor </h3>

</p>



## Table Of Contents

* [About the Project](#about-the-project)
* [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Usage](#usage)
* [Contributing](#contributing)
* [License](#license)
* [Authors](#authors)
* [Acknowledgements](#acknowledgements)

## About The Project

![Screen Shot](https://cdn.discordapp.com/attachments/1204047796840431697/1227209406568206407/rQ45VLk.png?ex=662792d2&is=66151dd2&hm=d99ab6aa79838bad58dc1392f8e6add5c719d654decb45572a9b0d6059be1c7c&)

if you would to track your server status or get info on the domain do you need this monitor Also faster than NNMonitor 

## Built With
* [node.js](https://nodejs.org/en)
* [dns](https://www.npmjs.com/package/dns)
* [fs](https://www.npmjs.com/package/fs)
* [Table](https://www.npmjs.com/package/Table)
* [winston](https://www.npmjs.com/package/winston)
* [readline](https://www.npmjs.com/package/readline)

### Prerequisites


* npm via node.js v21.1.0 visit {https://nodejs.org/en/download}  to download node.js

```sh
npm i && node .
```


### Installation



```sh
git clone https://github.com/assafgold1/server-website-monitor.git
```

3. Install NPM packages

```sh
npm install
```

4. Enter your data in `config.json`

Example : 
```
[
    {
        "number": 1,
        "ip-address": "192.168.1.1",
        "AddressType": "IPv4Address",
        "owner": "John",
        "group": "customers",
        "active": true,
        "ServerType": "Web Server",
        "ServerOperitengSystem": "windows"
    } ///you can add more if you like 
]
```

### Creating A Pull Request

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See [LICENSE](https://github.com/assafgold1/server-&-website-monitor/blob/main/LICENSE.md) for more information.

## Authors

* **assafgold1** - ** - [assafgold1](https://github.com/assafgold1/) - **

