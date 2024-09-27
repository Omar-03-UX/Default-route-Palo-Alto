![image](https://github.com/user-attachments/assets/935093cd-3dcd-4941-8b88-7a0772ba875d)![image](https://github.com/user-attachments/assets/c8975a5a-e437-42f7-8afd-aa5887e87964)![image](https://github.com/user-attachments/assets/f0d0aa40-1317-475f-97b3-42c52008c5ae)# Default-route-Palo-Alto

<h2>Description</h2>
In this hands-on lab, we will create add a router on the outside zone which will be the default route, we will assign the ip address and its respective loopback addresses. Once we assign the default route on the router which will point the router to its next hop address. We will create a zone in Palo Alto. We will then add this default router in palo alto by creating another static route to route traffic to router 3 address for the incoming traffic. The interface added to the outside zone will then be added to the virtual router that was created in Palo alto for the internal zone. Once we create the objective of creating a default route we will then redistribute the routes to allow both the internal and outside networks to communicate. As both zones have different routing protocols, in order for both of them to communicate its important that the route redistibution is created to enable seamless communication. 

<br />

<h2>Languages and Utilities Used</h2>

- <b> Eve ng </b> 
- <b>VM Workstation </b>
- <b> Palo Alto Firewall </b>

<h2>Environments Used </h2>

- <b> Vm Workstation Pro </b> 

<h2>Program walk-through:</h2>

<p align="center">
Setup devices <br/>
<img src="https://i.imgur.com/I2JJWK2.png" height="80%" width="80%" alt="Palo Alto route"/>
<br />
<br />

<p align="center">
Setup devices <br/>
<img src="https://i.imgur.com/45pAr7e.png" height="80%" width="80%" alt="Palo ping"/>
<br />
<br />

<p align="center">
Setup devices <br/>
<img src="https://i.imgur.com/vOrhSju.png" height="80%" width="80%" alt="Palo ping"/>
<br />
<br />


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
