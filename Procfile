worker: python3 run.py
web: gunicorn -k geventwebsocket.gunicorn.workers.GeventWebSocketWorker -w 1 core.botCore:APP