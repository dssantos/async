
# async
Synchronous and asynchronous tasks examples

## How to dev

### Linux
```bash
git clone https://github.com/dssantos/async.git async
cd async
python -m venv .async
source .async/bin/activate
python -m pip install -U pip
pip install -r requirements.txt
```

## Runing Sync and Asynk tasks

### Synchronous Programming
Using 2 syncronous taks to process one FIFO queue ([example_1.py](example_1.py))
```bash
# run example
python example_1.py
```

### Cooperative Concurrency
Using 2 pseudo concurrence tasks switching to process one FIFO queue ([example_2.py](example_2.py))
```bash
# run example
python example_2.py
```

## Reference:
https://realpython.com/python-async-features/
