# File-Sender-Python
# How to Transfer Files in the Network using Sockets in Python
To run this:
- `pip install -r requirements.txt`.
- ### For the server ( the receiver ):
    - 
        ```
        python receiver.py
        ```
- ### For the client ( the sender ):
    - 
        ```
        C:\> python sender.py --help
        usage: sender.py [-h] [-p PORT] file host

        Simple File Sender

        positional arguments:
        file                  File name to send
        host                  The host/IP address of the receiver

        optional arguments:
        -h, --help            show this help message and exit
        -p PORT, --port PORT  Port to use, default is 5001
        ```
        For instance, if you want to send `download.jpg` to `192.168.31.143`:
        ```
        python3 sender.py download.jpg 192.168.31.143
        ```
