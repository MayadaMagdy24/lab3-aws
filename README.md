# lab3-aws
1- jump-host public ip 
![Screenshot (699)](https://user-images.githubusercontent.com/93229250/227976233-de2ea1e6-e646-4468-b975-f6e89a264b4e.png)

- private instance (web1) ip
![Screenshot (700)](https://user-images.githubusercontent.com/93229250/227976462-c52db6a9-01e2-4278-bb21-b5ae114a2977.png)

-ssh to jump-host
![Screenshot (701)](https://user-images.githubusercontent.com/93229250/227976710-230263f2-a734-4bc1-8719-45ccc476cb9c.png)

-ssh from bastion to private machine 
![Screenshot (702)](https://user-images.githubusercontent.com/93229250/227976965-ee6d0612-b14c-4c79-9caa-924b99dac9c6.png)


2- the second private instance
![Screenshot (703)](https://user-images.githubusercontent.com/93229250/227980199-cf87de95-eef5-4fe1-bde8-c9be07801eee.png)

- the second jump-host 
![Screenshot (704)](https://user-images.githubusercontent.com/93229250/227980383-0161a144-7647-4547-9bf0-6d8718535e98.png)

- public load balancer
![Screenshot (705)](https://user-images.githubusercontent.com/93229250/227980508-06baec2a-21b7-41b4-b137-c29f077d36ed.png)

- private load balancer
![Screenshot (706)](https://user-images.githubusercontent.com/93229250/227980681-2363d2fa-87b6-40db-b674-1711917fde8c.png)

- public targets group are healthy
![Screenshot (711)](https://user-images.githubusercontent.com/93229250/227982784-3565b43d-4b40-4024-a0d5-893d7ba98560.png)

- private targets group are healthy
![Screenshot (710)](https://user-images.githubusercontent.com/93229250/227982157-78842302-8d80-4e30-927c-0b122ce4b984.png)

- nginx configuration in both jump-hosts
![Screenshot (709)](https://user-images.githubusercontent.com/93229250/227981443-59c04147-4694-412b-95c4-8ef2e86fdb51.png)

- dns of public load balancer
![Screenshot (708)](https://user-images.githubusercontent.com/93229250/227981067-a76474e0-17c6-4386-a32e-288c3a75e414.png)

