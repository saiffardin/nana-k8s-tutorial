# Deploy k8s app:

A simple setup to of web-app and it's database. 
We're going to deploy 2 applications **mongoDB** and **mongo-express**

1. Create *mongoDB* pod(deployment).
    - in order to talk to the pods create *service*.
    - mongoDB will have an **internal service**, means -
        - no external requests are allowed to the pod.
        - only components inside the same cluster can talk to it.

1. Create *mongo-express* deployment.
    - here we need *db-url*, *db-user* and *db-password*
    - as we need mongo express accessible through browser we need a **external service** here.



![8.png](./images/8.png)
![9.png](./images/9.png)
