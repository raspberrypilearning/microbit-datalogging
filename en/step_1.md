You can record data on your V2 micro:bit using the built in sensors and inputs. 
You will need to install an extension to use this.

In this example, the data from sound levels have been logged.

<div style="position:relative;height:calc(175px + 5em);width:100%;overflow:hidden;"><iframe style="position:relative;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/---codeembed#pub:_VCJdqy3yALDh" allowfullscreen="allowfullscreen" frameborder="0" sandbox="allow-scripts allow-same-origin"></iframe></div>


On the menu panel, click on **Extensions**. Another window will open showing recommended extensions. 

Click on the **data logger** and it will be installed as a menu item.

![The data logger extension being installed by clicking the extensions menu and then 'data logger'. A new block menu appears labelled 'Data Logger'.](images/installing-datalogger.gif)


You can find a `log data`{:class='microbitdatalogger'} block inside the `Data Logger`{:class='microbitdatalogger'} menu.

<img src="images/data-logger.png" alt="The Data Logger menu with the 'log data column...value' block highlighted." width="350"/>

Place the `log data`{:class='microbitdatalogger'} block inside an event block or a loop block. The `every`{:class='microbitloops'} block has been used in this example.

<div style="position:relative;height:calc(175px + 5em);width:100%;overflow:hidden;"><iframe style="position:relative;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/---codeembed#pub:_fY47PteVYTR2" allowfullscreen="allowfullscreen" frameborder="0" sandbox="allow-scripts allow-same-origin"></iframe></div>


You need to label your column field with a useful name for your data. In this example, the column has been labelled `Sound Level`.

<div style="position:relative;height:calc(175px + 5em);width:100%;overflow:hidden;"><iframe style="position:relative;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/---codeembed#pub:_fY47PteVYTR2" allowfullscreen="allowfullscreen" frameborder="0" sandbox="allow-scripts allow-same-origin"></iframe></div>


You also need to add the input sensor that will be logged into the value field of the `log data`{:class='microbitdatalogger'} block.

In this example, the `sound level`{:class='microbitinput'} block which can be found in the `Input`{:class='microbitinput'} menu has been used.

<div style="position:relative;height:calc(175px + 5em);width:100%;overflow:hidden;"><iframe style="position:relative;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/---codeembed#pub:_XbgU79F93PvT" allowfullscreen="allowfullscreen" frameborder="0" sandbox="allow-scripts allow-same-origin"></iframe></div>

You can view the data logged on your micro:bit by plugging it into your computer and opening the data file. 

You can add more than one sensor to be logged on the same `log data`{:class='microbitdatalogger'} block. 



### Logging data for V1 users

If you are using a micro:bit V1, you can only log data using two microbits. One transmits the data using the radio and the other receives this data.

Take a look at the [project from micro:bit to help you log data on the V1](https://microbit.org/projects/make-it-code-it/makecode-wireless-data-logger/#sensor-/-transmitter){:target="_blank"}
