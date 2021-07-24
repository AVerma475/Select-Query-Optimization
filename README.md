# Select-Query-Optimization

This is a DS implementation project and the basic point of motivation in this project is learning and implementing algorithms that reduces time and space     complexity. The objective is to minimize the number of disk accesses and thus, this project is concerned with techniques for achieving that objective i.e. techniques for arranging the data on a disk so that any required piece of data, say some specific record, can be located in a few I/O’s as possible.

Self-implemented indexes of a mock RDBMS implementation using B-Trees to improve query performance. Without the index, the RDBMS query is served via page scanand with an index created the RDBMS query is served via index seek leading to lesser numbers of data page loads from the hard disk and higher performance.

Result : For Data set of 10000 rows, Scans reduces from 10000 to 6. (99% faster)
