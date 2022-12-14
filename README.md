# weather
Here is a small script you can use on your linux machine to check the weather of any place anywhere anytime!

This script is based on the wttr.in api created by Igor Chubin on github. The official repository for the api can be accessed here:

```
https://github.com/chubin/wttr.in
```

The help page for this command has not been created yet but the instructions of using it have been mentioned in this README file. Those using the weather command are recommended to go through those.

Here are the flags the command accepts :

```
-r | --region : This flag gives you the freedom to know the weather of any place
Example : weather -r london or weather --region london
```

```
-h | --help : This flag will give you a help page created by Igor Chubin as output
Example : weather -h or weather --help
```
Note : weather --help or weather -h will lead you to the official help page created by Igor Chubin which gives you instructions on directly accessing the weather through curl requests. This script has been made to make that process a bit simpler and more intuitive. 

```
-d | --data-rich : The detailed information about the weather of a place including parameters like astronomy can be known through this flag
Example : weather -d london or weather --data-rich london
```

If you are using the command without a flag, it will give you the weather of your current location

Here are the instructions to use this command on your machine

Before starting, move into your downloads directory

```
cd Downloads/
```

Then clone the repository with the following command

```
git clone https://github.com/aaravshrivastav04/weather.git
```

Now move into the directory containing the script


```
cd weather/src
```

Then move the script into the /usr/bin directory

```
sudo mv weather /usr/bin
```

Finally, you can delete the cloned repository from your machine

```
cd ~/Downloads
sudo rm -rf weather
```


Now, you can use this command to check the weather of any place anywhere anytime, enjoy!
