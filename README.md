# CI/CD with CircleCI and GKE

This is the sample code accompanying my blog post on building a Continuous
Integration and Delivery (CI/CD) pipeline using CircleCI and Google
Kubernetes Engine (GKE).



## Docker Image

Run:

    docker build -t node-circle-gke .

Run:

    docker run -p 3000:3000 node-circle-gke
