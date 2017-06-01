# AWS Aurora FAQs

[https://aws.amazon.com/rds/aurora/faqs/](https://aws.amazon.com/rds/aurora/faqs/)

[https://aws.amazon.com/rds/aurora/pricing/](https://aws.amazon.com/rds/aurora/pricing/)

- Aurora is a relational database engine that combines the speed and reliability of high-end commercial databases with the simplicity and cost-effectiveness of open source databases.
- Aurora with MySQL-compatibility delivers up to five times the performance of MySQL without requiring any changes to most MySQL applications.
- MySQL-compatible means that most of the code, applications, drivers and tools you already use today with your MySQL databases can be used with Aurora with little or no change.
- Aurora database engine is designed to be wire-compatible with MySQL 5.6 using the InnoDB storage engine. Certain MySQL features like the MyISAM storage engine are not available with Amazon Aurora.

### How can I migrate from MySQL to Amazon Aurora and vice versa?

- You can use the standard mysqldump utility to export data from MySQL and mysqlimport utility to import data to Amazon Aurora, and vice-versa. 
- You can also use Amazon RDS’s DB Snapshot migration feature to migrate an RDS MySQL DB Snapshot to Amazon Aurora using the AWS Management Console. 

### What are the minimum and maximum storage limits of an Amazon Aurora database?

- The minimum storage is 10GB. 
- Based on your database usage, your Amazon Aurora storage will automatically grow, up to 64 TB, in 10GB increments with no impact to database performance. 
- There is no need to provision storage in advance.

