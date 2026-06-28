# qrandom
QRNG based random numbers

Fetch QRNG based numbers from https://quantumnumbers.anu.edu.au/

# Note
Do not use for production. Use a QRNG USB Key. 

# Requirements
You need a API key, register is free.

# Install
python -m venv .venv

pip install -r requirements.txt

# Run
ANU_API_KEY="Your API key" python3 qentropy.py -l 512 -o qentropy.bin

