<h1>AWS Solutions Architect </h1>

<h2>Creating a NAT Gateway in AWS - Windows server</h2>

- <b>Create a Virtual Private Cloud (VPC) in the US East (N. Virginia) us-east-1 region  </b>
- <b>Create private and public subnets </b>
- <b>Create Internet Gateway </b>
- <b> Create a public Route table and configure  </b>
- <b>Launch a Windows EC2 instance using the public subnet </b>
- <b>Launch a Windows EC2 instance using the private subnet </b>
- <b>Connect to both the public and private EC2 instances and test internet connectivity </b>
- <b>Create a NAT Gateway </b>
- <b>Update Route table and configure NAT Gateway </b>
- <b>Test internet connectivity for the EC2 instance using the private subnet </b>

<h2>Expected Outcomes</h2>
The EC2 instance using the private subnet does not connect to the internet until the NAT Gateway is set up and connected to the Route table
<br />

<h2>Languages and Utilities Used</h2>

- <b>AWS Interface </b>
- <b> Virtual Machine (Windows server) </b>

<h2>Project walk-through:</h2>
<p align="center">
Creating a VPC <br/>
<img width="940" height="437" alt="image" src="https://github.com/user-attachments/assets/71493bc1-b120-4522-8eea-21e8650229a3" />
<img width="940" height="501" alt="image" src="https://github.com/user-attachments/assets/9dfd788d-cff8-43ef-b117-cbb5b6822f6d" />
<br />

<p align="center">
Creating a Subnet <br/>
<img width="940" height="503" alt="image" src="https://github.com/user-attachments/assets/4b6fe75c-f282-4d4a-81dc-f5e274bbb356" />
<img width="940" height="471" alt="image" src="https://github.com/user-attachments/assets/9dff0455-b3fe-40ea-b74d-bf1a84526637" />
<br />

<p align="center">
Edit Public subnet to assign public IP allocation <br/>
<img width="940" height="422" alt="image" src="https://github.com/user-attachments/assets/7408e7f2-03ec-41b5-941e-9e9805a90dc8" />
<img width="940" height="204" alt="image" src="https://github.com/user-attachments/assets/e6739911-d1af-408e-a392-b6a8041475c6" />
<br />

<p align="center">
Create Internet Gateway and attach to VPC <br/>
<img width="940" height="330" alt="image" src="https://github.com/user-attachments/assets/d0efcf26-243b-48ea-b49d-9b0b9dba026a" />
<img width="940" height="165" alt="image" src="https://github.com/user-attachments/assets/b0028733-57b8-461a-8ddf-44b0bed7df75" />
<img width="940" height="250" alt="image" src="https://github.com/user-attachments/assets/4731f442-a81e-4332-8fd4-1d6d8d259d84" />
<br />

<p align="center">
Create a Route table and edit <br/>
<img width="940" height="346" alt="image" src="https://github.com/user-attachments/assets/a4cbe169-2525-4059-b964-93844c4887b6" />
<img width="940" height="241" alt="image" src="https://github.com/user-attachments/assets/33069521-581f-478f-a1be-2ea5967aafb8" />
<img width="940" height="242" alt="image" src="https://github.com/user-attachments/assets/f28193fb-768f-4d54-80a4-25fe1cbaf6b1" />
<img width="940" height="274" alt="image" src="https://github.com/user-attachments/assets/752eabe2-a580-45af-ada3-8e3b2153dea0" />
<img width="940" height="282" alt="image" src="https://github.com/user-attachments/assets/2342be62-e7e0-4e9f-8b4d-e8494e4d68d2" />
<br />

<p align="center">
Create a public EC2 instance <br/>
<img width="940" height="509" alt="image" src="https://github.com/user-attachments/assets/30b6805a-cf52-49e6-9f12-24bb6b9f70c3" />
<img width="940" height="501" alt="image" src="https://github.com/user-attachments/assets/a17ce56d-b84f-4fa8-8e1d-42386ce0ee96" />
<img width="940" height="479" alt="image" src="https://github.com/user-attachments/assets/83c18649-2ce2-4c6a-9c7d-fa32e2321dbd" />
<br />

<p align="center">
Create a private EC2 instance <br/>
<img width="940" height="508" alt="image" src="https://github.com/user-attachments/assets/f7ccec4e-62ea-4aa0-b62d-07f75ec42fdb" />
<img width="940" height="484" alt="image" src="https://github.com/user-attachments/assets/1dce19e8-101e-4015-a5c4-701900f875a7" />
<img width="940" height="484" alt="image" src="https://github.com/user-attachments/assets/5796026b-81f6-4749-bb8c-ed6e8ab94ae2" />
<br />


<p align="center">
Connect to EC2 instance <br/>
<img width="940" height="470" alt="image" src="https://github.com/user-attachments/assets/93541dcd-05f7-4602-a5bb-a0320ade35fc" />
<img width="940" height="396" alt="image" src="https://github.com/user-attachments/assets/8d7dc574-918d-4d07-915c-e2e7c5ff8a38" />
<img width="940" height="654" alt="image" src="https://github.com/user-attachments/assets/f41594b4-f8c8-42eb-8682-fc9698ba0735" />
<br />

<p align="center">
Testing Internet connectivity for EC2 instance using the public subnet<br/>
<img width="940" height="606" alt="image" src="https://github.com/user-attachments/assets/7a74d8f4-dabd-4184-91a8-bbd360fbbdaa" />
<img width="940" height="767" alt="image" src="https://github.com/user-attachments/assets/7e1c87ca-ff5a-414b-91fa-74eb26b2e23b" />
<br />



<p align="center">
Connect to the EC2 instance using the private subnet, from the one using the public subnet <br/>
<img width="940" height="531" alt="image" src="https://github.com/user-attachments/assets/ce6055be-c452-4df9-a323-1d97f00e5acb" />
<img width="940" height="472" alt="image" src="https://github.com/user-attachments/assets/1394acc9-dd8d-4404-8c5f-1fb84d350826" />
<img width="940" height="549" alt="image" src="https://github.com/user-attachments/assets/014745c8-729c-4b87-8e9a-1227136f6ca6" />
<img width="940" height="535" alt="image" src="https://github.com/user-attachments/assets/fb2b6e80-e5f5-41d8-9659-580f5e7e8814" />
<br />

<p align="center">
Testing Internet connectivity for EC2 instance using the private subnet<br/>
<img width="940" height="533" alt="image" src="https://github.com/user-attachments/assets/329f3e0a-8bab-4662-bb72-084e4c4cb158" />
<br />


<p align="center">
Create NAT Gateway<br/>
<img width="940" height="502" alt="image" src="https://github.com/user-attachments/assets/84af08bd-6320-4f71-84e7-411fe8096b7e" />
<br />

<p align="center">
Connect NAT Gateway to the default Route table<br/>
<img width="940" height="290" alt="image" src="https://github.com/user-attachments/assets/40db492c-3b18-40c9-9803-4a3b4c04131d" />
<img width="940" height="232" alt="image" src="https://github.com/user-attachments/assets/b8d374eb-fcc7-4af7-8a06-dfd5a33a48dc" />
<br />

<p align="center">
Testing Internet connectivity for EC2 instance using the private subnet after connecting the NAT Gateway to the Route table <br/>
<img width="940" height="540" alt="image" src="https://github.com/user-attachments/assets/e94ab881-adf5-4a43-b95c-06775dd6387a" />
<br />
