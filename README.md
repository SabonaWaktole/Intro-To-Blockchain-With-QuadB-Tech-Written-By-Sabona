# Blockchain Simulation with Flask

This is a simple blockchain simulation built using Python and Flask. The application mimics the core features of a blockchain, including creating blocks, validating the chain, adding transactions, mining blocks with Proof-of-Work, and demonstrating chain tampering detection.

---

## Features

1. **Blockchain Structure**:  
   - Each block contains:
     - Block index
     - Timestamp
     - List of transactions
     - Hash of the previous block
     - Current block hash

2. **Hashing**:  
   - SHA-256 is used to generate hashes for blocks.

3. **Dynamic Transactions**:  
   - Add transactions dynamically to the unconfirmed transaction pool.

4. **Proof-of-Work**:  
   - Simple computational difficulty for mining blocks.

5. **Chain Validation**:  
   - Validates the integrity of the blockchain.

6. **Tampering Detection**:  
   - Tampering with block data is detected by validation.

7. **QR Code Generation (Optional)**:  
   - Generate QR codes for transactions (requires Flask-QRcode).

---

## Requirements

The project requires the following Python libraries:

- `certifi`
- `charset-normalizer`
- `click`
- `colorama`
- `Flask`
- `Flask-QRcode`
- `idna`
- `itsdangerous`
- `Jinja2`
- `MarkupSafe`
- `Pillow`
- `pycryptodome`
- `qrcode`
- `requests`
- `urllib3`
- `Werkzeug`

---

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/<username>/<repository>.git
   cd <repository>
HOW TO RUN

clone this repository to your local machine.

install required dependencies

    pip install -r requirements.txt

change sys path to your local machine path in Backend/core/blockchain.py

    sys.path.append("path to your project folder")
    
save the changes and run the file blockchain.py
    open terminal
    
direct to your project path 
    
        cd pathtoyourproject\Blockchain\Backend\core
        
run the python file
    
        python blockchain.py
        
got to localhost([http://127.0.0.1:5000/]) to use the web version of your application
