# DevOpsInteriewPreparation

## What are the four key benefits of DevOps and how can we utilise them (provide use cases or examples)
- Flexibility 
- Ease of use
- Robustness
- Cost

## What is public cloud, Hybrid cloud and private cloud (use cases)
- Public cloud consits of services and resources made publically available by the provider. These allow resources and responsibilities to be transferred offsite. Common providers are AWS, Azure, and Google Cloud.
- Private cloud consists of on premises infrastructure and cloud specifically for one organisation. This allows greater control of the system, which is especiially useful when handling data subject to regulations and laws. Private clouds also have lower latency than public clouds
- Hybrid cloud utilises a mixture of both public and private cloud. This allows organisations to reap all the benefits of public cloud such as removing load off local resources, whilst taking advantage of the control the private cloud gives for sensitive assets. Resources can also be migrated between the two easily and more gradually than starting from scratch.

![Types of cloud](https://github.com/jackingham/DevOpsInteriewPreparation/blob/main/image.png?raw=true)



## What is Monolith Architecture, 2 tier and Micro-services Architecture (use cases and benefits )

- Monolith archticture is when all frontend, back end and database processes are combined into one unit. Whilst this is suitable for a smaller organisation's system(s), dependencies are formed between layers which stifles future changes and means the system can fail from any point.
- 2 tier architecture separates the front end side from backend and data processes this recuction in dependancies creates a more resilient system.
- Microservices break down the unit even further into individual componets. Whilst this introduces a lot of complexiites and makes testing each unit harder, the reduced depenadancy means if one microservice fails the rest of the services can function normally. The services can all also all use different technologies as they do not rely on a common database backend.

![Microservices](https://github.com/jackingham/DevOpsInteriewPreparation/blob/main/microservices.jpg?raw=true)


