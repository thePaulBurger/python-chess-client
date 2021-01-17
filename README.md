## A python chess client

A simple client to get started with coding a chess-ai in python. This client
talks to the chess server running on waltersmuts.com, playing against the Greedy
algorithm, by default. There is also a `Random` opponent for if you're struggling.

Take a look at the `example.py` file and you will see how to use the
`chessclient` module. Per default it currently outputs the board state in
[Forsyth–Edwards Notation]( https://en.wikipedia.org/wiki/Forsyth%E2%80%93Edwards_Notation)
but if you want to write a nicer frontend, pull-requests are welcome.

This is just the start... Much more to come :D

### Dependencies
* python3
* python modules in `requirements.txt`

### Running
On some systems python version 3 and pip is aliased to `pip3` and `python3` so
please change commands accordingly.
```
git clone https://github.com/WalterSmuts/python-chess-client.git
pip install -r requirements.txt
cd python-chess-client
python example.py
```

If you're interested in what's happening behind the curtains, check out
[chess-server](https://github.com/WalterSmuts/chess-server). If you want, you
can clone it and run it locally, pointing the client towards the local
endpoint. Currently it's quite bare, but I've planned a bunch more features.

### Planned features:
* Play against another client
* Multiple concurrent games
* Time constraints
