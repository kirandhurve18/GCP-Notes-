## AUTOSCALING GROUP 

### Prereuisite 

First you need to create instance template , 

### create instance tepmlate with specific configuration 

<img width="991" height="540" alt="image" src="https://github.com/user-attachments/assets/2cb18538-bdaf-48bf-a76f-c3775860ed2f" />

<img width="985" height="561" alt="image" src="https://github.com/user-attachments/assets/acc59432-234a-49a9-97fc-da4c5fd69186" />

<img width="992" height="132" alt="image" src="https://github.com/user-attachments/assets/9936b59c-9ec9-4280-8785-a7056fadd40c" />

<img width="988" height="297" alt="image" src="https://github.com/user-attachments/assets/21111912-dd2f-4481-be78-e8d37146153d" />

<img width="993" height="323" alt="image" src="https://github.com/user-attachments/assets/deef91f2-8ede-4513-bf45-cfd7f02b38e6" />

<img width="908" height="552" alt="image" src="https://github.com/user-attachments/assets/c377ff84-2e22-4dad-ad67-0e718be6ca81" />


### Instance group 

<img width="1273" height="614" alt="image" src="https://github.com/user-attachments/assets/d1cc5669-860a-4471-b867-68373127ddd9" />

<img width="890" height="667" alt="image" src="https://github.com/user-attachments/assets/a06362bc-118c-471d-9dac-a81dc221dede" />

<img width="903" height="532" alt="image" src="https://github.com/user-attachments/assets/2bac59e7-363f-4c8b-a6f3-2cb71ca3896e" />

### CREATE A LOAD-BALANCER :

Health check - suppose we have 3 vm , due to some interfaerence 1 vm got down , to avoid this the load balancer perform a health check ,
in this health check do is , they check the vm in every 5 sec , if he found something wrong , they remove the vm , and whatever traffic will 
transfer to the next two VMs. 

#### if the loadbalnacer is not working check the firewall rule , if not create a firewall rule .

Create load balancer :

1. application load balancer
2. public facing load-balancer
3. GLOBAL workload - it will solve all regional load balancer work Regional load balancer - only region specific
4. clasic load balancer.
5. Configure load balancer .
6. Configure  frontend for load balancer

<img width="1172" height="677" alt="image" src="https://github.com/user-attachments/assets/c76d4ec0-1d3e-4a19-9e0e-9a786208d522" />

7. Configure backend for the load balancer .

8. 

 





