# CSV Data Filter Script

A Bash script to filter data from a CSV file based on various criteria such as last modified date, file size, username, and file extension.




## Usage

    ./tree_filter.sh <csv_file> <-d date> [-s size] [-u user_name] [-e extension] [-h]


Following are the flags used:

* -d, --date <date>: Displays all the files with the specified last modified date (YYYY-MM-DD).
* -s, --size <size>: Displays all the files with given size and greater than that.
* -u, --username <name>: Displays all the files with the specified username/owner.
* -e, --extension <ext>: Displays all the files with the specified extension (Case-Insensitive).
* -h, --help: Display help message.




## Description

This script takes a CSV file as input and filters its data based on the provided criteria. You can filter files by date, size, username/owner, and extension. The script utilizes command-line arguments for specifying the filters. It then displays the lines (rows) from the CSV file that match the filter criteria.

The CSV file should include columns for permissions, owner, size, date, path, and filename. If the size is specified without a unit, it will be considered in bytes. If no matches are found after filtering, the script will display "No Results Found."




## Flow

Here is a detail work flow of this script in the form of flow chart.


![flow chart](./assets/task_flow.svg)



