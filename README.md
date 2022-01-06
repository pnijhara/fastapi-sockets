# fastapi-sockets
Implementing a simple chat application using redis, webockets and other usual fastapi stuff.

## How to run the application

1. Clone/Fork the repo
```shell
$ git clone pnijhara/fastapi-sockets
```

2. Make a virtual environment
```shell
$ python -m venv venv
$ source venv/bin/activate
```

3. Install the required dependencies
```shell
$ pip install -r requirements.txt
```

4. Run fasapi-redis in docker
```shell
$ docker run -d --name fastapi-redis -p 6379:6379 redis
```

5. Run the server in one terminal
```shell
$ uvicorn app:app
```

6. Run the client in a separate terminal
```shell
$ python -m http.server 9000
```

