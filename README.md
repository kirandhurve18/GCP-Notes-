# GCP-Notes-

## GO into the VM (INSATNCE):
 Hit command : 
 ````
ssh-keygen -t rsa -b 4096
````
so this command will genrate the id_rsa and id_rsa.pub .
you can copy this key in the local machine .

## WANT TO ADD THE PORT TO THE VM SUPPOSE 3000:

you have to do that , 
first create a tag in the VM 

<img width="1206" height="583" alt="image" src="https://github.com/user-attachments/assets/1bcf5d24-4b18-4a04-b72b-feb3fc1c7277" />

After that create a firewall rule :
For that you have to go to the VCP Network :
ADD Firewall rule - 
then create firewall rule :

<img width="805" height="535" alt="image" src="https://github.com/user-attachments/assets/d421578e-95cc-4981-aa27-49cda88c6e3c" />

<img width="691" height="810" alt="image" src="https://github.com/user-attachments/assets/543eea24-f6a6-4f21-b10b-ade31101347c" />

<img width="667" height="615" alt="image" src="https://github.com/user-attachments/assets/194ac2a7-727a-441f-91b0-72d9cff26001" />

<img width="592" height="727" alt="image" src="https://github.com/user-attachments/assets/d967c303-8988-422a-b2c0-de18861456c8" />

This is how we can attach port to 3000 to specific instance .

