This file is a part of Jenkins job.
The job collects the info about backups on each step by this command: `echo "service,type,date,location,size" > confluence_page.txt`
To launch script run the next lide of code: `python publish_confluence_page_v2.py -e ${USER} -t ${PASS} -u https://_name_of_space_.atlassian.net/wiki -p name_of_page -f ../confluence_page.txt -d'`
