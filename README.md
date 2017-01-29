# State Library Statistical Analysis
This project shows graphical analysis of library data using statistics provided by State Library Agency (StLA)
The project demonstrates integration involving semantic web technologies. The project uses multiple sets of semantically enabled data (and generally already available).The project requires understanding the semantic representation data sources and use of triples from multiple data sets to represent knowledge not present in any single set.

Description :
We are combining 2 datasets which contains the data from State Library Agency Survey  Fiscal year 2006 and Fiscal year 2007. This datasets are national census of state library agencies. A state library agency is the official agency of a state that is charged by state law with the extension and development of public library services throughout the state and that has adequate authority under state law to administer state plans in accordance with the provisions of the Library Services and Technology Act (LSTA). Beyond these two roles, state library agencies vary greatly. This dataset provides information on the range of roles played by state library agencies and the various combinations of fiscal, human, and informational resources invested in such work. 

Expected Results :
So, to output some interesting information using these datasets, we’ll try to use data presented in the datasets such as : Collections such as, books, audio, video, Govt docs etc. Transactions such as, provided to other libraries or received from other libraries. Total staff members (which is the sum of the staff in categories : Administrative, Library Development, Library Services, Other staff). Total Revenue. Total Expenditure.  These all datas will be categorized and referenced against each states and its population. Additionally, combining 2 datasets and extracting all the mentioned information will provide us the difference in those which occurred between fiscal year 2006 and fiscal year 2007. So, some interesting output like difference in collection sizes, staff member numbers, transactions, total revenue and total expenditure will be apparent. 

LOGD datasets used here: 
http://logd.tw.rpi.edu/source/data-gov/dataset/353.html
http://logd.tw.rpi.edu/source/data-gov/dataset/354.html


Below are the screenshots of the bar charts that are displayed when we run the website and the fuseki server.

![Bookvolume vs. Year 2006-07 & Various libraries](/Screenshots/Bookvolume.png "Bookvolume difference between year 2006-07")

![Total Staff vs. Year 2006-07 & Various libraries](/Screenshots/TotalStaff.png "Total Staff difference between year 2006-07")

![Total Income vs. Year 2006-07 & Various libraries](/Screenshots/TotalIncome.png "Total Income difference between year 2006-07")

![Total Expense vs. Year 2006-07 & Various libraries](/Screenshots/TotalExpense.png "Total Expense difference between year 2006-07")
