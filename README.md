<p align="center">
<img width="1440" alt="image" 
  src="https://github.com/RMBaez/VM-Web-Server-Deployment/assets/170957530/556252cb-981e-4992-9262-305d5013b854">


</p>

<h1>Azure: Create a Virtual Machine and Deploy a Web Server</h1>
In this tutorial, we create a Virtual Machine in Azure to deploy a web server, specifically a Nextcloud server. We will also observe how to use Bastion to connect to the machine via SSH, without exposing an external port to the Internet, and then installing a simple Nextcloud server and make the Virtual Machine available.  <br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure VM
- Virtual Network
- Bastion
- Network Protocol (SSH)

<h2>Operating Systems Used </h2>

- Ubuntu Server
- Nextcloud

<h2>High-Level Steps</h2>

-Task 1: Create a Resource Group

-Task 2: Create a Virtual Network and a subnet

-Task 3: Protect a subnet using a Network Security Group

-Task 4: Deploy Bastion to connect to a Virtual Machine

-Task 5: Create an Ubuntu Server Virtual Machine

-Task 6: Install Nextcloud by connecting via SSH using Bastion

-Task 7: Publish an IP

-Task 8: Create a DNS label

<h2>Actions and Observations</h2>

<p>
<img width="1440" alt="image" src="https://github.com/RMBaez/VM-Web-Server-Deployment/assets/170957530/f71be315-3a9c-4d99-b026-840fd326bb64">
<img width="1440" alt="image" src="https://github.com/RMBaez/VM-Web-Server-Deployment/assets/170957530/66735504-bc37-435f-8bc4-c0ab5969e242">

</p>
<p>
Task 1.
</p>
<br />

<p>
<img width="1440" alt="image" src="https://github.com/RMBaez/VM-Web-Server-Deployment/assets/170957530/7624304b-3c63-46f0-bc48-4dea52f67de3">
<img width="1440" alt="image" src="https://github.com/RMBaez/VM-Web-Server-Deployment/assets/170957530/a37ee951-5349-4325-8600-72fd2954ab71">
<img width="1440" alt="image" src="https://github.com/RMBaez/VM-Web-Server-Deployment/assets/170957530/5044e55a-3c45-4ccd-bd44-02ae47806a37">

  
</p>
<p>
Task 2.
</p>
<br />

<p>
<img width="1440" alt="image" src="https://github.com/RMBaez/VM-Web-Server-Deployment/assets/170957530/d20fd8e1-17a9-4ef9-89b5-e568b3e26947">
<img width="1440" alt="image" src="https://github.com/RMBaez/VM-Web-Server-Deployment/assets/170957530/03bf3e9d-f270-4c0a-883d-5b609eb98415">
<img width="1440" alt="image" src="https://github.com/RMBaez/VM-Web-Server-Deployment/assets/170957530/a293e2bf-9bd0-4b6c-bcbf-ac9aef403b37">


</p>
<p>
Task 3.
</p>
<br />


<p>
<img width="1440" alt="image" src="https://github.com/RMBaez/VM-Web-Server-Deployment/assets/170957530/74581312-7e76-4e6f-8a9a-81c030d008d6">
<img width="1440" alt="image" src="https://github.com/RMBaez/VM-Web-Server-Deployment/assets/170957530/3a337009-05ef-4a98-85b1-4b09f0ea061c">
<img width="1440" alt="image" src="https://github.com/RMBaez/VM-Web-Server-Deployment/assets/170957530/467134de-71d3-41aa-8556-3399b3c2c9cf">
<img width="1440" alt="image" src="https://github.com/RMBaez/VM-Web-Server-Deployment/assets/170957530/8ec44fa2-d8a2-409e-89c8-b37dec1016e1">


</p>
<p>
Task 4.
</p>
<br />


<p>
<img width="1440" alt="image" src="https://github.com/RMBaez/VM-Web-Server-Deployment/assets/170957530/f1e68674-93ab-4bf7-8111-e28bc506523c">
<img width="1440" alt="image" src="https://github.com/RMBaez/VM-Web-Server-Deployment/assets/170957530/888a0f97-afb1-4441-a07c-ab9e1e247ed4">
<img width="1440" alt="image" src="https://github.com/RMBaez/VM-Web-Server-Deployment/assets/170957530/e4b4a32c-a4ca-4b36-94d1-7b1bf82115d9">
<img width="1440" alt="image" src="https://github.com/RMBaez/VM-Web-Server-Deployment/assets/170957530/ed39852d-800e-48fc-9a46-18840ac308b5">
<img width="1440" alt="image" src="https://github.com/RMBaez/VM-Web-Server-Deployment/assets/170957530/62ae8e2a-19eb-47c2-b8aa-b166a94133e0">


</p>
<p>
Task 5.
</p>
<br />

<p>
<img width="1440" alt="image" src="https://github.com/RMBaez/VM-Web-Server-Deployment/assets/170957530/c12b2099-50df-4773-aad5-ee64fb87b302">
<img width="1440" alt="image" src="https://github.com/RMBaez/VM-Web-Server-Deployment/assets/170957530/dc590f6f-9928-4f14-beed-6f57ef908dee">
<img width="1440" alt="image" src="https://github.com/RMBaez/VM-Web-Server-Deployment/assets/170957530/88d6788b-d061-4fce-a063-fcf9880f680e">
<img width="1440" alt="image" src="https://github.com/RMBaez/VM-Web-Server-Deployment/assets/170957530/e6107b8a-09f7-4e5d-a796-058786ddface">
<img width="1440" alt="image" src="https://github.com/RMBaez/VM-Web-Server-Deployment/assets/170957530/73c471d3-c3ac-4cce-9d88-5b18b5757101">
<img width="1440" alt="image" src="https://github.com/RMBaez/VM-Web-Server-Deployment/assets/170957530/b3c4bbca-198b-4345-b742-e37e3de13241">



</p>
<p>
Task 6.
</p>
<br />


<p>
<img width="1440" alt="image" src="https://github.com/RMBaez/VM-Web-Server-Deployment/assets/170957530/9453de4e-18b5-404e-b8ba-7c14be5ec788">
<img width="1440" alt="image" src="https://github.com/RMBaez/VM-Web-Server-Deployment/assets/170957530/8c09a4ee-179c-4acc-9a33-09f963d5bd46">
<img width="1440" alt="image" src="https://github.com/RMBaez/VM-Web-Server-Deployment/assets/170957530/ecdc2629-8b43-47a0-8bc4-8317259b73fc">
<img width="1440" alt="image" src="https://github.com/RMBaez/VM-Web-Server-Deployment/assets/170957530/2e375f14-bea1-4b84-9b1c-3f03134490ab">


</p>
<p>
Task 7.
</p>
<br />


<p>
<img width="1440" alt="image" src="https://github.com/RMBaez/VM-Web-Server-Deployment/assets/170957530/a7b4a909-76cb-4d5d-b662-d7179dea0a31">
<img width="1440" alt="image" src="https://github.com/RMBaez/VM-Web-Server-Deployment/assets/170957530/bde53088-4c5d-4186-bcc3-1258560a3151">


</p>
<p>
Task 8.
</p>
<br />
