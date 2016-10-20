Assigment-1: The team work collaboratively on the city bike report. The report can be viewed with its authors on the Authorea website.

https://www.authorea.com/users/106219/articles/134338/_show_article?access_token=8Nww4GhkDJi3rmQq1Ec2pw

Assinnment-2: The team had a difficulty reading the csv file. William Xia from the team suggested to delete the existign PUI2016data.txt 
file and create a PUI2016data folder manually.
Marc Toneatto then recommended to manually save the csv and shp files into this folder after download and call them into code with 
the gp.GeoDataFrame.from_file and gp.GeoDataFrame.from_csv methods.
I downloaded the mn_mappluto_16v1.zip to the PUI2016 from the NYC open data  opended it with zip.Zip and created namelist to read namelist.
I was also able to get the first plots. I could not continue because the gp.GeoDataFrame.from_file for the bsize returns only the geometry
not the rest of the information needed for BBL. I could get floats for the EUI kBtu/ft2 but it would not produce for the BBL. therefore no floats.
This is where this program stops.
