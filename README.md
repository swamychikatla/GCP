# GCP
In AWS we have EC2. In GCP we have compute Engine.
GCP is product from google.
To access GCP we need to create account.
https://console.cloud.google.com/
Above one is the url to access. First we need to provide out gmail userid & password

![image](https://github.com/swamychikatla/GCP/assets/40513374/9daeb43b-4c88-41d9-a58f-3534d635ca04)

Click on Activate button to access the 300$credit.

![image](https://github.com/swamychikatla/GCP/assets/40513374/4cfa5e4f-3ae9-4ca8-bb27-808836bffe76)

Provide Country name accept Terms of service and click on continue

![image](https://github.com/swamychikatla/GCP/assets/40513374/325f0972-f6ed-4ce8-b6b5-b8111fc19da0)

Account type as individual and Tax information as Unregistered individual

![image](https://github.com/swamychikatla/GCP/assets/40513374/577a1f99-18cd-4351-8619-598f9434122d)

Provide card details and click on Start My Free Trail.

Why we need Operating System?
We have one program created in some language like phyton or php,... and you want to run this program you need the operating system. Without operating system it is impossible to run the program. But if you want to run or boot the operating system we need the RAM and CPU. Without RAM and CPU you wont able to boot the operating system. If you want to install the operating system you need the HardDisk. HardDisk is typically known as Storage. (Storage is permanent, For temporary memory (RAM) is used). Typically RAM and CPU is known as Compute or Compute Unit. But if you want, data needs to store some data permanently (OS is store permanent after reboot also it doesn't remove)we need HardDisk typically known as storage or Storage Unit. If you want to run the program, sometimes program is also known as services. For example. one of the name of the service called as Web service, because you want to launch a website or App service, If you want to launch some app of java or python, etc... If you want to launch a program called Database Services you need the Operating System. For Operating system you need Compute Unit and Storage Unit. We need it so we need to purchase it as these are the devices invest your money to run the program.
We have a Developer team and they deveoped a Website, Application, Database ,... we need to host our website for customers. (We have a client in the internet and we want the client to visit the website for example, ecommerece website.
To launch a website you need a hardware. This hardware needs to be purchase, we require real public IP, we real internet connectivity, firewall, network devices, we need to hire a technical guy, databases team, IT involment, all we have to invest.

Now there are more thirdparty now a days more than decade. Now we dont want to invest upfront in our IT infrastructure. I dont want to hire some guys who manage by Operating system, Databases, My Security, My firewall, My network, My Ram, CPU. I don't want to purchase these items. There are lot od companies in the market who are doing business for us. Companies are called as Service Providers. They provided services to us. Companies are known as providers and they are providing services. So they are called as Service Providers.

What are the services: If we go and ask provide the RAM and CPU. Yes they will provide us compute. Typically they use a term called compute as a service and they will provide. Don't need to give upfront amount. For example, for this compute unit if you purchase in real world it might cost 1000$. But here you need to pay anything as we don't no how much we are going to utilize more or less. This company work on a model for us and the model is called custome model (Pay as you go). As much you use, you have you pay. Depends on which service you need if you need RAM and CPU, ask we need compute service. If you need storage , It is storage as a service. We have some many like network a service , container service, Kubernetes service, Firewall as a service, Docker as a service, Function as a service, Machine learning a services. 

Previously called as Service Providers. Now a days we use a term called Cloud computing.

Different types of Cloud Computing:
Public Cloud
Private Cloud
Hybrid Cloud.

Anyone can use it, it is public cloud
AWs from Amazon , Azure from Microsoft, Google Cloud Platform(GCP) is a product from Google. It is offering us a public cloud. It means anyone after create a account in platform as a indidivual or any other company can use the computing power of Google.

RAM and CPU, Harddisk, Networking are called as Resources.

**Public Cloud Computing**
Login to GCP
![image](https://github.com/swamychikatla/GCP/assets/40513374/49822867-1afe-4576-9180-f691a858e2e3)
We can demand google we need particular resource

                              As-A-Service
On-Demand --> Resources ---> Compute (RAM/CPU)
                        ---> Storage (HardDisk)
                        ---> Network (Router)


Run or Launch OS in our Laptop is called Barematel 
Launch OS on top of Virtual machine is called Virtualization
Launch OS on top of Container is called as Containerization
Launch OS on top of Cloud is called Cloud Computing. 
   (In Cloud computing we didn't call the term called OS. We call it as Instances) In some of cloud computing it also called as Virtual Machines.
    In GCP normally we call as Virtual machine.
    If we go to Google cloud and say i want a compute service, i want to launch my virtual machine we have a product or service called Compute as a service. On top of the Compute as a service we can go and launch our virtual machine. The name of the service is called Google Compute Engine.

In the console page, we have a navigation menu 
![image](https://github.com/swamychikatla/GCP/assets/40513374/feba8e16-8e81-4496-8d1c-bd337bb504d9)
Click on 3 lines, we can see all services
![image](https://github.com/swamychikatla/GCP/assets/40513374/c9735c9c-37e3-479d-abe8-35675039fabe)
Here we can see Compute Engine
![image](https://github.com/swamychikatla/GCP/assets/40513374/ea889fb5-4fc0-4f40-b5d1-9b8c219ace35)

If you want to utilize storage, we have different types of Storage (Object storage, block storage, file storage)
Storage is mainly, to store data permanently. When ever you store your data permanently means after you reboot also it won't delete means permanent. In this we call it as persistant.

We have a different types of storage in GCP console depends up on the requirement:
![image](https://github.com/swamychikatla/GCP/assets/40513374/73ea7c21-f528-4633-8131-fefd04b8b7dc)

Use case is different and requirement is different.

For network, we have a networking as a service called VPC network.
![image](https://github.com/swamychikatla/GCP/assets/40513374/25385639-5715-47c7-8438-53eea5218062)
VPC is the main service give you firewalls , routers , IP address based on the requirement.

Storage where you install your operating system is known as Block storage.
Hard Disk in laptop typically known as Block storage.
Hard Disk is Block storage.

In Compute Engine we have a product called Disks
![image](https://github.com/swamychikatla/GCP/assets/40513374/98e0a574-755c-4801-88a9-96505c3f61f7)
If you go fir Disks, it is Hard Disk or it is block storage.


---> In AWS, Google Compute Engine is known as EC2

-----------> Block storage is known as EBS

-----------> VPC is known as VPC.

How to use Google Compute Engine (GCE)
--------------------------------------
![image](https://github.com/swamychikatla/GCP/assets/40513374/d98b1fcf-a170-4d32-b30a-a12e4cf77a3a)
This service is used to launch a instance.
![image](https://github.com/swamychikatla/GCP/assets/40513374/947a227b-a354-447c-8725-c4f4071523d0)
OS will launch inside the datacenter of Google.

Google Cloud Platform(GCP) is running on one of the Datacenter of Google
Google data centers are the large data center facilities Google uses to provide their services, which combine large drives, computer nodes organized in aisles of racks, internal and external networking, environmental controls (mainly cooling and humidification control), and operations software (especially as concerns load balancing and fault tolerance).
Google owns and operates data centers all over the world, helping to keep the internet humming 24/7. Learn how our relentless focus on innovation has made our data centers some of the most high-performing, secure, reliable, and efficient data centers in the world.

If i need RAM & CPU, Google will provide from the datacenter only.

Typically, when as a user if you go to google and say i  want to use your Cloud platform
We are the user, in cloud world any user is known as user who use the cloud
And User also called as Tenant/Client.

User/Tenant/Client----------------------------->GCP (Data Center)

Google Datacenters located in almost all countries.
In India we have one data ceter in Mumbai.
When ever they pick any country they launch atleast 2 or 3 data centers. where ever they launch the data centers. if you pick mumbai, they launch 3 data centers, 1a, 1b, 1c
They use the call it as region. Here mumbai is a region
Asia is one continental work on multi regional, one is mumbai and one is Singapore
In Mumbai there are 3 data centers. 1a, 1b, 1c.
This datacenters are also called as Zone. 1a is a zone.
Cloud locations : Google Cloud has added new regions this year: Berlin (Germany), Doha (Qatar), Dammam (Saudi Arabia). Our private, software-defined network provides fast and reliable connections to users around the world.
![image](https://github.com/swamychikatla/GCP/assets/40513374/e0ec342f-6e3e-433f-ade2-fde0f4a569af)

![image](https://github.com/swamychikatla/GCP/assets/40513374/2f007bd7-80df-42ce-a454-5f23bf9b213d)









