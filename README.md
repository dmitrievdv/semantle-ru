So, this is sort of hacked together from a lot of data sources and the
code is a mess.  Here's a hello world of how to get up and running.

1. Install Python requirements using `pip3 install -r requirements.txt`.

2. Place `russian-w2v.bin` in the parent directory.

3. Run `python3 dump-vecs.py` to create an SQLite database and store the main vectors.

4. Run `python3 dump-hints.py` to create a hints pickle. Wait a very long time.

5. Run `python3 store-hints.py` to import the pickle into the DB.

6. Run `python3 semantle.py` for the web server.

Formatting
==========

`black .` to reformat all Python files
