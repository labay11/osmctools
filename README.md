# osmctools

Fork of the open source project `osmctools` used to convert OpenStreetMap data between different file types. See the [full documentation](https://wiki.openstreetmap.org/wiki/Osmconvert) or the [usage instructions](https://www.mankier.com/1/osmconvert).

Author of all included tools is [Markus Weber](http://m.m.i24.cc/). All tools (except packaging configs) is completely
made by him and only him even if commit author is someone else.

Some tools can be found in [authors repository](https://gitlab.com/osm-c-tools/osmctools).

## Install

Run `cmake .` from the repository directory to generate the make files.

Once successfull, run `make` to generate the executable files.

## Contributions

An extra option has been added that allows printing of ways nodes as a column in `csv` format.

        --csv-noderef
                Choose this option to add the node references of the ways.

The list of nodes is printed as a `;` separated list at the end of the way line, it is not possible to choose any other order as the list of nodes does not have a fixed length and will make processing more difficult.
