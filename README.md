# Visual Programming - Create Microservice, Monolith or Distributed Monoliths faster than 2min Noodles 
- This blog throws light on low code Drag N Drop platforms that embrace the concept of Visual Programming and suggests how these platforms come handy when time to market is priority.
- Node-Red by IBM is one such opensource Drag N Drop platform that is taken as an example to present a fully-featured event driven platform.
- Node-Red not only simplify the creational and structural concerns for Software Architects but also helps in curbing staffing problems by promoting flow based visual programming.
## What is Visual Programming ?
```
A Visual Programming Language (VPL) is any programming language that lets users create programs by manipulating program elements graphically rather than by specifying them textually.
```
- https://en.wikipedia.org/wiki/Visual_programming_language

## Benefits of Node-Red
### Simplification
- As the name no-code/low-code indicates, coding is eliminated and programming is intuitively completed with a minimal number of operations needing to be used.
### Efficiency
- Node-RED flow editor takes care of building the application execution environment, library synchronization, the integrated development environment (IDE), and editor preparation so that you can concentrate on development.
### High quality
- High quality is the true value of flow-based and visual programming. <b>Each node provided as a component is a complete module that has been unit tested.</b>
### Open source
- Node-RED is an open source piece of software under the Apache2 license.
### Node-Red library
- Although Node-Red implement all aspects of CRUD operations but also provide placeholders for writing custom logic in NodeJs, for those who find it difficult to practically implement SOLID design principles.

## Node-Red alternatives
- Blockly by Google (https://developers.google.com/blockly)
- N8N (https://n8n.io/)
- Camunda (https://camunda.com/)
- Imixs Workflow (https://www.imixs.org/)

## Setup
- docker run -it -p 1880:1880 -v $PWD/data:/data nodered/node-red

## REST Implementation
![img.png](.imgs/img.png)

![img_1.png](.imgs/img_1.png)
## MongoDB CRUD Operation
### [Mlab](https://mlab.com/) - Mongo As A Service
![img_2.png](.imgs/img_2.png)
### Configure MongoDB in Node Red
#### Configure Mongo Instance in Node Red
![img_3.png](.imgs/img_3.png) 
#### Configure Collections & Operations
![img_4.png](.imgs/img_4.png)
#### CRUD Operations
![img_6.png](.imgs/img_6.png)
##### POST
![img_5.png](.imgs/img_5.png)
##### GET By ItemName
![img_7.png](.imgs/img_7.png)
##### GET All
![img_8.png](.imgs/img_8.png)

##  Kafka Integration
### [Cloudkarafka](https://www.cloudkarafka.com/) - Kafka As A Service
![img_10.png](.imgs/img_10.png)
#### Configure Kafka Cluster in Node Red
![img_11.png](.imgs/img_11.png)
#### Configure Producer
![img_12.png](.imgs/img_12.png)
#### CQRS Pattern
![img_13.png](.imgs/img_13.png)
#### POST Request
![img_14.png](.imgs/img_14.png)
![img_16.png](.imgs/img_16.png)
![img_17.png](.imgs/img_17.png)
#### GET Request
![img_15.png](.imgs/img_15.png)

## Placing Node Red in microservice architecture
![img.png](img.png)

## References
- https://en.wikipedia.org/wiki/Visual_programming_language
- https://subscription.packtpub.com/book/web_development/9781800201590/2/ch02lvl1sec05/node-red-benefits
- https://developer.ibm.com/blogs/top-5-reasons-to-use-node-red-right-now/