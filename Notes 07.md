# Notes 07: Storage
## Introduction to Storage & AWS Storage Services 

What is Storage?
* Storage is basically a technology that allows a user to retain digital data onto a medium. It is one of the core components of a computer and in cloud computing, something that you need to understand the differences.

Volatile vs. Non-Volatile
* **Volatile Memory:** Volatile memory is a type of storage whose contents are erased when the system's power is turned off or interrupted. 
  * For example, RAM is volatile. When you are working on a document, it is kept in RAM, and if the computer loses power, your work will be lost. For this reason, you should save your document to a file on a non-volatile storage medium, such as your hard drive.
* **Non-Volatile Memory:** NV or Non-volatile memory is a term used to describe any memory or storage that is saved regardless of the power to the computer is on or off. It is also called persistent storage or permanent storage. 
  * An example of non-volatile memory and storage is a computer hard drive, flash memory, and ROM. If data is stored on a hard drive, it will remain on that drive regardless if the power is interrupted, which is why it is the best place to store your data and documents. Non-volatile memory also stores your computer's time and system settings even when the power is off.
Local Storage Types:
* Read Only Memory (RAM): temporary storage that allows data and programs to be stored in memory in order the operating system to use them. After the operating system has booted up, each program you open, such as the browser you're using to view this page, is loaded into memory while it is running. If too many programs are open, the computer will swap the data in the memory between the RAM and the hard disk drive.
* Hard Drives: can be used to store any data, including pictures, music, videos, text documents, and any files created or downloaded. Also, hard drives store files for the operating system and software programs that run on the computer. The two main types of hard drive are HDD (hard disk drive) and SSD (solid state drive). Below is a table comparing them.
* Optical Drive: uses lasers and lights as its method of reading and writing data. The three standards of optical media are CD (compact disk), DVD (digital versatile disk or digital video disk), and Blu-ray. All standards use the same size disc, but the data is read differently for each. Below is a table of data capacity for each standard.
* Flash Drive: Alternatively referred to as a USB flash drive, data stick, pen drive, memory unit, keychain drive, and thumb drive, a jump drive is a portable storage device. It is often the size of a human thumb (hence the name) and connects to a computer via a USB port. Flash drives are an easy way to store and transfer information between computers and range in sizes from 2 GB to 1 TB.

Storage in the Enterprise:
1. Redundant Array of Independent Disks (RAID): The simplest way to replicate data is to use a Redundant Array of Independent Disks or RAID for short. Depending on the level you use, you can lose a drive and still keep all your data safe. Computers and servers can use a RAID to replicate data across multiple redundant drives in order to ensure data is available
    ![Notes 07](https://user-images.githubusercontent.com/90662294/142610268-ec4f4157-10a2-4635-a0cc-bb457bebc91e.png)
2. File Servers:
3. Network Attached Storage (NAS):A file server is a type of server on a network that is used to provide authorized users with access to files. It has all of the same components that a computer or server has including a CPU, RAM and storage, but the storage used for serving files is generally larger and optimized for serving files. Normally file servers are kept off of the public internet for security reasons, but are available on an internal enterprise network.
4. Storage Area Network (SAN):A Storage Area Network, SAN for short, is a specialized high-speed network that provides access at a raw block-address level. Systems can attach it to servers using technologies like Fiber Channel (FC) or Internet Small Computing System Interface (iSCSI) so that the storage appears to be attached locally rather than connected via a network.

Storage in the Cloud: Cloud storage is a cloud computing model that stores data on the Internet through a cloud computing provider who manages and operates data storage as a service. It’s delivered on demand with just-in-time capacity and costs, and eliminates buying and managing your own data storage infrastructure. This gives you agility, global scale and durability, with “anytime, anywhere” data access.
* Examples: Google Drive, Dropbox, Box.com, Microsoft Onedrive
* How does Cloud Storage work?
  * Cloud storage is purchased from a third party cloud vendor who owns and operates data storage capacity and delivers it over the Internet in a pay-as-you-go model. These cloud storage vendors manage capacity, security and durability to make data accessible to your applications all around the world.
* Benefits of Cloud Storage:
  * Total Cost of Ownership
    * With cloud storage, there is no hardware to purchase, storage to provision, or capital being used for "someday" scenarios. You can add or remove capacity on demand, quickly change performance and retention characteristics, and only pay for storage that you actually use. Less frequently accessed data can even be automatically moved to lower cost tiers in accordance with audit-able rules, driving economies of scale.
  * Time to Deployment
    * When development teams are ready to execute, infrastructure should never slow them down. Cloud storage allows IT to quickly deliver the exact amount of storage needed, right when it's needed. This allows IT to focus on solving complex application problems instead of having to manage storage systems.
  * Information Management
    * Centralizing storage in the cloud creates a tremendous leverage point for new use cases. By using cloud storage lifecycle management policies, you can perform powerful information management tasks including automated tiering or locking down data in support of compliance requirements.




