# monero-etl
Tool to get your personal transaction data out of the Monero blockchain into other data formats.

* release 0.0.2
* Currently supports csv destination
* Additional  destinations planned: SQL and BeanCounter
* open source: https://github.com/tiedtoastar/monero-etl/
* works with Monero 0.12.x and later
* Provides easy step by step configuration to your running Monero RPC
* python 3.x compatible

Want to help?

If you find this project useful, please consider a donation to the following address: 

* 41q64QdRUTWfHDcFFhdD5XDwPR6RVY6haPWEgih66HB3XzDwv2naW2CSYvsJsbgpRMTYZ5KW9wMSTJekHM8Tpjj6N7GQREi

Please support developers that made this project possible:

* https://github.com/emesik/monero-python


Usage
-----------

1. Clone the repo
2. Open terminal or command line
3. Start Monerod
4. Start monero-wallet-rpc
5. In the director above monero-etl
6. Create virtualenv & activate it

.

    python3 -m venv .venv
    source .venv/bin/activate

7. Install monero-python

.

    pip install git+https://github.com/emesik/monero-python.git

6. Run tool
First time it is run, you will be asked for the details to connect to your monero rpc.
Outputted file will be in your current directory
.

    python monero-etl

