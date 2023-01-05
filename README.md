![logo](logo.png)

# Pagger
A collection of scripts to generate Sub-GHz raw files compatible with the Flipper Zero to handle restaurants/kiosks pager systems.

### Supported systems:
[Retekess T119](https://pawcker.github.io/pagger/retekess-t119/retekess-t119.html)\
[Retekess TD174](https://pawcker.github.io/pagger/retekess-td119/retekess-td119.html)

### How to use:
Get your Flipper Zero, go to **_Sub-GHz_** -> **_Read_** and try to detect some useful signal:

![read](read.jpg)

Once you get your key, go to the related Pagger generator and write it in the form, you will be able to calculate back the station, pager and action numbers:

![calculate-back](calculate-back.jpg)

From there you can generate a single key file for a single pager:

![key-file](key-file.jpg)

or a combo raw file for multiple pagers: 

![raw-file](raw-file.jpg)

### Contribute:
If you have a new generator, please PR it.\
If you simply have key/raw files of an unsupported system, open a new Issue with brand, model, pager number and as much info as you can have, this will help the community to work on it.\
At the moment I have no time or interest to develop a Flipper Zero app.\
Feel free to use this code to build your own project, in that case let me know, I'd like to check it out!

### Disclaimer:
I developed these scripts for research purposes.\
I don't endorse any attack that could damage any public service, so please use it responsibly.

### Credits:
Thanks to [ShotokanZH](https://github.com/ShotokanZH) for his awesome work with [flipper_sub_plotters_comparers](https://github.com/ShotokanZH/flipper_sub_plotters_comparers)