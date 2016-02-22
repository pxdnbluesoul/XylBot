##Installation

On CentOS 7, you need a little prep.

`sudo yum update`  
`sudo yum install perl perl-CPAN gcc`  
`sudo cpan` (Let it run through the first-run process, you can take all defaults.)  
`sudo cpan install String::Similarity`  

You may also need to:

`sudo cpan install File::Read`

At that point you should edit the config.ini file and edit the details for your installation, and edit admins.ini following the example entries. 500 is a full admin, 400 is a moderator.

##Additional Reading

http://scpgaming.wikidot.com/mafia-hub