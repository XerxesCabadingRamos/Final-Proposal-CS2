# Quarter 3 Updates

## Members
- Audrey Salvo  
- Xerxes Ramos  
- Daniel Bustamante  
- Chanelle Suriba  
- Zoe Lara  
- Jade Felisan  

## Team Members and Contribution (since Quarter 1)
- **Xerxes Ramos** – Led system development, handled Firebase integration, implemented feature functionalities (Add Transaction, Search Transaction), managed GitHub repository updates, and ensured successful deployment in Google Colab.

- **Audrey Salvo** – Participated in system planning discussions and helped review the project structure and documentation.

- **Daniel Bustamante** – Assisted in organizing repository files and coordinating dataset preparation during earlier phases.

- **Chanelle Suriba** – Contributed to proposal conceptualization and provided feedback on system design.

- **Zoe Lara** – Helped in reviewing documentation and testing system outputs during development stages.

- **Jade Felisan** – Participated in initial project planning and documentation drafting.


## Update (Quarter 3 Feature Implemented)

Feature Implemented:
1. Realtime Databise (FireBase) 
2. Uploading the Transactions JSON to FireBase 
3. Transaction Adding Feature
4. Transaction Searching Feature 

Description:
The system has a stable connection to FireBase's Realtime Database via Google CoLab. The Transactions dataset is uploaded and stored in the database. Users can now add new Transactions and search for existing ones stored in said database.

How it Works:
- CoLab uses a Service Account to connect to FireBase
- The Transactions.json dataset is loaded and uploaded into the database.
- The Transaction Plus Feature allows users to add new Transactions to the database
- The Search Transaction Feature allows users to look for preexisting transactions in the database via transaction ID's.

Firebase Integration:The Firebase Admin SDK is used to authenticate and establish a connection to the Realtime Database. All transaction records are stored under the `transactions` node in the database. Data is written and retrieved dynamically using database references.
