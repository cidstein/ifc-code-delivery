# Code Delivery

This project was replicated of the event "Imersão Full Cycle".

#### Description
- A delivery system that allow visualize in real time the delivery guy
- Possibility of multiples delivery guys simultaneosly
- Simulator that will send the real time position of each delivery guy
- The data of each delivery will be store at Elasticsearch to future analyses
- To avoid data loss we wont work with REST, we will work with Apache Kafka to send and receive data between systems.
- The Kafka Connect will consume the simulator data and will insert into Elasticsearch
- We will work with websockets to show the real time position of each delivery guy.

Original project: https://github.com/codeedu/imersao-fsfc2
