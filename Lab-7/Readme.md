# Working with MySQL Database Service (MDS)
**To create MySQL DB System on MDS, please watch this Youtube video**: https://www.youtube.com/watch?v=dasutiDLTkM
</br>
</br>
**Skip step 1, 2, 3, because you've done it. Go directly to step 4**
</br>
</br>
1.	On the Navigation Menu, under Database, select MySQL -> DB Systems. 
2.	On DB Systems in <Compartment Name> Compartment, click on Create MySQL DB System. 
3.	On Create MySQL DB System, under DB System Information, select a Compartment, enter a Name for the DB System, add a Description, select an Availability Domain, select a Fault Domain, select a configuration for the MySQL Shape, and click Next. 
4.	On Create MySQL DB System, under Database Information, create the Administrator Credentials by entering Username and Password, specify the network information selecting the Virtual Cloud Network and Subnet in the compartment and entering Hosting Name, and click Next.
5.	On Backup Information, select Enable Automatic Backups, select the Backup Retention Period, select Default Backup Window, and click on Create.
6.	The New MySQL DB System will be ready to use after a few minutes. The state will be shown as Creating during the creation.  
7.	The state Active indicates that the DB System is ready to use. Check the MySQL endpoint (Address) under Instances in the MySQL DB System Details page.
  
