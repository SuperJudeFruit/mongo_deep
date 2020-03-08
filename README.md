# mongo_deep
 Tool to make a deep and precise analysis of a Mongo database

# usage: mongo_reader.py [-h] [-d DB] [-c COLLECTIONS] [-s] [-p] [-v] [-i IO]

Python tool used to make a deep and precise analysis of a Mongo database

optional arguments:
  -h, --help            show this help message and exit
  -d DB, --db DB        Database to explore.
  -c COLLECTIONS, --collections COLLECTIONS
                        Precise collections to explore
  -s, --stats           Display statistics of collection(s).
  -p, --path            Display every different path present in collection,
                        only the first occurence is displayed.
  -v, --value           Display value of each path present in collection,
                        every values are displayed. This can take a long time.
  -i IO, --io IO        Put result into a file.
