# PyChain Ledger
This Python file updates the provided PyChain ledger structure by adding a Record data class, modifying the existing Block data class to store record data, and adding relevant user inputs to the Streamlit interface.

## Step 1: Create a Record Data Class
* Create a new data class named Record.
* This class will serve as the blueprint for the financial transaction records that the blocks of the ledger will store.
* The Record class consists of the sender, receiver, and amount attributes.
## Step 2: Modify the Existing Block Data Class to Store Record Data
* Change the existing Block data class by replacing the generic data attribute with a record attribute that's of type Record.
* The Block class also includes a hash_block() method that calculates the SHA-256 hash of the block.
## Step 3: Add Relevant User Inputs to the Streamlit Interface
* Create additional user input areas in the Streamlit application to collect the relevant information for each financial record that will be stored in the PyChain ledger.
* These input areas should capture the sender, receiver, and amount for each transaction that will be stored in the Block record.
## Step 4: Test the PyChain Ledger by Storing Records
* Test the complete PyChain ledger by storing financial records and checking if the ledger is valid.
