to run:

inside /docker - 
docker-compose up --build


in another terminal - /workload_simulator -
python3 simulate_requests.py


in another terminal - /kafka -
python3 producer.py

in another terminal - /KafkaConsumer -
python3 consumer.py
