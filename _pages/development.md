---
title: "Development"
layout: single
permalink: /changelog

sidebar:
  nav: "side_nav_dev"
        
                            
---


### Source code
The latest source code can be obtained from <a href="https://www.github.com/LIISim/LIISim3" target="_blank">GitHub</a>. 
Please see the developer's guide (Downloads) for further instructions on compiling the source code and required libraries.



### Changelog
      
Changes and bugfixes for the current LIISim version will be shown on this page after release of the software.
If you want to get notifications about updates, please write an email to raphael.mansmann@uni-due.de


#### Version 3.0.6 
                        
***Libraries***
* *Qt framework* updated to 5.10.1
* *Matio Library* updated to 1.5.11
* *zlib* version 1.2.11 added for MATLAB file compression support
                
                                                               
***Features*** 
* Export: MATLAB export reworked, new structure with support of parallel export for 
   unprocessed and processed data, standard deviation, temperature calculator 
   metadata, file compression 
* Plugin:Transfer: new plugin for transfering processed signals from raw to 
   absolute processing chain
                
                
***Bug fixes***
* Fixed scaling problems with high DPI displays (http://doc.qt.io/qt-5/highdpi.html)
* Plugin:Baseline: offset from LIISettings was only applied for first channel
* Plugin:MultiSignalAverage: when plugin is added, 'end signal'-field is now set to the highest signal number
* FitCreator: FitRun is removed when associated MRun is removed
* AnalysisTools - TemperatureFit: fixed crash when selecting a datapoint without a valid temperature signal calculated
* AnalysisTools - TemperatureFit: when 'clear plot' button of FitVisualization plot was pressed, additional legend items in FitResults are added
* AnalysisTools - TemperatureFit: for Fit Results plot, 'Show' combobox items were swapped
* AnalysisTools - ParameterAnalysis: multi-signal average signals are only shown once for temperature traces
* SignalPlot: channel description in plot legend showed 'ch' for temperature signals 
* SignalPlot: standard deviation envelope was displayed even if channel was deactivated
* SignalPlot: channel selection is now preserved while the checkboxes are displayed and other MRuns are selected
* SignalPlot: channel checkboxes label changed to 'T#' when signal type is temperature.


***Other changes***
* ExportDialog: selected export type is now saved/restored across restarts
* FitSettings: revamped due to scaling issues on high DPI displays 
* GeneralSettings: default session file name unified to 'iniSession.xml' 
* GeneralSettings: button added to reset splitter states 
* GuiSettings: added functions to load/save/reset splitter states
* SignalPlot: Channel checkbox bahavior improved: channel checkboxes state is preserved if other MRun is selected and if checkboxes are hidden, all channels are shown again.
* MRunDetails: table layout improved
* SignalManager: changed some status messages, so they are constantly displayed during signal processing
* AnalysisTools - ParameterAnalysis: changed data table resize method, resizing is now possible after table update


## LIISim - Model Development Kit (MDK)

{% include figure image_path="https://raw.githubusercontent.com/LIISim/LIISim-MDK/master/docs/2018-03-26_MDK.png" 
  alt="LIISim-MDK" %}
Additionally to the C++ software, a model development kit (MDK) was written in MATLAB for comparison
and validation of the integrity of the implemented algorithms. For the MDK the same class structure is
used and the functionalities are limited to simulation of temperature traces using the same heat-transfer models and databases as of the C++ version.
The MDK can be used for testing and developing new models before they are integrated in the LIISim framework.<br><br>
<b>Source code:</b> <a href="https://github.com/LIISim/LIISim-MDK" target="_blank">https://github.com/LIISim/LIISim-MDK</a>


### License
LIISim is free software: you can redistribute it and/or modify it under the terms 
of the GNU General Public License as published by the Free Software Foundation, 
either version 3 of the License, or (at your option) any later version.

LIISim is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; 
without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. 
See the [GNU General Public License](http://www.gnu.org/licenses/){:target="_blank"}  for more details.