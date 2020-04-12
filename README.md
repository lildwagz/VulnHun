VulnHun
===============
```
Search exploits/vulnerabilities in multiple databases online!

VulnHun is a multiplatform tool(Windows and Linux), which was developed in PHP with the aim of helping the hacker 
community to find exploits or 'vulnerabilities', using online databases, below is the list of databases which 
can be used in this release:
1. Exploit-DB
2. MIlw00rm
3. PacketStormSecurity
4. IntelligentExploit
5. IEDB
6. CVE
7. Siph0n

The tool offers several options, such as:
* Search individual.
* Search with multiple words(list).
* Select which databases will be used for research.
* Filter to remove repeatable results.
* Blocking specific databases.
* Save log with the survey data.
* Save the exploits/vulnerabilities found.
* Use of proxy.
* Set the time that the databases have to answer.
* Conduct research just indicating the author's name.
* Disable display of the banner.

Simple use: php VulnHun.php [command] [term]
        Ex: php VulnHun.php --search WordPress


```

TO RUN THE SCRIPT
----
```
To use all the features as the tool provides, the following is recommended:
PHP Version(cli) 5.5.8 or higher
 php5-cli         Lib
cURL support      Enabled
 php5-curl        Lib
cURL Version      7.40.0 or higher
allow_url_fopen   On
Permission        Writing & Reading

Dependencies necessary:
php5
php5-cli
php5-curl
curl
libcurl3

If you are unsure if the dependencies are installed, run the following command(Only for linux):
        php "VulnHun.php" --install-dependencie
Or run in terminal: sudo apt-get install php5 php5-cli php5-curl curl libcurl3
```


```


Screenshot

<img src="https://raw.githubusercontent.com/lildwagz/VulnHun/master/photo_2020-04-12_12-50-52.jpg">
<img src="https://raw.githubusercontent.com/lildwagz/VulnHun/master/photo_2020-04-12_12-50-54.jpg">



If you find any bug or want to make any suggestions, please contact me by email
