# AWS-Infra
Secure design for migration between AWS and on-prem infrastrucutre that insure auditable, accessible, secure, user-friendly solution to remotely access target systems (both EC2 instances in AWS and VMs in DCs)
![g1](https://user-images.githubusercontent.com/9371316/169713456-2d27be6a-bcbf-40e5-a452-34e3f3fb8c0c.jpg)


The Pros and Cons of Authentication and Authorization in place

Pros: 
    1- Extended AD on both AWS and on-prem provide high availability, scalability, and reliance on connectivity .
    2- Support multiple authentication and authorization mechanisms such as (SAML Federation, Mutual Authentication, AD)

Cons: 
    1- Extended AD on both AWS and on-prem affects the extra cost for deploying an AD replica on AWS.

