# Overview

Kafka has many moving pieces, but also has a ton of helpful resources to learn available online. In this homework, your
challenge is to write answers that make sense to you, and most importantly, **in your own words!**
Two of the best skills you can get from this class are to find answers to your questions using any means possible, and to
reword confusing descriptions in a way that makes sense to you. 

### Tips
* You don't need to write novels, just write enough that you feel like you've fully answered the question
* Use the helpful resources that we post next to the questions as a starting point, but carve your own path by searching on Google, YouTube, books in a library, etc to get answers!
* We're here if you need us. Reach out anytime if you want to ask deeper questions about a topic 
* This file is a markdown file. We don't expect you to do any fancy markdown, but you're welcome to format however you like

### Your Challenge
1. Create a new branch for your answers 
2. Complete all of the questions below by writing your answers under each question
3. Commit your changes and push to your forked repository

## Questions
#### What problem does Kafka help solve? Use a specific use case in your answer 
* Helpful resource: [Confluent Motivations and Use Cases](https://youtu.be/BsojaA1XnpM)
* Kafka is powerful  processing distributed events/live data

#### What is Kafka?
* Helpful resource: [Kafka in 6 minutes](https://youtu.be/Ch5VhJzaoaI) 
distruting a queue structure

#### Describe each of the following with an example of how they all fit together: 
 * Topic: a group of partitions, with order, but not able scale out, partition no. and offset
 * Producer: source of events
 * Consumer :  very lightly, read diff record
 * Broker:server that is made of one or more servers, holds a subset of records that belongs to the entire cluster 
 * Partition:The smallest storage unit that holds a subset of records owned by a topic

#### Describe Kafka Producers and Consumers

#### How are consumers and consumer groups different in Kafka? 
* Helpful resource: [Consumers](https://youtu.be/lAdG16KaHLs)
* Helpful resource: [Confluent Consumer Overview](https://youtu.be/Z9g4jMQwog0)
 Consumer groups: strong order, and preserve scaling.
#### How are Kafka offsets different than partitions? 
Offset is a unique sequential identifier within a partition
#### How is data assigned to a specific partition in Kafka? 
The data is assigned to a partition by pattern matching
#### Describe immutability - Is data on a Kafka topic immutable? 
No
#### How is data replicated across brokers in kafka? If you have a replication factor of 3 and 3 brokers, explain how data is spread across brokers
* Helpful resource [Brokers and Replication factors](https://youtu.be/ZOU7PJWZU9w)
a replication factor of 3 means each topic and each Partition  are distributed across 3 brokers
#### What was the most fascinating aspect of Kafka to you while learning? 
how it order events and keep it scal