# 1 install java 
```
sudo apt install openjdk-17-jdk
sudo apt install openjdk-17-jre
```

# 2 get antlr4
```
$ cd /usr/local/lib
$ wget https://www.antlr.org/download/antlr-4.7.2-complete.jar
$ export CLASSPATH=".:/usr/local/lib/antlr-4.7.2-complete.jar:$CLASSPATH"
$ alias antlr4='java -jar /usr/local/lib/antlr-4.7.2-complete.jar'
$ alias grun='java org.antlr.v4.gui.TestRig'
```
