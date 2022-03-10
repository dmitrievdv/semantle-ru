So, this is sort of hacked together from a lot of data sources and the
code is a mess.  Here's a hello world of how to get up and running.

1. Install Python requirements using `pip install -r requirements.txt`.

2. Run `python dump-vecs.py` to create an SQLite database and store the main vectors.

3. Run `python dump-hints.py` to create a hints pickle. Wait a very long time.

4. Run `python store-hints.py` to import the pickle into the DB.

5. Run `python semantle.py` for the web server.

Formatting
==========

`black .` to reformat all Python files
