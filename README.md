# csvserver
1.1 Docker failed to as there in no input data file
1.2 Created the script to generate the csv file name inputFile
1.3 I inspected the continer it was exposed on port 9300
1.4 I ran the continer using the command docker run  -v /root/testscript/inputdata:/csvserver/inputFile  -d -p 9393:9300 -e CSVSERVER_BORDER=Orange infracloudio/csvserver
Note: /root/testscript/inputdata is the input file location, depending on your path, you would need to change this value.

Docker-compose file is uploaded.


I didn't work on Part 3 as I idn't worked on prometheus yet 

