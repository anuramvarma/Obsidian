Cloud Computing:

- Uses remote servers on the internet to store, manage and access data online rather than local drives.
- The data can be anything such as files, images and documents

**Cloud Architecture**
  ![[Images/CloudArchitectureImage.png]]
-------------------------------------------------------------------------------------------------------------
### **Cloud Deployment Models**

1. **Public Cloud**
    
    - Cloud services offered **over the internet** to the public.
    - Easily accessible for general public
    - It is Less Secure due openness
        
    - Managed by third-party providers.
        
    -  _Example:_ AWS, Azure, Google Cloud.
        
2. **Private Cloud**
    
    - Used by a **single organization** for internal use.
    - It is also called as Internet cloud
    - Provides **more control and high security** because of it's private nature.
        
    -  _Example:_ VMware, OpenStack, IBM Cloud Private.
        
3. **Hybrid Cloud**
    
    - Combination of **public and private clouds** for flexibility and scalability.
    - Hybrid Cloud= Public + Private cloud
        
    -  _Example:_ Azure Hybrid, AWS Outposts.
--------------------------------------------------------------------------
### **Types of Cloud Computing Services (Service Models)**

![[Pasted image 20251008104226.png]]
**SaaS (Software as a Service)**

- Provides **ready-to-use software** applications over the internet.
- You use **ready-to-use software** over the internet — no installation or maintenance required.  
	Just log in and use.
-  _Example:_ Google Workspace, Salesforce, Microsoft 365, Zoom.
- It’s like **booking a hotel room** — everything is ready for you; you just check in and use the services.

**PaaS (Platform as a Service)**

- Provides a platform to **develop, test, and deploy** applications without managing infrastructure.
- Here, you don’t worry about servers or operating systems.  
- The provider gives you a **ready-made platform** to build, test, and deploy applications.
- It’s like **renting a fully furnished apartment** — you move in and start living (developing), without worrying about plumbing or electricity (infrastructure).
-  _Example:_ Google App Engine, AWS Elastic Beanstalk, Heroku.

**IaaS – Infrastructure as a Service**
- Provides **virtual machines, storage, and networks**.
- Users manage OS, runtime, and apps.
- Example: AWS EC2, Google Compute Engine, Microsoft Azure VM.
### **Advantages**
- Cost-efficient (pay-as-you-go)
- Accessible from anywhere
- Scalable and flexible
--------------------------------------------------------------------------
## **Elasticity in Cloud Computing**

### **Definition:**

**Elasticity** means the **ability of a cloud system to automatically adjust resources** (like CPU, RAM, storage, and servers) **based on current demand** — **scaling up when load increases** and **scaling down when demand drops.**
In short:

> **Elasticity = Auto-scaling resources as per need.**

Think of elasticity like a **rubber band**   
It **stretches** when needed (increase demand) and **contracts** when not (decrease demand).
### **Example:**

Let’s say you have an **e-commerce website** hosted on AWS.

- 🔺 During **festival sales**, traffic suddenly spikes — thousands of users visit your site.  
    → The cloud **automatically adds more servers** to handle the load.
- 🔻 After the sale, traffic decreases.  
    → The cloud **removes extra servers** to save costs.
--------------------------------------------------------------------------
## **Monolithic vs. Microservices Architecture**

## **Monolithic Architecture**
 **Definition:**
A **monolithic application** is built as **one large, single unit** where **all modules (features)** — like payments, recharge, wallet, ticket booking, etc. — are **combined into one codebase** and deployed together.

![[Pasted image 20251008112723.png]]

