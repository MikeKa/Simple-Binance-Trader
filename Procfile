worker: python3 run.py
web: gunicorn --worker-class geventwebsocket.gunicorn.workers.GeventWebSocketWorker -w 1 core.botCore:SOCKET_IO
