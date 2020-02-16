## Inspiration
We're both big blockchain nerds – we wanted to explore the technical territory by building a dApp. Some of our other ideas included an accountability cryptocurrency, medical data stored on blockchain, and crypto-based health incentive programs.

Given recent drama surrounding college admissions scandals & inequities in education access, we ultimately thought the most interesting & feasible use case was in education.

## What it does
Bloqi provides secure verification of academic credentials (eg. transcripts, enrollment, certifications) for recruiters, jobseekers, and educational institutions.
For example: when Emily earns a diploma from Stanford, the university sends her the official digital document via Bloqi. When she applies to jobs, employers cross-check her résumé with her credentials on Bloqi -- with full confidence in its security. She can't lie in the future about attending UC Berkeley (the better school), and it saves her one less step in the background check process.

Increased transparency, honesty, and security improves job-searching and college admissions for all parties involved.

## How we built it
The smart contract logic and workflow was developed in Solidity (an Ethereum-specific, JS-like language); the front-end web app was built in ReactJS. Our file storage, Ethereum network handling, and user authentication are handled in Microsoft Azure Blockchain Workbench API calls.

## Challenges we ran into
One of us had never attended a hackathon before, and the other had never written a line of Javascript before TreeHacks. 

We first ran into a buggy Azure Blockchain Workbench configuration script with little documentation (con of working on a blockchain project!) We spent a majority of the day trying to circumvent it and manually get ourselves set up.

We also had trouble connecting our webapp to the Microsoft Azure Blockchain Workbench through API calls. We are both very inexperienced with API access, and the blockchain workbench required many more authentication steps because of the nature of the technology. We've both also never written fullstack applications.

## Accomplishments that we're proud of
We were successfully able to develop a smart contract in Solidity (!!), create the configuration and metadata file for it, and run the contract in our Azure application. With that, we fully deployed the blockchain application, but we wanted to make it more user-friendly and made the web-app. Additionally, a first time feat for both of us was actually connecting the web-app to the workbench with get and post API calls.

## What we learned
A better understanding of dApp architecture & the technicalities of blockchain! By trying to manually configure our app for Azure, we were forced to read through clunky documentation to understand 1) how decentralized apps normally run, 2) how ReactJS worked, and 3) how to make API calls within react to Azure services.

## What's next for Bloqi
The technology can be easily altered to fit use-cases in healthcare, HR, or business where secure verification of personal information is paramount! We see Bloqi most likely being applied in either the educational or healthcare space.
