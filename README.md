# SpringOne Platform 2018 :: Spring Cloud on PKS 
S1P :: Docs about Spring Cloud on PKS presentation 

This document goes over the features covered in the presentation. 
The following repositories were deployed into an instance of PKS (Pivotal (K)Container Services), but the same application be deployed to other Kubernetes installations. 

- [s1p_gateway]()
- [s1p_concerts-service]()
- [s1p_tickets-service]()
- [Spring Boot Admin]()

In order to deploy each service into PKS, we used [Jenkins X](http://jenkinsx.io) 

<IMAGE>
  

# Deploy yourself

1) Configure your kubernetes cluster to get access using kubectl
2) Install Jenkins X (Getting Started)
3) Fork [s1p_gateway]()
  3.1) jx import (inside the cloned directory)
  3.2) Wait for the pipeline to deploy the Spring Cloud Gateway
4) Fork [s1p_concerts-service]()
   4.1) jx import (inside the cloned directory)
   
   
