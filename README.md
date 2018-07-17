# CI/CD with CircleCI and GKE

This is the sample code accompanying my blog post on building a Continuous
Integration and Delivery (CI/CD) pipeline using CircleCI and Google
Kubernetes Engine (GKE).



## Docker Image

Build:

    docker build -t node-circle-gke .


Build with version number

    docker build -t node-circle-gke --build-arg COMMIT_REF=23sdfsdf23 --build-arg BUILD_DATE=2018-07-01 .

Run:

    docker run -p 3000:3000 node-circle-gke
