# DEVOIR-LINUX
Installation MySQL+Apache+PHP
Premièrement, MySQL :
Décompresser et desarchiver le fichier : $ tar -xf mysql-8.0.3.tar.gz
$ cd mysql-8.0.3
$ sudo apt install libssl-dev
$ ./configure
$ make
$ sudo make install 
\n
Deuxièmement, Apache :
Décompresser et desarchiver le fichier : $tar -xf httpd.tar.gz
$ cd httpd
$ ./configure --prefix=/usr/local/apache
$ make 
$ sudo make install 
\n
Troisièmement, pour PHP 
Meme étap décompresser et desarchiver le fichier 
$ tar -xf php.tar.gz
$ cd php 
$ sudo apt install libsslite3-dev
$ make 
$ sudo make install 
