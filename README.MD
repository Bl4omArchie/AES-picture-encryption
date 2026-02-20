# AES picture encryption

**Disclaimer: None of the cryptography in this repository is meant to be used for real-life purposes; it is only intended for educational and testing purposes.**

# Installation

1- Clone the repository
```py
git clone https://github.com/Bl4omArchie/AES-picture-encryption
```

2- Create and activate a python env
```bash
python3 -m venv rng
source rng/bin/activate 
```

3- Install dependencies : 
```bash
pip3 install -r requirements.txt
```


# Features
- aes_picture_encrypt : encrypt and decrypt pictures using AES with pycryptodome library.

- streamlit dashboard for AES encryption :
![Streamlit dashboard preview for AES picture encryption](preview.png)

Use this command to launch the dashboard :
```bash
streamlit run main.py 
```

- entropy_calculator : compute the entropy of a given file
