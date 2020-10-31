# bcredi_data_engineer_test
Technical test for the Data Engineer position at Bcredi.

## Challenge 1
### Context:
Imagine a scenario where a team of developers mantain several backend applications as microservices and some key events are produced in RabbitMQ Queues/Kafka topics which are mainly used to feed applications, but also to enable data-driven business decisions. Your goal is to design a data infrastructure architecture which enables:
- Data analysts to easily consume the data provided by the source applications in order to aggregate information;
- Data scientists to develop machine learning models having the flexibility to use data from one or more sources;
- Managers without an IT background to easily consume and visualize the data.
### Requirements:
- The architecture may process some data as real time streams where applicable and some in batches;
- Assume that real time data from different RabbitMQ Queues/Kafka topics may need to be consolidated and aggregated before being consumed by end applications (assume that a single process may be represented by multi-topic events, all of which are related by a single ID);
- Ensure that access to sensitive data is limited to specific roles (eg. data scientists may need access to the raw data, but business analysts only require access to aggregate data);
- The architecture can be designed using any tool or technology, with preference to open source code and cloud services;
### What we evaluate:
- The extent of which requirements are met;
- Feasibility and cost of implementation of the architecture proposed;
- Organization and justification of the tools used.

## Challenge 2
In this repository is commited a Jupyter Notebook, your challenge is to solved all the questions. If you prefere you can just fork this repository and send to us.

