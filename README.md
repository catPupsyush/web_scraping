# Function ga_scraper goes to the GA home page, logins to a GA account, surfs to the User Explorer page,
# sets the Date Range and exports data for every User ID in the Date Range as a json file as <UserID.json> 
# in the in the specified folder.
# Then function ga_scraper outputs information about its performance in the in the specified folder.
#
# Function folderCheck checks resuls of function ga_scraper and output it in the log file:
# 1) the number of files with User IDs' data in the downloaded folder 
# (it ought to be equal to the number of User IDs in the table of total User IDs).
# 2) the availability of data in every file with User ID' data.
# 3) the readability of data in every file with User ID' data.
