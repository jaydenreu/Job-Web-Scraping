# Job Web Scraping
 Scrapes data analyst job postings data from Seek.co.nz

This repository contains two files:
* seek_jobs_data_scraping.ipynb
 - Contains the Python/Jupyter Notebook which scrapes, parses, processes and loads the data
* seek_data_analyst_10.csv
 - Contains the data output scripted in the ipynb file

### Fields:
* [b]role[/b]: Title of the role/job posting
* company: Name of company who posted the role/job
* when_posted: How long ago the job was posted (from 2022-07-29 00:00:00 NZST - note this repository is not dynamically updated)
* sector: Sector in which the company/role operates
* industry: Industry in which the company/role operates
* region: Region in which the company operates/role is based
* district: District in which the company operates/role is based
* salary: Salary and/or benefits for the role (note that most jobs do not have this listed)
* summary: Additional information (such as company info, job requirements, etc).
