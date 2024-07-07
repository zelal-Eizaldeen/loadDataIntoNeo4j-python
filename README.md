Load data into Neo4j
1. Install prerequisite packages by running the command below in the terminal. $ pip3 install pandas
2. Change director (cd) to the folder of your data files. Run the following shell script (which you download from the shared folder) in the terminal to generate data for Neo4j.
$ chmod +x GenerateNeo4jCSV.sh $ ./GenerateNeo4jCSV.sh
A neo4j_data directory will be created containing the processed data files.
