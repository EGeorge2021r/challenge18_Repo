# Challenge18_Repo


# User Story
Role: Lead developer on their decentralized finance team

Goal: Build a blockchain-based ledger system, complete with a user-friendly web interface. 

Reason: This ledger should allow partner banks to conduct financial transactions (that is, to transfer money between senders and receivers) and to verify the integrity of the data in the ledger.

# Requirements
1. Create a Record Data Class

2. Modify the Existing Block Data Class to Store Record Data

3. Add Relevant User Inputs to the Streamlit Interface

4. Test the PyChain Ledger by Storing Records

# Libraries and dependencies
The following libraries and dependencies were deployed:
- import streamlit as st
- from dataclasses import dataclass
- from typing import Any, List
- import datetime as datetime
- import pandas as pd
- import hashlib

# Technology and Applications
- Streamlit Application
- Python
- VS Code
- Pychain

# Explanation  and Usage of Streamlit Application 

The PyChain ledger that is used in this module already includes the functionality to create blocks, perform the proof of work consensus protocol, and validate blocks in the chain. The following were followed to complete and validate the Blockcahin:
1.	Create a Record Data Class
2.	Modify the Existing Block Data Class to Store Record Data
3.	Add Relevant User Inputs to the Streamlit Interface
4.	Test the PyChain Ledger by Storing Records

# Testing the application

To test the complete PyChain ledger and user interface the following steps are required:
1.	In the terminal, navigate to the project folder where the codes are.
2.	In the terminal, run the Streamlit application by using streamlit run pychain.py.
3.	Enter values for the sender, receiver, and amount, and then click the Add Block button. Do this several times to store several blocks in the ledger.
4.	Verify the block contents and hashes in the Streamlit drop-down menu. 
The screenshot of the Streamlit application page below, shows the detail blockchain that consists of multiple blocks.
## Screenshot D2  shows the verification of the block contents and hashes in the Streamlit drop-down menu with the Block Difficulty set 2
![Block content verification_D2 screenshot](https://user-images.githubusercontent.com/88909565/150904819-7babc0f1-d252-4a85-a048-c208319bf61a.png)

## Screenshot D4  shows the verification of the block contents and hashes in the Streamlit drop-down menu with the Block Difficulty set 4
![Block content verification_D4 screenshot](https://user-images.githubusercontent.com/88909565/150904770-d2ce0287-d0e0-4571-8d05-15a41f7bc084.png)

5.	Test the blockchain validation process by using the web interface. 
The Streamlit application page, indicates the validity of the blockchain. See the screenshot below:

## Screenshot Blockchain validation D2  indicate the validity of the blockchain with Block Difficulty set 2
![Blockchain validation_D2 screenshot](https://user-images.githubusercontent.com/88909565/150905003-730ae50b-1ef3-410e-a9ae-b9acde9ee0e0.png)

## Screenshot Blockchain validation D4 indicate the validity of the blockchain with Block Difficulty set 4
![Blockchain validation_D4 screenshot](https://user-images.githubusercontent.com/88909565/150905019-70fa5ce4-efd4-4302-ba85-6de2909ffc88.png)

## At the VS Code terminal, the sample screenshot below shows that the Blockchain is valid.
VS Code Terminal Blockchain output.png
![VS_Code Terminal Blockchain output](https://user-images.githubusercontent.com/88909565/150904685-0022a58b-0fc9-483e-a9bb-d1a990c0e1fb.png)

