# System Design 2

**PasteBin**

**What to be designed?**

1. Pastebin like services enable users to store plain text or images over the network (typically the Internet) and generate unique URLs to access the uploaded data. 

2. Such services are also used to share data over the network quickly, as users would just need to pass the URL to let other users see it.

3. Try it out. Go to pastebin.com, please try creating a new ‘Paste’ there and spend some time going through the different options their service offers.

**Feature Requirements**

Primary Features:

1. The data and links would automatically expire after a certain period of time; users should also be able to specify the expiration date.
2. Users should be able to upload or "paste" their data, and have access to a unique URL.
3. The users can upload text only.
4. Users should be optionally able to choose a custom alias for the paste.

Secondary Requirements:

1. The system should be available at all times. This is necessary because the users will not be able to access their pastes if our service is down. 
2. The system should be highly reliable, and should not lose any data uploaded. 
3. Paste (not predictable) links should not be guessable. 
4. With minimal latency users should be able to access their Pastes in real time. 

**TO DO : Follow the below framweork to design System. Mandatory upload of hand drawn photos of design.**

**Capacity Estimation and Constraints**

What will your estimations of scale? As a system design student you should be able to make intelligent assumptions based on real life systems. 

**System APIs**

**Database Design**

**Basic System Design and Algorithm**

**Data Partitioning and Replication**

**Caching**

**Load Balancing**

**Handling Edge cases in given system**
