# AWS DMZ: CloudWatch Monitoring & Split-Tunnel VPN


-Architected and implemented a real-world corporate DMZ infrastructure using AWS VPC, emulating front-end and back-end firewalls through the configuration of Network ACLs (NACLs) and Security Groups, adhering to the principle of least privilege. Implemented public and private subnets, Internet Gateway, NAT Gateway, and custom route tables to achieve network segmentation and resource isolation. 

-Deployed and configured AWS Linux EC2 instances in a tiered architecture: • DMZ subnet: Web server (Apache), mail server (Postfix), and DNS server (BIND) • Internal subnet: Application server (Tomcat) and database server (PostgreSQL) Implemented a bastion host with SSH agent forwarding for secure administration. Set up AWS Client VPN with split tunneling to simulate real-world remote employee access scenarios.

-Enhanced security monitoring capabilities by implementing a CloudWatch dashboard, featuring real-time tracking of failed SSH attempts across DMZ, and VPN connection attempts with custom metric filters and alarms. Troubleshooted DNS Resolution Issues, and Business Hour and Off-Hour VPN Metric Filters. 


[Project Posted on Medium: "AWS Security Engineering: Building a Corporate DMZ Architecture (Using Free Tier Resources)" by Soel Kwun](https://medium.com/@cybersoel/aws-security-engineering-building-a-corporate-dmz-architecture-using-free-tier-resources-e4f05354b493)





<h1 align="center">Summary Diagram</h1>


<p align="center">
<br/>
<img width="750" alt="Portfolio" src="https://i.imgur.com/DLrpFEj.png">
<br />
</p>





