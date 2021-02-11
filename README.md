## generates a report of employess that started on a given date

#### Analysis of CSV file with Python

A Python script that reads a file from URI and generates a report on the employees that started on a given date.

##### Example of data format:

`{ datetime.datetime(2018, 7, 13, 0, 0): ['Alfreda Ryan', 'Jameson Rowland', 'Jasmine Howard'], datetime.datetime(2018, 3, 9, 0, 0): ['Hamilton Manning'], datetime.datetime(2020, 1, 8, 0, 0): ['Lyle Schultz'], datetime.datetime(2019, 10, 16, 0, 0): ['Hu Hyde', 'Lesley Fuentes'], datetime.datetime(2020, 6, 27, 0, 0): ['Melanie David', 'Jordan Golden'], }`

##### Output example:

`{ '2019-05-06': ['Rudyard Williamson', 'Paul Spears', 'Vaughan English'], '2020-03-09': ['Kane Rosa', 'Mannix Estes', 'Josiah Morrow', 'Rhiannon Dodson'], '2018-09-06': ['Jamalia Clarke'], '2020-06-11': ['Kiona Nguyen'], '2020-06-25': ['Quynn Parsons', 'Katell Gill'], '2018-01-26': ['Echo Foster', 'Alana Potts'], '2018-01-13': ['Brody Carter'], '2020-06-20': ['Jarrod Nicholson'], '2018-05-31': ['Alma Ford', 'Judah Sloan'], }`
