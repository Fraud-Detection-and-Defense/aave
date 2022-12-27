# aave
Data Analysis for Aave Protocol

The Fraud Detection & Defense (FDD) workstream is open-source funding’s first line of defense against malicious sybil attackers who attempt to manipulate Gitcoin’s donor reward system. Consisting of high caliber developers, data scientists, and digital detectives, the team works tirelessly to both proactively prevent and reactively thwart active threats to web3’s flagship public funding protocol, while continuously improving fraud defense detection processes and contributors’ behavior and tendencies analyses. Through their experience defending the Gitcoin protocol, the team has developed advanced analytical approaches for the analysis and understanding of on-chain behavior of wallet accounts. To this end, the team is proposing a wallet segmentation analysis that will help Aave to better understand the behaviors of their user base & characterize platform momentum.

The team is led by Disruption Joe, a crypto DAOizen and workstream lead for FDD. Sybil defense for Gitcoin Grants has prevented over $3 million in illegitimate matching funding. 
 
Project Goals: 


Our goal is to enhance Aave’s understanding of their current and future user base by performing a wallet segmentation analysis that will unearth insights into how groups of users borrow, lend, and interact with the Aave platform. Successful completion of this project will produce personas of wallet addresses that will:


1.    Provide insight into Aave platform usage, group behavior, churn rate, etc
2.    Guide and direct marketing and product development
3.    Produce reproducible analysis that can be used to leverage and identify user behavioral pattern (usage, attitudes, loyalty)
4.    Motivate the selection of exclusive Aave verification stamps to be used in the next iteration of Gitcoin Passport

Project Description: 

The process of developing on chain behavioral personas first begins with a transversal of the subgraphs of the relevant Aave contracts for all wallets that have made one or more event calls.
This list of wallets forms the population sample, a snapshot of all Aave platform users up until that point in time. Platform agnostic characteristic data such as the wallet balance, number of NFTs held and active chains is collected for each wallet along with contract specific counts for individual contract calls.  The former gives a high-level breakdown of the types of wallets that interact with the platform, while the latter set of datum provides a nuanced picture of how the platform is being utilized (user needs and habits).It is at this point the data is transformed and fed into an unsupervised machine learning model that best groups the observations according to behavioral and descriptive similarity. These groups are then visualized and re-expressed as easy to understand personas.

The process implemented code and a slide deck of the results will form the deliverable presented to the Aave community.



Milestones: 
Milestone One: Data Collection, Curation and Munging – In the first phase, on-chain data is collected from the Aave smart contracts. (3 Weeks)
Milestone Two: Segmentation Analysis – Utilizing the data collected from the smart contracts and wallets, unsupervised learning techniques such as Self-Organizing Maps, K-Means, and Hierarchical clusters are applied to the data. (3 Weeks)
Milestone Three: Visualization, Documentation and Presentation – The results of the cluster analysis are formalized, documented, and shared with the Aave community. (2 Weeks)
