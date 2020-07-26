<a href="https://github.com/L0rdC0mm4nd3r/AnoChat"><img src="https://github.com/L0rdC0mm4nd3r/pdfscrape/blob/master/banner.png" title="Anochat" alt="AnoChat"></a>

# AnoChat

> Anochat is an encrypted chatting system built over TCP
> It's purely written in python3

## Features

- Easy and simple to use
- Fast
- Multiple client chat at the same time
- Assymetric encryption - RSA 2048 ( can be manually increased to any bits you like )
- Doesn't need port forwarding to work as it will automatically do that for you

## Requirements

- pcryptodome

- stdiomask

- configparser

- pyngrok

- beautifulsoup4

## Installation 

> clone this repo

```
gitclone https://github.com/L0rdC0mm4nd3r/pdfscrape
```
 
> Run the setup

```
python3 setup.py
```

## Usage

Ngrok will be used by default to mask your machine also to make it accessable from WAN
How ever if the server is hosted on Termux ngrok will fail So you'll have to change the
value of ngrok by opening server.ini inside config directory.

Port and Passcode can also be changed by opening server.ini inside config directory.

You can start the server by changing directory to server and
```
python3 server.py
```

For client

```
python3 anochat.py <server_ip> <server_port>
```

## Screenshots

![IMG1](https://github.com/L0rdC0mm4nd3r/pdfscrape/blob/master/gif.gif)
![IMG2](https://github.com/L0rdC0mm4nd3r/pdfscrape/blob/master/gif.gif)
![IMG3](https://github.com/L0rdC0mm4nd3r/pdfscrape/blob/master/gif.gif)
![IMG4](https://github.com/L0rdC0mm4nd3r/pdfscrape/blob/master/gif.gif)
![IMG5](https://github.com/L0rdC0mm4nd3r/pdfscrape/blob/master/gif.gif)
![IMG6](https://github.com/L0rdC0mm4nd3r/pdfscrape/blob/master/gif.gif)
![IMG7](https://github.com/L0rdC0mm4nd3r/pdfscrape/blob/master/gif.gif)
![IMG8](https://github.com/L0rdC0mm4nd3r/pdfscrape/blob/master/gif.gif)

## Author

* **Lord Commander** [Github repo](https://github.com/L0rdC0mm4nd3r/) [Telegram](https:t.me/L0rdComm4nd3r)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* MoonCake for letting me finish it
