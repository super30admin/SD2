# System Design 2

**Designing Instagram**

**What to be designed?**

1. Instagram is a social networking service that allows users to upload their photos and videos and share them with other users.
2. Users of Instagram may opt to share information either privately or publicly.
3. Any publicly shared content can be seen by any other user, while privately shared content can be accessed only by a specified set of people.
4. We plan to design a simpler version of Instagram for the sake of this exercise, where a user can share photos and follow other users too.
5. For each user the 'News Feed' will consist of top photos of all the people that the user follows.

**Feature Requirements**

Primary Features:

1. Users should have the option to upload / download / view photos. 
2. Users can perform photo / video title searches. 
3. Other users can follow. 
4. The system should be able to generate and display the News Feed of a user which consists of top photos from all the people that the user follows.

Secondary Requirements:

1. Our service needs high availability. 
2. Consistency can take on a hit (for availability), if a user fails to see a photo for a while; it should be fine. 
3. The system should be highly reliable; no photo or video that is uploaded should ever be lost.

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
