# Getting Pharo runnning from the command line

Here are some simple steps to get pharo ready from the command line. The script 
presupposes that you have a bin folder in your home directory. 

The following script downloads the stable vm version of Pharo 80. Check the web page [https://get.pharo.org/64/](https://get.pharo.org/64/)
to get the possible choices. 

```bash
mkdir bin
cd bin
curl https://get.pharo.org/64/vm80 | bash
```

This script creates two scripts, pharo-ui and pharo-vm both using the contents of the Pharo folder that is also created. 

Once installed you can execute pharo as follows: 

```bash
./pharo-ui Pharo8.image 
```

If you do not want that pharo pops-up a user interface you can invoke it as follows: 

```bash
./pharo Pharo8.image 
```
