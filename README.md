# flask-base [![master](https://github.com/page1337com/flask-base/actions/workflows/master.yml/badge.svg)](https://github.com/page1337com/flask-base/actions/workflows/master.yml)
Flask Base in Docker via Github Actions to Github Packages

```
.
├── Dockerfile
├── README.md
├── app
│   ├── api
│   │   ├── __init__.py
│   │   └── routes.py
│   └── main.py
├── docker-compose.yml
└── requirements.txt
```

# Prerequisites
- Ubuntu (Recommended)
- docker.io
- docker-compose

```
sudo apt install docker.io docker-compose -y 
```

# How to use
```
git clone https://github.com/page1337com/flask-base
```

```
docker-compose build && docker-compose up -d && docker-compose logs -f
```

```
curl localhost:8080
```
