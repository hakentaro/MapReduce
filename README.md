# MapReduce
A Python code that uses the mrjob package to search GDELT data with the mode running jobs locally

### How to use
- Install mrjob
  ~~~
  $ pip install mrjob
  ~~~

- Store the data you want to count lines in the "GDELT" folder, which was put in the same directory with the Python code.

- Enter the command below in terminal.
  ~~~
  $ python3 mr_line_count.py GDELT/*
  ~~~

- You will get the total numbers of the lines in all of the files in the directory.
