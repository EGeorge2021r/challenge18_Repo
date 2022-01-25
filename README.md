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
See screenshotes below:

4.	Verify the block contents and hashes in the Streamlit drop-down menu. 
The screenshot of the Streamlit application page, shows the detail blockchain that consists of multiple blocks. 
5.	Test the blockchain validation process by using the web interface. 
The Streamlit application page, indicateS the validity of the blockchain. See the screenshot below:
 

