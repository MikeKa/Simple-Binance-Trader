worker: python3 run.py
web: gunicorn --worker-class geventwebsocket.gunicorn.workers.GeventWebSocketWorker -w 1 botCore.start:APP
