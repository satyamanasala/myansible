nano roles/stack/templates/context.xml.j2
xml version should be 1.0

<copy the entire context.xml> with resource also at the end 

in the last line modify as
jdbc:mysql://{{ansible_hostname}}:3306
username:"{{DBUSER}}"
password:"{{DBPASS}}"