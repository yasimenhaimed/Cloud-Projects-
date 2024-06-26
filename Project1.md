# FIRST PROJECT WEB STACK IMPLEMENTATION

## WEB STACK IMPLEMENTATION (LAMP STACK) IN AWS
A technology stack refers to a carefully selected combination of frameworks, programming languages, databases, and other tools used to build a software product. These components are chosen to work seamlessly together, creating a cohesive and efficient system.
For instance, the LAMP stack, a stalwart of web development, encompasses:
- Linux: The operating system
- Apache: The web server
- MySQL: The database management system
- PHP: The programming language

Each element in the LAMP stack fulfills a distinct role and synergizes with the others to furnish dynamic and interactive websites and web applications.


After logging into AWS, you'll see the main console, where you can find all the available services listed for you to navigate through.

<img width="877" alt="Screenshot 2024-04-15 at 9 47 35 PM" src="https://github.com/yasimenhaimed/Cloud-Projects-/assets/135265745/7cb11bcc-7967-48c5-8038-58fbcdc2591c">

Before creating an EC2 instance, choose the region closest to you. Consider factors like speed, security, and cost when making your decision.

<img width="700" alt="Screenshot 2024-04-15 at 9 47 12 PM" src="https://github.com/yasimenhaimed/Cloud-Projects-/assets/135265745/65dab39f-769c-477e-9957-a00f691b2cb4">



**Launch a new "EC2" instance of t2.micro family with Ubuntu Server 20.04 LTS(HVM) 64 bit**

<img width="1171" alt="Screenshot 2024-04-15 at 9 54 25 PM" src="https://github.com/yasimenhaimed/Cloud-Projects-/assets/135265745/86c4c622-84e9-439f-b005-812e8f10e7bf">



**Next: Configure Instance Details**

Before you launch an instance, you need to select a key pair which is then required for SSH access to the Server.


<img width="810" alt="Screenshot 2024-04-15 at 10 29 31 PM" src="https://github.com/yasimenhaimed/Cloud-Projects-/assets/135265745/2853b1df-4be2-4470-94a6-ae8cea1017c4">

When you launch an instance from an AMI, a root storage device is automatically created. This device contains everything needed to boot the instance. However, you can also add or configure additional storage volumes alongside the root device. These additional storage volumes are known as block devices and can be specified during the instance creation process.

<img width="806" alt="Screenshot 2024-04-15 at 11 29 21 PM" src="https://github.com/yasimenhaimed/Cloud-Projects-/assets/135265745/b9331a1e-1d62-4139-820f-82b467a52e1a">




Now, it's time to check the status of your instance. Click on your instance to see whether it's up and running or still in the process of being launched (pending). If your instance is running, you can proceed to view its details and access its information.


<img width="1273" alt="Screenshot 2024-01-30 at 9 30 06 PM" src="https://github.com/yasimenhaimed/Cloud-Projects-/assets/135265745/aa474a4b-3c71-4367-aa5d-df2968d337e8">








