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
![Block content verification D2 screenshot](https://user-images.githubusercontent.com/88909565/150897217-1bf11e04-40f3-4cd6-b2be-650be14b2cb9.png)

![Block content verification D4 screenshot](https://user-images.githubusercontent.com/88909565/150897257-8ad29610-6bff-415b-9270-c8394bd89693.png)

5.	Test the blockchain validation process by using the web interface. 
The Streamlit application page, indicateS the validity of the blockchain. See the screenshot below:
![Blockchain validation D2 screenshot](https://user-images.githubusercontent.com/88909565/150897363-d9b9d16d-2713-4b2f-91be-1d8f7767ec10.png)

![Blockchain validation D4 screenshot](https://user-images.githubusercontent.com/88909565/150897391-329aafeb-d8a6-4272-8172-f8aac8f92bb8.png)

At the terminal, the sample screenshot below shows that the Blockchain is valid.
VS Code Terminal Blockchain output.png
![VS Code Terminal Blockchain output](https://user-images.githubusercontent.com/88909565/150897471-af0d30ba-5078-487e-bef0-34bcb26f4857.png)
