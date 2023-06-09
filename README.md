# Demo luồng ETL sử dụng Kafka, Spark Streaming và Apache Hudi

## Step 1: 
```
docker-coompose up --build
```

## Step 2: 
```
pip3 install -r requirements.txt
```

## Step 3: 
```
python producer.py
```

## Step 4: 
```
python hudi-kafka.py
```
