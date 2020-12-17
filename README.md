# CS143 Blockchain Voter Registratin



## How to run to run

Install the dependencies,

```sh
$ pip install -r requirements.txt
```

Start a blockchain node server,

```sh
$ export FLASK_APP=node_server.py
$ flask run --port 8000
```

Run the application on a different terminal session,

```sh
$ python run_app.py

```
Find the application running on http://localhost:5000

From there, add in the information and click submit. Next Click register to mine and then resync to view the newly registered user. 
Multiple miners can be added by running flask on different ports.
