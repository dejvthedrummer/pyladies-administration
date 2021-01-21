#! /bin/bash

# following code works quite nicely but returns counts per each name per each file

#for x in ./pyladies.cz/teams/*.yml 
#	echo $(grep -n "name:" $x | cut -d ":" -f 3 | cut -d " " -f 2 | sort | uniq -c)
#	#echo $(grep -o 'Ivana' ./pyladies.cz/teams/brno.yml | wc -Toml)
#done

x=./pyladies.cz/teams
echo $(grep -n 'name:' $x/*.yml| cut -d ":" -f 4 | cut -d " " -f 2 | sort | uniq -c | sort -r)
