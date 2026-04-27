# hw2
#Created Documentation with above information.
Found and listed Data set to be used in this project.
Created GitHub repository for HW1 named hw1.
Shared with Professor, made into collaborator.
Logged into GitHub account on Git Bash.
In hw1 directory/repository on Git Bash, created a test.txt file, committed, and pushed to GitHub for validation.
Curled Data.gov: Washington Technology Solutions (WATech) State of Washington Open Data on Electric Vehicle Population Data
https://data.wa.gov/api/views/f6w7-q2d2/rows.csv?accessType=DOWNLOAD
and pushed to repository.
Used Head to determine that my target column is $9
Used the following command to print and save the 9th column from ev.csv to a new file named evt.csv: awk -F’,’ ‘{print $9}’ ev.csv > evt.csv
cat evt.csv to ensure the file contains either “Battery Electric Vehicle (BEV)” or “Plug-in Hybrid Electric Vehicle (PHEV)”
Added, committed, and pushed updates (evt.csv).
Used the following command to count the number of BEV in evt.csv file and print the count into a new output called bev.csv: awk -F',' -v target="Battery Electric Vehicle (BEV)" '$1 == target {count++} END {print count}' evt.csv > bev.csv
Used the following command to count the number of PHEV in evt.csv file and print the count into a new output called phev.csv: awk -F',' -v target="Plug-in Hybrid Electric Vehicle (PHEV) " '$1 == target {count++} END {print count}' evt.csv > phev.csv
Added, committed, pushed repository to GitHub.
Created GitHub repository for HW2 named hw2.
Shared with Professor, made into collaborator.
Logged into GitHub account on Git Bash.
Created, added, committed, and pushed a “test.txt” file to hw2 repository to ensure functioning repository connection with Git Bash.
Uploaded hw1 repository files to hw2 repository.
Curled Data.gov: Washington Technology Solutions (WATech) State of Washington Open Data on Electric Vehicle Population Data
https://data.wa.gov/api/views/f6w7-q2d2/rows.csv?accessType=DOWNLOAD
and pushed to repository.
Created an .ipynb file that first counted PHEVs and BEVs in Electric Vehicle Types and then filtered the columns by “Electric Vehicle Type” == “Battery Electric Vehicle (BEV)” then grouped by “Make” then counted, then ordered by Count Descending & filtering the columns by “Electric Vehicle Type” == “Plug-in Hybrid Electric Vehicle (PHEV)” then grouped by “Make” then counted, then ordered by Count Descending.
Downloaded. ipynb file and uploaded to GitHub.
Pulled hw2 repository into Git Bash clone to keep consistency.
