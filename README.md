# ETL-Data-Lineage

This is a small demo on how to visualize ETL data flows, and on how to browse the data flows to answer **data lineage** questions such as

- I have a data warehouse table *sales_order_row* that is used in reporting. Where does the data come from?
- There will be a change SAP table *LIPS*. What do I need to change or check in the ETL?


This demo is created by a tool that I have developed. So, everything you see is created **automatically** from an ETL tool (in this case IBM Cognos Data Manager). This is only a small portion of the original visualisation.

Some explanations

- **squares** are databases (or source systems)
- **ovals** are database tables
- **arrows** are the low level ETL programs (that read from one of more tables and write to one of more tables)

![alt text](https://github.com/PaavoT/ETL-Data-Lineage/blob/master/FORWARD_sap__lips.jpg)

How to use the demo

- download the zip, unzip it, and 
- open **index.svg** with a browser.

You should see this.. the overall ETL landscape. From there you can drill down to the details to see how data flows from a table to another, and even see the SQL that is used in the ETL.

![alt text](https://github.com/PaavoT/ETL-Data-Lineage/blob/master/index.jpg)

Have fun!
