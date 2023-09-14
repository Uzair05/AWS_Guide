# Summary and list of AWS services used

I will try to list out all the services used, and try to draw out how each component is connected to each other.
By: Uzair

---

## List of Services - Singapore

### 1. Elastic Beanstalk

Used to host servers. Servers are Node Js apps which make use of other AWS services \(e.g. S3\) no redundant services are kept on Node Js app.

- Apiserver-env  
  Handles the Boar Detection Server
- Crayfishbackend-env  
  Handles the Crayfish Backend Server

---

-> Tips  
Set the balanced load to 0, 0 to turn off server and save cost.  
![Img1](Mojo/Images/1.1.png)  
![Img2](Mojo/Images/1.2.png)

## List of Services - Hong Kong
