# Covid19report
Mediamarkt_interview_PowerBIreport_database
Power BI report is provided as the solution to the Case study assigned.
Microsoft Sql server management studio is used to extract the raw data extracted from the link :https://npgeo-corona-npgeo-de.hub.arcgis.com/datasets/dd4580c810204019a7b8eb3e0b329dd6_0/data
Following steps are performed to transform the raw data:
1. The copy of raw data is maintained as it is (in case of failures)
2. In the staging process : the columns are transformed into english columns for better uderstanding purposes.
3. Assigned appropriate names to the columns for better understanding.
After staging , the next process is to create a business view.
Here the data normalization is performed (3NF)
The redudancy is removed , Primary and foreign keys are generated along with three tables generation: Gender, State and District tables.
Finally using Views : Power BI reports are generated for the specific questions asked in the case study(report is attached)

Tools used and links to download :
SQL Server : https://www.microsoft.com/de-de/sql-server/sql-server-downloads
SSMS: https://docs.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver15
Power BI desktop version :https://powerbi.microsoft.com/en-us/downloads/

