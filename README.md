# Subnet Calc Trojan
 A Subnet Calcualtor which installs backdoors on a linux system and exfiltrates system info to a mySQL server.

mySQL API Libraries:
apt-get install libmysqlclient-dev

To Compile:
gcc -o SubnetCalc 'Subnet Calculator.c' $(mysql_config --cflags) $(mysql_config --libs)
	*The order is important