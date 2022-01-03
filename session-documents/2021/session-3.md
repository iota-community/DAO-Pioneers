# IOTA DAO Pioneers

We took inspiration from [Stephen Reid](http://stephenreid.net/) ([@daoist321](https://twitter.com/daoist321)) How to DAO course, but harmonized content and adjusted it to the needs of our IOTA community.


## Session 3 prep

Listen in to this great podcast episode on Spotify about reward systems in DAOs.



* [Compensation in DAOs with Tracheopterix](https://open.spotify.com/episode/3IdmMizxDPHTUjRKqYrMzG?si=hWwNmc7fRR-SK1dRrU6dGA)

Optionally, check out some of the content coming out of The DAOist:



* [The DAOist design sketch](https://www.youtube.com/watch?v=u8YZRtNzPhY)
* [Hard things we forget to talk about @ The DAOist Paris](https://www.youtube.com/watch?v=G6EK_TDhxj8) 

**Session 3 content:**


### **DAO Operating Systems**



* DAOHaus
* Aragon
* DAOStack

**Recognizing Contribution**



* Sourcecreed
* Coordinape
* Collabland

**DAO Tools**



* Snapshot
* Tally
* Gnosis / Multisig
* Sesh


## DAO Operating - Systems



* [A comparative analysis of the platforms for decentralized autonomous organizations in the Ethereum blockchain](https://jisajournal.springeropen.com/articles/10.1186/s13174-021-00139-6#Tab5)
* [Aragon, DAOStack, Colony, Moloch](https://kronosapiens.github.io/blog/2019/06/16/aragon-daostack-colony-moloch.html)


### DAO Haus

<img width="503" alt="image" src="https://user-images.githubusercontent.com/77154511/147893214-092fe1a6-bbd8-4ba4-af8e-549ae6894521.png">


DAOhaus DAOs differentiate between (non-transferable) voting-economic rights (called 'Shares') and (non-transferable) economic-only rights without voting power (called 'Loot'):

"To allow the DAO to issue non-voting shares, we introduce the concept of Loot. Just like Shares, Loot is requested via proposal, issued to specific members and non-transferable, and can be redeemed (via ragequit) on par with Shares for a proportional fraction of assets in the Guild Bank. However, Loot does not count towards votes, and DAO members with _only_ Loot will not be able to sponsor proposals or vote on them."

The next version of DAOhaus will totally decouple voting rights from economic rights with separate 'Voice' (voting) and 'Exit' (economic) shares.

Thus you can think of DAOhaus DAOs as **blockchain-based multi-stakeholder co-operatives**.


### Shares and Loot

<img width="620" alt="image" src="https://user-images.githubusercontent.com/77154511/147893222-04ab1956-544b-4e09-9f04-fb3e8fb1ca79.png">



_Member page of [POOLhaus](https://app.daohaus.club/dao/0x64/0x224ed86c7256c59c391d88f2fd4732e9e7251681/members)_

A reminder:



* Shares = voting rights (enabling you to vote on DAO proposals) + economic rights (enabling you to ragequit a proportionate share of each token in the DAO's treasury)
* Loot = economic rights only


### Ragequitting

<img width="618" alt="image" src="https://user-images.githubusercontent.com/77154511/147893233-89d2201b-cc58-4679-ab01-cd777c480316.png">



_Ragequitting is done via the Profile page_

Burns a certain number of Shares and/or Loot in exchange for a proportionate share of **each ERC-20 token** in the **DAO's main treasury**. Note, there is no claim on tokens (ERC-20s or NFTs) in side-vaults (Safes).


### Stages of a proposal

From the [DAOhaus docs page](https://daohaus.club/docs/proposals/):

**1. Submit Proposal**

Anyone, even non-members, can submit proposals to the DAO.

**2. Sponsor Proposal**

After submitting a proposal, it will enter the Unsponsored Proposals section. This means someone with shares (which could be you) must Champion the proposal for it to be moved to voting.

Note: You can sponsor your own Proposal, but it is recommended that you have another member sponsor it so they can make sure you have filled out the proposal with the correct information and you get the result you intended for.

Only members can 'Sponsor' the proposal, sending it to the queue.

**3. In queue**

Once the proposal has been sponsored, it will enter the queue. The queue ensures proposals are funneled to voting in an orderly fashion. One proposal will go from the queue to the Voting Period in a time frame specified by the summoners of your DAO.

**4. Voting Period**

Once in the Voting Period, members can now vote on the proposal. Every proposal has an 'x' amount of time in the voting period where it must receive more Yes than No votes to pass.

**5. Grace Period**

Voting is over, and the Proposal is set to pass or fail depending on the votes cast during voting. Members who voted No, and have no other pending Yes votes, can ragequit during this period.

**6. Ready for Processing**

Next, the proposal is sent to Processing, in which the vote is time-stamped on-chain.

**7. Completed**

After being processed, the proposal is marked as Completed, and all shares, funds or outcomes are executed as specified in the proposal. All outcomes of a proposal that affect you can be viewed by clicking your Address (top right) and selecting View Member Profile.


### Proposal types

<img width="617" alt="image" src="https://user-images.githubusercontent.com/77154511/147893251-2ed54008-778a-453e-914d-8c1820cbb6bc.png">



* Request shares for tokens: Request shares from the DAO in exchange for ERC-20 tokens
* Request shares for work completed: Request shares from the DAO by showing finished work (shares and/or tokens)
* Whitelist a new token: Create a proposal to add a new token to the DAO treasury
* Guild kick: Create a proposal to kick a member (a forced ragequit)

<img width="611" alt="image" src="https://user-images.githubusercontent.com/77154511/147893264-b7dbd1e1-0a43-4170-97cb-ec788c4a8365.png">
<img width="620" alt="image" src="https://user-images.githubusercontent.com/77154511/147893274-2004c786-3680-440e-a0f5-eb6f6c60fed4.png">





* Membership proposal/Funding proposal/Swap tokens for Loot or shares (these are functionally equivalent, they just have different UI skins): tribute in, shares/loot/tokens out. They are a superset of _Request shares for tokens_ and _Request shares for work completed_.
* Loot grab: in development
* Signal proposal: no tribute in, no shares/loot/tokens out


## Aragon



* [Govern better, together. Build your DAO now. (aragon.org)](https://aragon.org/)


<img width="615" alt="image" src="https://user-images.githubusercontent.com/77154511/147893278-d33b1b9f-a08b-41a7-b5aa-20bf3847dc54.png">





* [Building DAOs with Aragon. A framework to create decentralized… | by Gaurav Agrawal | QuikNode | Medium](https://medium.com/quiknode/building-daos-with-aragon-c8b95956a405)
* [https://changelly.com/blog/aragon-ant-review/](https://changelly.com/blog/aragon-ant-review/)
* [Aragon Network DAO and Decentralized Governance | Gemini](https://www.gemini.com/cryptopedia/aragon-crypto-dao-ethereum-decentralized-government#section-aragons-blockchain-technology)
* [How to create your own DAO with Aragon explained - step-by-step beginners guides | QuickNode](https://www.quicknode.com/guides/web3-sdks/how-to-create-your-own-dao-with-aragon)


## DAOStack



* [DAOstack](https://daostack.io/)

DAOstack aims to support the entire process of building DAOs, and so the stack currently includes everything from basic peer-to-peer decision-making modules to a fully functional user interface that requires no technical knowledge. 

"There is a natural tension between scalability, the number of decisions a collective can make in a period of time, and resilience, the incorruptibility of those decisions. We resolve that tension with a new collective decision-making process, called holographic consensus, whereby small groups can make decisions on behalf of the larger majority in such a way that guarantees perfect alignment between the two."

— DAOstack architect Matan Field

This is where the GEN token comes into play. GEN is a [cryptocurrency](https://en.wikipedia.org/wiki/Cryptocurrency) that manages attention within the DAOstack ecosystem. GEN cannot buy voting power, nor does holding it grant voting privileges, but you can use GEN to place a stake for or against a proposal. This stake influences whether or not the proposal rises into the collective attention of the voters. If you stake for proposals that the voters then pass, you're rewarded with more GEN. If you stake for a proposal that then fails, you lose your GEN. And vice versa if you stake against a proposal.

This staking system effectively amounts to a prediction market that runs in parallel to the voting apparatus.

Since predictors are incentivized to pick out the best, most DAO-aligned proposals, we can lower the passing requirements for the top predicted proposals: these proposals can be passed much more quickly and with fewer total votes than other proposals. This creates a dynamic we call holographic consensus.

To create DAOs resilient to corruption, DAOstack's first governance templates implement voting rights using a system called Reputation. Reputation is a score assigned to each user that represents that user's voter power. Each DAO has a separate ledger of Reputation scores, and so Reputation cannot be directly transferred from peer to peer. Rather, it is distributed through the passing of proposals inside the DAO.

Indirect transfers of Reputation that cannot be completely prevented, such as a user transferring selling control of their account, are discouraged by a DAO's ability to slash Reputation: if DAO voters find that an account has indirectly transferred its voting power, the DAO can pass a proposal to set that account's Reputation score to zero.


<img width="660" alt="image" src="https://user-images.githubusercontent.com/77154511/147893286-465ac5fa-5d1d-4950-b505-035376612822.png">



* [An Explanation of DAOstack in Fairly Simple Terms | by Ezra Weller | DAOstack | Medium](https://medium.com/daostack/an-explanation-of-daostack-in-fairly-simple-terms-1956e26b374)


# Recognizing contributions


### Collab.land

<img width="533" alt="image" src="https://user-images.githubusercontent.com/77154511/147893353-7c2c8c21-2b62-4c85-b2b5-ccc9d34cc6ee.png">


* [Collab.Land](https://collab.land/)
* [Discord Bot Walkthrough : Collab.land Support](https://collabland.freshdesk.com/support/solutions/articles/70000036689-discord-bot-walkthrough)
* [Collab.Land - Unlocking the Power of Crypto: NFTs and DAOs](https://www.youtube.com/watch?v=I7ayZ9X9sQw)

Token-based roles, airdrops (as claims), and tipping


<img width="644" alt="image" src="https://user-images.githubusercontent.com/77154511/147893308-c026c808-2325-4f9f-8d5e-7d7754251904.png">



### Coordinape

<img width="619" alt="image" src="https://user-images.githubusercontent.com/77154511/147893326-61d4ce94-528c-4026-9e3e-c498b7791d51.png">


* [Coordinape](https://coordinape.com/) 
* [How To Use Coordinape](https://docs.coordinape.com/welcome/how_to_use_coordinape) 
* [Metanauts Guide to Coordinape 🐵. ](https://medium.com/mstable/metanauts-guide-to-coordinape-964778e0f073) 
* [Decentralized payroll management for DAOs | by Andre Cronje | Yearn](https://medium.com/iearn/decentralized-payroll-management-for-daos-b2252160c543) 
* [Coordinape - Decentralize Payroll for the Modern DAO](https://www.youtube.com/watch?v=J8oGun8EKDE)
* [Coordinape - Zach & Tracheopteryx | Meet the Nation](https://www.youtube.com/watch?v=JM0zF3AzFno)
* [Coordinape: An overview](https://forum.tecommons.org/t/coordinape-an-overview/616?utm_source=pocket_mylist) 
* [Richard Dennis Bartlett + Zach from Coordinape](https://www.youtube.com/watch?v=CumN3ZwiagI) 
* Soon, similar vibe: [Quadratic Diplomacy](https://www.quadraticdiplomacy.com/) 

"At the start of the epoch, each Circle member receives a number of non-divisible GIVE tokens. Members allocated their GIVE tokens to other members over the course of the epoch to reward them for their value to the organization. Members can adjust their allocations up until the end of the epoch. They can add notes to their allocations if they wish. At the end of the epoch, all allocated GIVE tokens become locked (now called GET tokens), and all unallocated GIVE tokens are burned. Budget distribution is then formulated according to the percentage of total GET tokens that each member of the circles has received."


### SourceCred

<img width="617" alt="image" src="https://user-images.githubusercontent.com/77154511/147893347-7088fb57-daf2-4882-a977-bf543ebc8e44.png">



* [SourceCred](https://sourcecred.io/)
* [❓ FAQ](https://sourcecred.io/docs/beta/faq/) 
* [DAOs and the Missing Link: Reputation Protocols](https://medium.com/sourcecred/the-dao-missing-link-reputation-protocols-8e141355cef2)
* [SourceCred: An Introduction to Calculating Cred and Grain](https://research.protocol.ai/blog/2020/sourcecred-an-introduction-to-calculating-cred-and-grain/)

DAOs experimenting with SoureCred:



* MakerDAO: [What is SourceCred and how do I opt in?](https://forum.makerdao.com/t/what-is-sourcecred-and-how-do-i-opt-in/3913)
* FWB: [Friends With Benefits: A New Model for Social Tokens on Ethereum](https://consensys.net/blog/codefi/friends-with-benefits-a-new-model-for-social-tokens-on-ethereum/)
* TEC: [SourceCred in the TEC](https://forum.tecommons.org/t/sourcecred-in-the-tec/270) & [SourceCred - TEC Handbook](https://token-engineering-commons.gitbook.io/tec-handbook/tec-agreements-1/sourcecred)
* 1hive: [Pollen](https://wiki.1hive.org/getting-started/pollen) & [Updates to SourceCred](https://forum.1hive.org/t/updates-to-sourcecred/726/2) 
* Balancer: [[Proposal] SourceCred Engagement Incentives - Governance - Balancer](https://forum.balancer.fi/t/proposal-sourcecred-engagement-incentives/684) 

"Most communities have no fair, transparent, and incentive-compatible way to value contributions. SourceCred makes this possible by offering a credibly neutral framework that assigns Cred scores based on contributions, and then distributing Grain tokens based on those scores."

Similar vibe: the Commons Stack praise bot and SEEDS gratitude bot



* [What is Commons Stack Praise?](https://wiki.commonsstack.org/contributors-guide) 
* [Praise - TEC Handbook](https://token-engineering-commons.gitbook.io/tec-handbook/tec-agreements-1/praise)
* [commons-stack/CommonsStackBot](https://github.com/commons-stack/CommonsStackBot)
* [The Praise Debate Post-Action Summary - ⚛ Community](https://forum.tecommons.org/t/the-praise-debate-post-action-summary/533) 
* [Decentralizing Our Economies with Gratitude | by Rieki Cordon | SEEDS](https://medium.com/joinseeds/decentralizing-our-economies-with-gratitude-8526fb8c6bf8)
* [Gratitude Token by Julio Holon](https://mbc.joinseeds.earth/academy/academy-video-playlist/gratitude-token-by-julio-holon)


## Useful web2 software to support decision-making


### Loomio

<img width="617" alt="image" src="https://user-images.githubusercontent.com/77154511/147893372-658a19f1-e325-44b4-9675-89687b167497.png">


* [Intro to Loomio](https://youtu.be/Zlzuqsunpxc) (3m)
* [Loomio User Manual](https://help.loomio.org/en/user_manual/) 
* [Types of polls and proposals](https://help.loomio.org/en/user_manual/polls/proposal_types/)
    * Time poll
    * Check
    * Poll
    * Multiple choice
    * Score poll
    * Dot vote
    * Ranked choice
    * Proposal


### Polis

<img width="590" alt="image" src="https://user-images.githubusercontent.com/77154511/147893387-4d74e85a-c98b-450b-853c-d4825d299299.png">



* [Polis](https://pol.is/home) 
* [Polis handbook](https://compdemocracy.org/Polis/)
* [pol.is in Taiwan: better public discourse through artificial intelligence → more informed public servants → better laws](https://blog.pol.is/pol-is-in-taiwan-da7570d372b5) 
* [Polis case studies](https://compdemocracy.org/Case-studies/)
* [Polis media coverage](https://compdemocracy.org/Media-coverage/)
* [Taiwan is making democracy work again. It's time we paid attention](https://www.wired.co.uk/article/taiwan-democracy-social-media) 
* [Crossing Divides: How an app could save democracy from deadlock](https://www.bbc.co.uk/news/technology-50127713) 
* [Can Taiwan Reboot Democracy?](https://www.youtube.com/watch?v=VbCZvU7i7VY) (on Polis; 7m)
* Podcasts with Audrey Tang:
    * [Digital Social Innovation to Empower Democracy | Audrey Tang | TEDx](https://www.youtube.com/watch?v=LscTx6DHh9I) (2019, 17m)
    * [How digital innovation can fight pandemics and strengthen democracy | Audrey Tang](https://www.youtube.com/watch?v=IZ2N3tF4W_k) (2020, 50m)
    * [Digital Democracy Is Within Reach - Your Undivided Attention | Podcast with Audrey Tang](https://open.spotify.com/episode/0RrR4b1tUcuVZYV4fLH0tM) (2020, 47m)
    * [13: How To Hack The Epistemic Crisis, with Audrey Tang](https://open.spotify.com/episode/2euzZC2esXfRWBWFgZk9ss)  

"In plain language, Polis is an open-source technology for survey research that leverages data science. It is described on the website as:

_a real-time system for gathering, analyzing, and understanding what large groups of people think in their own words, enabled by advanced statistics and machine learning._

More specifically, Polis is a platform for a conversation, in which participants submit short text statements or comments (&lt;140 characters), which are then sent out semi-randomly to other participants to vote on by clicking agree, disagree or pass. Polis allows conversation owners to create conversations that can seamlessly engage (currently) up to hundreds of thousands or (conceivably) millions of participants…

Polis might at first look like a fancy online opinion polling tool. But it can more accurately be described as an evolving, lively, artificially intelligent, interactive "suggestion box" that can realize consensus around a controversial question. It works like this:  Dozens or thousands of participants submit short statements expressing their views on the question. They also respond to other participants' statements with Agree, Disagree, or Pass.

As hundreds of these statements and evaluations accumulate, a behind-the-scenes algorithm sorts participants into diverse clusters of like-minded responders. The algorithm then identifies "consensus statements" about which all the diverse clusters agree. Participants can view graphics revealing the whole ecosystem of perspectives at any time as it evolves. They can create new statements that respond to what they see in that overview if they wish. Over time their statements tend to become more specific and practical.

After days or weeks of this activity, the results - both consensus statements and divisive statements - are usually turned over to a dialogue among diverse stakeholders, citizens, or decision-makers to inform and stimulate their creative responses to the question. Activities can be organized through which views from polis exercises and dialogues feedback and forth into each other to generate deepening insight and/or specificity.

Polis has been used with populations ranging from 40 to 40,000 people. It is ideal for discovering unrealized possibilities in complex, conflicted situations involving widely diverse perspectives."


##DAO Tools


### Snapshot



* [Snapshot](https://snapshot.org/#/)
* [Home - Snapshot](https://docs.snapshot.org/) Documentation
* [What is Snapshot? The Decentralized Voting System - Decrypt](https://decrypt.co/resources/what-is-snapshot-the-decentralized-voting-system)
* [The holy grail: Off-chain polling with on-chain execution (aragon.org)](https://aragon.org/blog/snapshot)

<img width="638" alt="image" src="https://user-images.githubusercontent.com/77154511/147893396-3278bde2-0e37-460d-989d-60a60657095e.png">
<img width="641" alt="image" src="https://user-images.githubusercontent.com/77154511/147893402-74c218b7-d034-4c06-a8c0-e4eafcbffd58.png">
<img width="637" alt="image" src="https://user-images.githubusercontent.com/77154511/147893409-b29822d1-e448-4c1c-b15a-87d91eeb2fc7.png">




### Gnosis / multisig



* [Overview - Gnosis Safe (gnosis-safe.io)](https://gnosis-safe.io/)
* [👛 Multisig transactions with Gnosis Safe | by Federico Ulfo | Gauntlet | Medium](https://medium.com/gauntlet-networks/multisig-transactions-with-gnosis-safe-f5dbe67c1c2d)
* [Protofire Deploys a Fork of Gnosis Safe Multisig into Moonriver to Enforce Security | by ProtoFire.io | ProtoFire Blog | Oct 2021 | Medium](https://medium.com/protofire-blog/protofire-deploys-a-fork-of-gnosis-safe-multisig-into-moonriver-to-enforce-security-13e8630d9569#:~:text=Gnosis%20Safe%20Multisig%20is%20a%20fully%20customized%20crypto,assets%20stored.%20How%20Gnosis%20Safe%20Multisig%20can%20help)
* [Setting up Gnosis Multisignature Wallets - EWF - Confluence (atlassian.net)](https://energyweb.atlassian.net/wiki/spaces/EWF/pages/557908009/Setting+up+Gnosis+Multisignature+Wallets)


### sesh



* [sesh](https://sesh.fyi/)

Regular events are an essential part of almost every DAO, and sesh is the best calendar bot for Discord.


<img width="619" alt="image" src="https://user-images.githubusercontent.com/77154511/147893421-25b99533-5b5d-44b2-822a-eadcdb85ecf5.png">



Bau running sesh's !list command in the DAOhaus Discord

<img width="619" alt="image" src="https://user-images.githubusercontent.com/77154511/147893427-896fcb12-08d1-4ede-94b6-4231cfad9efe.png">



_sesh features_


### Tally

Today at Tally, we build tools and interfaces to scale decentralized decision-making. We have tools to vote, see who is participating in governance, and understand what votes and proposals are available. We support protocols looking to launch on-chain governance with an interface for creating and managing proposals. We help tokenholders keep up with governance via email notifications and to gather delegations and support from their fellow holders.

[Tally (withtally.com)](https://www.withtally.com/) \
 \
[Tally - Explore Governances (defiprime.com)](https://defiprime.com/tally)

DAO overview Dashboard

<img width="641" alt="image" src="https://user-images.githubusercontent.com/77154511/147893434-5e5e1593-3a53-48b1-8f58-c8324b3fa874.png">



All-time top voters with the highest voting power over all governance votes

<img width="558" alt="image" src="https://user-images.githubusercontent.com/77154511/147893443-a45a850a-658e-4065-bc2d-7ae943ab96fb.png">



Insights in the internal governance structure of every DAO \
 
<img width="614" alt="image" src="https://user-images.githubusercontent.com/77154511/147893453-2fa1710e-55a1-435f-9f60-0b1bd54dda18.png">


Insights in all active and ended proposal votes


<img width="596" alt="image" src="https://user-images.githubusercontent.com/77154511/147893470-931a9557-1bbf-43ef-bd64-fefd1f0de99a.png">


