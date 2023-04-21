    

<h1 style: align=center> Cinemana: System Architecture </h1>

<p style: align=center> Modern Software Architecture </p>

<p align=right>Al Hassani Baraa Basim Raoof 2022272110002 <br> Kazi Enamul Hque 2022272110004 <br>   Pant Sushovan Nath 2022272110006 <br> Muhammad Zarar 2022272110007 <br></p>

---

| Date       | Member                | Contribution                        |
| ---------- | --------------------- | ----------------------------------- |
| 30/03/2023 | Sushovan              | Initial comit to github.            |
| 03/04/2023 | All                   | Updated the key quality attributes. |
| 06/04/2023 | Sushovan, Baara, Kazi | Finished three quality attributes.  |
| 09/14/2023 | Kazi, Baara, Sushovan | Discussion for further changes. |
| 14/04/2023 | Sushovan              | Added "System Context".            |
| 19/04/2023 | Baara, Sushovan       | Added some database diagrams.                 |

---

## Contents

- [System Context](#1-system-context)
  - [Context](#11-context)
  - [Description](#12-description)
  - [Business Information](#2-business-information)
    - [Business Vision](#21-business-vision)
    - [Target Audience](#22-target-audience)
    - [System Evolution](#23-system-evolution)
- [Stakeholders](#3-stakeholders)
- [Quality Attributes](#4-quality-attributes)
  - [Key Quality Concerns](#41-key-quality-concerns)
- [Database Schema](#database-schema)
  - [Database Components](#database-components)
  - [Database Pipelines](#database-pipelines)
- 

## 1. System Context

This section outlines the system context. The section starts with an introduction of the company. Subsequently, the context of the system is outlined. This section ends with a description about the Cinemana software.

### 1.1 Context

In today’s world, with the easy access to internet and computer devices, the potential of video streaming services are limitless. The growing online population have defined new changes in the way videos and movies are consumed by the public. Not only do people have the freedom to watch anything they want from their personal devices but also no longer need to go to a shop or a movie theatre to rent or watch a movie. This even provides them with the choice to enjoy movies or videos regardless of the time of release and also at their own pace. With such trends and changes, we foresaw a good opportunity to fill that demand and Cinemana was born.

### 1.2 Description

Cinemana is a subscription-based streaming service that allows its members to watch TV shows and movies on an internet-connected device. Cinemana allows its users to easily navigate through a number of movies and TV shows effortlessly and also provides a search bar functionality. Users will be able to stream the content online or download it directly to the device. It is equipped with user-tailored recommendation system which is backed by a large database of movies. It is available in different languages and also provides its users with the flexibility to synchronize different devices under the same account. It also allows the users to add movies to a “watch-later” list and also group movies together.

## 2. Business Information

The following section emphasizes on describing the business environment of Cinemana. The architectural relevant business information is also illustrated.
At first the business vision and rationale are presented, including the unique selling point of Cinemana. Furthermore, the main functionalities of the system are described with an emphasize on providing high-level overview of the system.
Afterwards, the evolution and roadmap of Cinemana are presented.
<br>The section finishes with an illustration of the financial model and an identification of potential competitors.

### 2.1 Business Vision

Our vision statement is, “Becoming the best global entertainment distribution service.” Cinemana will change the way entertainment videos are consumed by the public and to some extent even the way they are produced. Cinemana 	stresses the desire to set a quality bar in the provision of on-demand video services. The ability of our members to control what they want to watch, when they want it, in one simple subscription is a great experience for each user.
Cinemana has three main goals:

1. Provide its users with a stellar service.
2. Provide investors a prospect of sustained profitable growth.
3. Provide employees the allure of huge impact.

The opportunities and threats are listed in the table below.

| Opportunities              | Threats                                               |
| -------------------------- | ----------------------------------------------------- |
| 1. Exponential growth.     | 1. Limited copyrights.                                |
| 2. Global costumer base.   | 2. Growing operational costs.                         |
| 3. Affordable pricing.     | 3. Competitors could provide better local services。 |
| 4. Adaptability.           | 4. Government regulations.                            |
| 5. Exploit Ad-based model. | 5. Piracy and carbon emission.                        |

### 2.2 Target audience

The target customer of Cinemana is any individual with the knowledge to operate a simple computer and has an internet connection. The target audience can be of any age group as the system will provide content relevant to people of all ages. The customer must be familiar with using the internet and have the basic ability to browse through a site. The target audience should be willing to spend a small amount of money for monthly subscription.

### 2.3 System Evolution

As soon as Cinemana is widely accepted by users in the target audience, the next step involves making Cinemana’s presence global by penetrating foreign markets.
<br>Furthermore, the goal is to develop a highly efficient and user friendly on-demand video streaming service that can be used across various devices under different kinds of internet speed. Hence, the system will be implemented to more devices (iOS and Android) and also be optimized to adjust video settings according to the available internet connection speed.
<br>Additionally, with the increment of the supported devices, new versions of Cinemana will provide the users with better features backed up with AI.

## 3. Stakeholders

| Stakeholders          | Definition                                                                                                                                                                                                                                                                |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Users (Customers)     | Users are the most important stakeholders in Cinemana's software architecture. They use the service to stream content and expect the software to be fast, reliable, and easy to use.                                                                                      |
| Software developers   | The software developers are responsible for building and maintaining the software that powers Cinemana. They need to ensure that the software is scalable, efficient, and easy to maintain.                                                                               |
| Operations team       | The operations team is responsible for ensuring that the software is running smoothly and that any issues are resolved quickly. They need to ensure that the software is highly available and that the customer experience is not impacted by any technical issues.       |
| Content providers     | Content providers are responsible for providing the content that is streamed on Cinemana. They need to ensure that their content is compatible with the software and that it is delivered in the best possible quality.                                                   |
| Business stakeholders | Business stakeholders include executives, investors, and partners who have a financial interest in the success of Cinemana's software architecture. They need to ensure that the software is delivering value to the customers and that it is profitable for the company. |
| Negative (hackers)    | Negative stakeholder is anyone who tries to use the system in an unethical way or harm the system and the users involved. This also includes users that download and then distribute the content of the system without permission.                                        |

## 4. Quality Attributes

There are several quality attributes that are important for Cinemana software architecture from a software architecture perspective. These include:

* Performance: Cinemana software architecture needs to be able to deliver a high-quality video streaming experience to customers with minimal buffering or lag time. This requires the software to be optimized for speed and efficiency.
* Scalability: The software architecture needs to be able to handle a large number of concurrent users and traffic spikes, particularly during popular events such as new releases or major sporting events.
* Reliability: The software architecture needs to be highly reliable, with minimal downtime or service disruptions. Customers expect to be able to access the service at any time, and any technical issues can lead to frustration and lost revenue.
* Security: The software architecture needs to be secure, with robust measures in place to protect customer data and prevent unauthorized access or hacking attempts.
* Maintainability: The software architecture needs to be easy to maintain, with clear documentation and well-organized code that can be easily updated or modified as needed.
* Usability: The software architecture needs to be easy to use, with intuitive interfaces and navigation that allow customers to quickly find and stream the content they are looking for.
* Compatibility: The software architecture needs to be compatible with a wide range of devices and platforms, from desktop computers to mobile devices. This requires the software to be designed to work seamlessly with a variety of hardware and software configurations.

### 4.1 Key Quality Concerns

| Key Quality concern | Concerned stakeholders | Viewpoints              |
| ------------------- | ---------------------- | ----------------------- |
| Security            | All                    | Layered pattern         |
| Scalability         | Business stakeholders  | Deployment, Performance |
| Usability           | Users, developers      | Functionality           |
|                     |                        |                         |

1. Security:

   HTTPS — Encrypting the traffic between client and server over HTTPS. This will ensure that no one in the middle is able to see the data especially passwords.

   Authentication — Each API request post-log-in, will do authentication by checking the validity of auth_token in the authorization HTTP header. This ensures that the requests are legitimate.

   By analyzing the Cinemana system architecture using the layered pattern viewpoint, the security quality attribute can be addressed in a comprehensive and systematic way, ensuring that the system is secure at all levels of the architecture.
   ![layered_pattern](image/CinemanaSystemArchitecture/layered_pattern.png)
   By analyzing the Cinemana system architecture using the layered pattern viewpoint, the security quality attribute can be addressed in a comprehensive and systematic way, ensuring that the system is secure at all levels of the architecture.
2. Scalability

   - Horizontal Scaling — add more application servers behind the load balancer to increase the capacity o the service.
     ![1682062270577](image/CinemanaSystemArchitecture/1682062270577.png)
   - Database replication — Use the relational database in Master-slave configuration where the write will happen to the master and reads from the slave. This will improve the performance of reading queries as they won’t be stopped due to write locks on rows. There is a slight replication lag (a few milliseconds) as data is written to the master DB and then propagated to the slave DB.
   - Database sharding — distributing data to multiple servers to perform read/write operations efficiently. we can share the video metadata database using video_id. Our hash function will map each video_id to a random server where we can store the video metadata.
   - Cache sharding — We can distribute our cache to multiple servers. Redis has out-of-box support for partitioning the data across multiple Redis instances. Using consistent Hashing for distributing data will ensure that load is equally distributed if one instance goes away.
   - Search database sharding — Elasticsearch comes with native support for sharding and replication. Sharding helps in improving the query runtime by running them in parallel against multiple shards.
3. Usability
   <br>The user interface (of the web app).
   ![cinemanaUI](image/CinemanaSystemArchitecture/cinemanaUI.png)

   TODO - Use use case diagrams to introduce functional reuirements. Use scenarios to play out some of the use cases.

   ## Database Schema

   ![1682062025801](image/CinemanaSystemArchitecture/1682062025801.png)

   ### Database Components

   ![1682062046379](image/CinemanaSystemArchitecture/1682062046379.png)

   ### Database Pipelines

   ![1682062080088](image/CinemanaSystemArchitecture/1682062080088.png)
