# Internet Protocols - Static and Dynamic Addresses

 ![EC2](https://github.com/BoyNovr/Static-Assets/blob/main/AMAZONEC2.PNG)

In this lab, we explore the use of both static public IP and dynamic public IP. In a case study, we play the role of a cloud support team receiving a complaint from a customer. The customer reports that their public IP constantly changes when they turn off instances to save costs. They explain that they have to power down instances when not in use.
We engage in hands-on practice by creating a new instance in the lab. After creating the instance, we power it down, and what happens is that the public IP vanishes. When we attempt to restart the instance, we realize that the public IP has changed. In conclusion, when we create a new instance by default, we receive a dynamic public IP.
The solution to this problem is easily creating a static public IP and attaching it to the EC2 instance. This way, the instance will obtain a persistent static public IP even when it's powered down."
