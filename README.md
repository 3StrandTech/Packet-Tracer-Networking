<h1> Packet Tracer Networking Project </h1> 

<h2> Project Overview </h2>

<br> A simple network project demonstrating a basic network with three PCs connected to a switch with a router connected to the switch. The router will function as a DHCP server with a pool of IP addresses to hand out to the PCs. <br>

<h2> Project Objective </h2> 

<br> Configure a simple three PC network with a connected switch and router and then have each PC ping each other to verify connectivity. <br>

<br> <h2> Project Steps </h2> <br>     

<br> Step 1: Place three PCs, a switch and a router and connect all devices with appropriate network cables <br>
<br> <img width="364" alt="Step 1 Screenshot" src="https://github.com/user-attachments/assets/15fd7567-0b9c-4866-ba82-01233671849e" /> <br> 


<br> Step 2: Configure the connected router interface with a static IP to avoid routing conflicts <br> 
<br> <img width="897" alt="Step 1 Screenshot" src="https://github.com/user-attachments/assets/398d4441-b259-4b18-9754-f6e3416d0a8d" /> <br> 

<br> Step 3: Configure connected router with DHCP settings including: <br>
<br> -Excluded addresses, Pool name, Default router <br> 
<br> -DNS-Server, TFTP Server, Full DHCP Network Pool <br>
<br> <img width="887" alt="Step 3 Screenshot" src="https://github.com/user-attachments/assets/46710916-105b-42ca-b9f3-861542312efa" /> <br>

<br> Step 4: Once DHCP is configured, configure PCs to obtain IP address by running ipconfig /renew from the PC Command Prompt <br>
<br> <img width="725" alt="PC1 DHCP Renew" src="https://github.com/user-attachments/assets/1b284ea1-32c1-497a-9f23-4668f8abbf1e" /> <br>
<br> <img width="826" alt="PC2 DHCP Renew" src="https://github.com/user-attachments/assets/9f177b61-b7de-4a5a-9b4c-987e652f964e" /> <br>
<br> <img width="799" alt="PC3 DHCP Renew" src="https://github.com/user-attachments/assets/061c87e2-49b0-4c7e-be7a-48a7ea56b158" /> <br>

<br> Step 5: Once each PC has an IP address, verify connectivity by having each PC ping one of the other PCs
<br> <img width="842" alt="PC1 Ping Verify" src="https://github.com/user-attachments/assets/81a0a95c-70fe-4de5-aead-f085dfe85140" /> <br>
<br> <img width="851" alt="PC2 Ping Verify" src="https://github.com/user-attachments/assets/3b7d3c49-ef99-45a1-9746-7c4e72e6f42b" /> <br>
<br> <img width="806" alt="PC3 Ping Verify" src="https://github.com/user-attachments/assets/42985430-5bba-487e-b38f-cf2636f57c99" /> <br>

<br> Step 6: Verify DHCP allocations on the router by using the show dhcp bindings command from the router CLI <br> 
<br> <img width="938" alt="Show DHCP Binding" src="https://github.com/user-attachments/assets/77777d9d-f94c-42fd-9e71-1b02c36a8f62" /> <br>

<h1> Lessons Learned </h1>

Valuable exercise. It helped me learn the logic regarding routing and switching. I especially learned the difference between a layer 2 and layer 3 device because I kept trying to put IP addresses on the switch interfaces. Once I did some research and realized that all a switch does is forward Layer 2 frames, connectivity was quickly established between the PCs and the whole concept made sense to me. I look forward to expanding this network to greater complexity and functionality as I continue my journey. Thanks for investigating this project with me.


<h1> Tools Used </h1>
-Cisco Packet Tracer 
<br> -Cisco IOS (Internetwork Operating System) <br>
<br> -Command Prompt (from Windows OS via Cisco Packet Tracer) <br> 

