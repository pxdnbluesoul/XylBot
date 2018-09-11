##Installation

On CentOS 7, you need a little prep.

`sudo yum update`  
`sudo yum install perl perl-CPAN gcc`  
`sudo cpan` (Let it run through the first-run process, you can take all defaults.)  
`sudo cpan String::Similarity`  

You may also need to:

`sudo cpan File::Read`
`sudo cpan Time::HiRes` on CentOS 6 or if you get an error stating `No method called "time" for  object. at lib/Net/IRC.pm line 195`

You should now edit the config.ini file and edit the details for your installation, and edit admins.ini following the example entries. 500 is a full admin, 400 is a moderator.

## Standalone Modules

* `mafia/mafia-stats.pl` - Will evaluate `game.log` and generate rankings. You must run the module to get fresh rankings.
* `mafia/estimate-role-power.pl` - Will evaluate `game.log` and compare the efficacy of certain roles versus their expected power, resulting in them being more or less likely to appear to balance a game. Run this periodically to rebalance the bot for your players.

##Additional Reading

http://scpgaming.wikidot.com/mafia-hub
