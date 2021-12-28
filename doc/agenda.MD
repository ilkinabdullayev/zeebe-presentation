# Agenda

- Wild West Integration
- What is workflow engine?
- Example of retail
- Example of our project

- Scalable workflow engine?


# Zeebe vs Camunda

------------
No Database bottleneck.
a. The state is stored as events distributed throughout the cluster, history is exported.
Horizontally scalable.
a. adding more nodes = better performance. (Camunda Platform’s Database prevents this)
Event Based architecture.

Camunda Platform isn’t going anywhere! It’s still a great, very mature engine that has functionality beyond Zeebe currently. The future for it is more about being able to embed it in services or to self host it as a certain service.
--------------


# Notes

You can implement Zeebe for cloud native architecture like for FAAS, microservices.

https://www.youtube.com/watch?v=6bF_1w6GeEI
https://jit.at/zeebe-meeting-the-new-kid-in-town/?lang=en
https://tallyfy.com/workflow-engine/
https://github.com/camundacon2019/zeebe-ft-demo
https://workflowengine.io/blog/why-use-a-workflow-engine/
https://www.cflowapps.com/workflow-engine/