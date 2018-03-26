---
title: "Screenshots"
layout: single
permalink: /screenshots

sidebar:
  nav: "side_nav"
  
feature_row:
  - image_path: /assets/screenshots/2018-03-26_V3.0.6_SignalProcessing.png
    alt: "SignalProcessingEditor"
    title: "SignalProcessing"
    excerpt: "The modular signal processing toolbox allows processing of raw signals, 
    absolute signals and temperature traces. Processing steps can be individually 
    set and arranged. Intermediate processing results can be visualized and analyzed with various plot tools."
    url: "/assets/screenshots/2018-03-26_V3.0.6_SignalProcessing.png"
#    btn_label: "Zoom in"
#    btn_class: "btn--primary"


feature_row2:    
  - image_path: /assets/screenshots/2018-03-26_V3.0.6_AToolTemperature.png
    alt: "placeholder image 2"
    title: "AnalysisTool: Temperature Fit"
    excerpt: "Visualization of spectral temperature fitting using Planck's law. Temperature traces
    that are calculated in the SignalProcessing module can be analyzed and all fitting iterations can be visualized."    
    url: "/assets/screenshots/2018-03-26_V3.0.6_AToolTemperature.png"
#    btn_label: "Zoom in"
#    btn_class: "btn--primary"

feature_row3:        
  - image_path: /assets/screenshots/2018-03-26_V3.0.6_ParameterAnalysis.png
    title: "AnalysisTool: Parameter Analysis"
    excerpt: "Experimental data can be systematically compared for various parameters
     (i.e., laser fluence, LII peak temperature, PMT gain voltage,...)."                                                        
    url: "/assets/screenshots/2018-03-26_V3.0.6_ParameterAnalysis.png"
#    btn_label: "Zoom in"
#    btn_class: "btn--primary"
    
feature_row4:
  - image_path: /assets/screenshots/2018-03-26_V3.0.6_FitCreator.png    
    title: "FitCreator"
    excerpt: 'Select from a variety of heat transfer models and databases for simulation of LII signal
     traces and comparison with experimental data.'                                                                        
    url: "/assets/screenshots/2018-03-26_V3.0.6_FitCreator.png"
#    btn_label: "Zoom in"
#    btn_class: "btn--primary"
    
                     
                                                                                            
#feature_row4:
#  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
#    alt: "placeholder image 2"
#    title: "Placeholder Image Center Aligned"
#    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
#    url: "#test-link"
#    btn_label: "Read More"
#    btn_class: "btn--primary"
    
  
  
---
## Motivation

LIISim is designed to provide transparent and flexible tools, which allow individual 
setting of processing parameters, visualization of intermediate processing steps, and 
comparison of multiple experimental data sets.

Main features:
- Modular choice of user-defined material properties (soot, silicon, germanium,...)
- Comparison of experimental data with different pre-implemented heat-transfer models
- Various analysis tools help visualizing dependencies between experimental data sets (plots, parameter comparison, statistical information)
- Easy-to-use import (TXT/CSV) and export (TXT/CSV/MATLAB) functionalities
- Copy/paste of signals and analysis results into spreadsheet software (MATLAB, Excel, Origin,...)
- Software architecture allows processing and comparison of large data sets (> 4 GB) 

## Screenshots
                                                                                                              
                                                                                                              
{% include feature_row id="feature_row" type="left" %}

{% include feature_row id="feature_row2" type="right" %}

{% include feature_row id="feature_row3" type="left" %}

{% include feature_row id="feature_row4" type="right" %}
