---
layout: default
title: Evaluation
nav_order: 2
description: "Evaluation details."
permalink: /evaluation
---

# Evaluation
{: .fs-9 }

This document aims to provide details on how to evaluate the product, first from a user experience point of view, and then from a technical point of view.
{: .fs-6 .fw-300 }

---

### Evaluation metrics
Let's define the parameters used for the evaluation:
* **Accessibility**
    * Any type of user should be able to use Munity efficiently.
* **Simplicity** 
    * The user must have quick and easy access to the application and all its features.
* **Usability**
    * The response times of the chatbot must be rapid, otherwise this may lead the user to not use the application, furthermore the whole experience must be smooth and lag-free.
* **Graphical interface** 
    * The overall interface must be user friendly and pleasant at sight.
* **Privacy & Security**
    * Munity does not store any sensible data. The passwords are hashed as for standard requirements.


---
## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## <a id="comp"></a>Competitors
In this table, we try to compare Munity with some of the applications already present in the store. In particular as competitors we have chosen:
- [Cinemaniacs](https://play.google.com/store/apps/details?id=it.papalillo.moviestowatch&hl=it&gl=US)
- [JustWatch](https://www.justwatch.com/it)
- [Letterboxd](https://letterboxd.com/)

Features                             | Munity| Cinemaniacs | JustWatch | Letterboxd | 
|------------------------------------|:-----:|:-----------:|:---------:|:----------:|
Notifications on updates 		     |  ✅   |     ❌     |     ❌    |     ❌		
Handle WatchLists or Collections     |  ✅   |     ✅     |     ✅    |     ✅
Social Components        		     |  ✅   |     ❌     |     ❌    |     ✅
*"Where to watch"*                   |  ✅   |     💰     |     ✅    |     ✅
Personal Statistics                  |  ✅   |     ✅     |     ❌    |     ❌
Gamification 						 |  ✅   |     ❌     |     ❌    |     ❌
Multiplatform ready                  |  🔜   |     ✅     |     ✅    |     ✅
A.I. Chatbot and Theatre integration |  ✅   |     ❌     |     ❌    |     ❌

As we can see from the table above, Munity bridge the gap between all those applications, aiming to be a definitive solution for the users to have all those features in a single place.
Furthermore, the UI/UX of those applications, except for JustWatch, is not updated to modern standards resulting in being obsolete for the target user.

## <a id="tech"></a>Technical aspects

Let's analyse the Technical aspects through the edge components that interface directly with the user. Here is the status glossary:
* ✅ Completed
* ⚠️ Work in progress
* 🔜 For the future


  
### Metrics description
* **Accessibility**
    * Indicates the ability of the technology to be exploited by the user.
* **Complexity**
    * Complexity can be attributed to hardware and software needed for the system.
* **Scalability**
    * The scalability of a system ensures its normal operation even when the sphere of the application becomes larger.
* **Cost**
    * The cost of a system like this can depend on several factors. The most important ones include money, time, space, weight, and energy.
* **Security**
    * Security means the danger that data sent through the system will be violated or accessed by third parties.

### Metrics evaluation

| Metrics | Status |Solution/Result |
| ------------- |:---:| :----- |
| `Accessibility` |  🔜 | Accessible with a any smartphone, both IOS and Android thanks to React Native hybrid development.|
| `Complexity` | ✅ | Fast learning curve of React Native and hybrid development approach makes the implementation fast and easier|
| `Scalability` | ✅ | Microservices approach is suited to grant scalability to the system.|
| `Cost` | ✅ | The application is free to download in the store, theatre convenction can be discussed individually|
| `Security` | ✅ | All data provided by the users are encrypted. No sensible data needed. |

## <a id="usex"></a>User experience

### Users survey
To evaluate the idea, we used a survey, sharing it with our family, friends, and friends of friends. Indeed, with this feedback and suggestions, we understood where to make some changes, especially if the final user would really like and possibly use the service.

Here the anonymous results:
- [International](not-yet-available)

{: .warning }
> The results of the pool is not yet available since it's still ongoing. 


## <a id="state"></a> Implementation state

*Glossary*
* ✅ Completed
* ⚠️ Work in progress
* 🔜 For the future

### Mobile application 

| Feature | Status |
| :------ | :----: |
| The mobile application must follow a graphically connected interface, this interface is built with Adobe Xd| ✅ |
| The mobile application must be able to send and receive requests and responses from the back-end via HTTP through fetch construct | ⚠️ |
| The mobile application must be able to guarantee the login to the application | ⚠️ |
| The mobile application must be accessible from all the systems | ⚠️ |
| Users can interact with a finite-state chatbot to get suggestion on movies or reserve tickets in it's preferite theatre | ⚠️ |
| Users can check updates on followed titles with an ad hoc internal and external notifications system | ⚠️ |
| Users can check where to watch a title using the most known streaming services | ⚠️ |
| Users can login in the application and start to search, and add in lists movies and tv series | ⚠️ |
| Users can understand and see the statistics of their own profile collected by the system | ⚠️ |
| Users can earn badges to improve the engagement and loyalty to the product | ⚠️ |

     
### Backend

| Feature | Status |
| :------ | :----: |
| The interaction between the mobile application and the backend must be safe and guarantee the privacy of the user | ⚠️ |
| The interaction between the mobile application and the backend must guarantee predictable behavior in case of failures or critical situations | ⚠️ |
| The interaction between the mobile application and the backend must guarantee correct behavior in case of unexpected input or situation | ⚠️ |
| The interaction between the mobile application and the backend must be flexible so that fixes, upgrade and new development can be easily implemented | ⚠️ |
| The backend must be able to interact with the databases through a query system, in particular, all the information needed may be retrieved. | ✅ |
| The backend must be able to connect with a REST service to book a seat for a movies with Theatre API. | ⚠️ |
| The backend must be able to connect with API gateway which will redirect the traffic to the appropriate service. | ✅ |
| All the microservices must be able to connect with their own database. | ✅ |
| All the microservices must be able to scale independently. | ✅ |
| All the microservices must be easy to deply through the use of docker-compose. | ✅ |
| _(POC)_ The Theatre API service will be emulated for this phase. | ⚠️ |


### Database 

| Feature | Status |
| :---- | :----: |
| The interaction between the database and the backend must be able to guarantee backup services and disaster recovery procedures. | 🔜 |
| The interaction between the database and the backend must guarantee the consistency of the information stored. | ⚠️ |
| The database should be reachable in every moment, in case of a fault the system must be able to control the situation. | ✅ |
| Eventually sensible data must be encrypted by the backend before the insertion. | ⚠️ |

***PoC*** means that the functionality is simulated
