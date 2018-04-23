# Design for Blockchain Economic System

"Blockchain" is believed to be the next disruptive technology, which involves a lot of technical problems and engieering work. The blockchain community has been working hard to build the software infrastructure of public blockchains like ethereum and improve their scaling capabilities to process more transactions per second. 


## 1. What blockchain brings to us?

At first glance, it seems to be a software development task which is an absolutely "engineering" work, but it is not. What blockchain brings to us is actually a new **"Blockchain Economic System"**, which is the "digital twin" of our physical economic system in the crypto world:

* each person in *physical world* is "mapped" or "digitalized" into the *crypto world* as a "digital twin" with wallet.  
* each person can be uniquely represented with his/her own wallet, because only the ower has the private key to access the fund in the wallet.
* users interact with each other and the economic system through transactions with their wallets.

Each blockchain application builds an "blockchain economic system", which has its own incentive token and operating rules. The concept can be illustrated with following figure:

| ![](img/bitcoin-overview.png) | 
|:--:| 
| *Users are mapped into Crypto Space through Wallet (source: What is Bitcoin, Really?[1])* |


## 2. Why design of economic system is critical?

The development of blockchain application is not techinically difficult. However, the "design" of the economic system is extremely difficult and challenging.


### 2.1 Code Is Law

The rules of blockchain economic system are defined with smart contracts. Due to the principles of blockchain immutability, the "deployed" contracts are immutable as carved in stone and all smart contract executions are final. As such, people believe "Code is Law" on the blockchain and build their "Trust" with the blockchain economic system. 


However, the blockchain immutability is a two-edged sword bringing significant obstacle to the design of economic system, because there is no way to repair bugs or upgrade with features on the deployed contracts. Therefore, it is urgently sought to have a “indefectible” design of rules with one-shot opportunity at the very beginning.
 


### 2.2 Reconcile Conflict Interests 

In any economic system, participants usually are egoistic who make decisions in their own best interest. In the meantime, all participants form an economic system which needs to survive and evolve for social interest of the whole community. 

The pursuits of self-interest and social interest seem to be conflict, but they can be reconciled by a “well-designed” economic system with rules and incentives. In this kind of system, individuals acting in their own self-interest can “unconsciously” promote the evolvement of the entire community and benefit the social interest. 

Our human society is a case in point: individuals work hard to achieve great fame and fortune. In the same process, they create tremendous value to the society and contribute to the social interest. This is what Adam Smith called the "invisible hand". Our human society has been operating in this way for thousands years and it works pretty well. 

Therefore, the design of blockchain economic system shall define sophisticated rules and incentives so that to reconcile the conflict between self interest and social interest.

## 3. What kind of rules and incentives?

Specifically, the rules and incentives define follwoing aspects:

* the way how people can participate in the system and interact with each other.
* the mechanism to prevent bad actors from cheating or damaging the system.
* the punishment to penalize bad actors for their malicious behavior.
* the attractive incentives to motivate people to make contribution.

A well-designed rules incentivize desired behavior and enforce a punishment to disincentivize malevolent activity. Therefore, participants are encouraged to maintain the normal operation of the community which becomes a self-sustainable and autonomous economic system.

## 4. What makes the economic system fail?

To better understand the criticality of rules and incentives, it is worthwhile to explore the reasons for the failure of blockchain economic system:

1. **Inadequate Incentive**: people are usually lazy by nature, as they are disinclined to volunteer and make contributions to the community (e.g., mining blocks, maintain records, verify computing results, and etc.). Charlie Munger’s famous quote is very insightful to this point: "Show me the incentive and I’ll show you the outcome". Clearly, the economic system have no way to survive without attractive incentives for individuals.


2. **Malevolent Activity**: economic system shall have penalty mechanism to disincentivize malevolent activities. Otherwise, bad actors can cheat the system and cause great loss to other people with desirable behavior. In this way, the community will shrink, lose population, and cease to exist in the end.

## 5. How to design blockchain economic system?

There are some existing works trying to characterizes the blockchain network to be a physical network (i.e., electronic or robotic) so that engineering model and analysis can be applied. However, there is one neglected discrepancy: 

* the behavior of individuals in physical network follows the deterministic physical rules, which defines a *limited* feasible region of their state change (i.e., a set of individual's feasible states in the physical system). As such, their behavior can be modeled with formulae and simulated to predict state changes.

* the behavior of people in blockchain network is extremely unpredictable, because people have the capability of creation and imagination and possess *unlimited* feasible region of state change. So the blockchain system demands a “indefectible” design to prevent potential malicious behavior.



From this point of view, the blockchain system is much more complicated than physical system and needs more cross-discipline knowledge such as engineering, gaming theory, sociology, psychology, finance and etc. I believe people will build a close-to- indefectible procedure or framework to design the blockchain economic system over the time. 



# Reference
* [1] [What is a Bitcoin, Really?](http://preshing.com/20140127/what-is-a-bitcoin-really/)