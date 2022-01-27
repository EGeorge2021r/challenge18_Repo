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
![Blockchain verification D2_screenshot](https://user-images.githubusercontent.com/88909565/151301123-88cccc80-f32e-4d02-8a1a-b258c564bd77.png)

5.	Test the blockchain validation process by using the web interface. 
The Streamlit application page, indicates the validity of the blockchain. See the screenshot below:

## Screenshot D4  shows the verification of the block contents and hashes in the Streamlit drop-down menu with the Block Difficulty set 4
![Blockchain verification D4_screenshot](https://user-images.githubusercontent.com/88909565/151301707-376a1b47-b85a-4679-bc26-7575751736d0.png)

## Screenshot Blockchain validation D4 indicate the validity of the blockchain with Block Difficulty set 4
![Block content validation D4_screenshot](https://user-images.githubusercontent.com/88909565/151301018-4de12b0d-a673-4453-96de-8a31ca83eaf0.png)

## At the VS Code terminal, the sample screenshot below shows that the Blockchain is valid.
VS Code Terminal Blockchain output.png
![VS_Code Terminal Blockchain_output](https://user-images.githubusercontent.com/88909565/151300943-9b3a3b15-d7c4-4b00-b819-49c75fe95ce3.png)

