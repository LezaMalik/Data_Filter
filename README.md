# CSV Data Filter Script

A Bash script to filter data from a CSV file based on various criteria such as last modified date, file size, username, and file extension.



## Usage

    ./tree_filter.sh <csv_file> <-d date> [-s size] [-u user_name] [-e extension] [-h]


* -d, --date <date>: Displays all the files with the specified last modified date (YYYY-MM-DD).
* -s, --size <size>: Displays all the files with given size and greater than that.
* -u, --username <name>: Displays all the files with the specified username/owner.
* -e, --extension <ext>: Displays all the files with the specified extension (Case-Insensitive).
* -h, --help: Display help message.


## Flow



![flow chart](./assets/task_flow.svg)
  
