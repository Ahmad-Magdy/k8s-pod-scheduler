## Kubernetes(K8S) Pod Scheduler
A simple and lightweight go tool that can run on top of K8s to schedule and run long-running tasks.

It's something smaller and simpler than Apache Airflow for small or simple tasks. Instead of using a workflow management tool with a lot of overhead, this tool can be more fit for simple and small jobs.
 

### Use cases of this package
When a user wants to read jobs from a remote-store and schedule them accordingly.




### TODO:
- Store the registered jobs state in a persistent store instead of storing them in memory.
- Provide API to add, update, and remove tasks. 
 