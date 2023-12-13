# acme-site-automation

Project Title: Automate Data Extraction and Processing(of Acme-test.uipath) through Robotic Process Automation

Project Summary:

The implementation of this project will be carried out in three phases: Login to the site, Data extraction and Storing to Orchestrator Queue, and Processing the Data. These stages are designed to manage knowledge and support processes for the execution of RPA project.

All Workflows Used In RE-Framework :

**Login.xaml**: It login to the Acme-test.uipath.com and open the dashboard of the site.

**Extract.xaml:** It opens work items and Extracts all data and stores it to acmeData Queue( Orchestrator Queue).

**Process.xaml:** It opens the URL of each field stored in Queue and marks the status field to Complete.

Note: In Process.xaml "In_TransactionItem" Variable is used to Dynamically get the data of Queue.
