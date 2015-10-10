# Shell-script-to-create-a-MySQL-BBDD-from-a-csv-file
These are two script to automate the load into a Mysql BBDD tables from a csv file

There are two differents versions of these shell scripts:</br>
1-scriptFullScan </br>
2-scriptQuickly

The first one optimize the craation of the BBDD fields lenght and the second one assigned the value passed in the second argument.

Use:
Two script needs as first argument the name of the file ( without the extension) and only the second script needs as second 
argument the length of the fields.

Examples:</br>
./scriptFullScan nameOfCsvFile
</br>
./scriptQuickly nameOfCsvFile 255

Finally in both scripts you will have to add into then, the path of the csv file and your BBDD username and password 

You can do in your terminal a #which mysql to know waht will be the path that you have to fill into the script

Be carefull inside the script maybe you will need ot change the end of file \r by \n
