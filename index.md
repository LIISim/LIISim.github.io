---
layout: splash
author_profile: false                                                                                             
classes:
  - landing

date: 2018-03-26
header:
  overlay_color: "#C0C0C0"
  overlay_filter: "0.5"
  overlay_image: /assets/screenshots/2018-03-26_V3.0.6_SignalProcessing.png
  cta_label: "Learn more"
  cta_url: "/about"
  caption: "Screenshot: LIISim V3.0.6 - Signal Processing"
  
excerpt: "A modular signal processing toolbox for laser-induced incandescence (LII) measurements"

feature_row:
  - image_path: /assets/screenshots/2018-03-26_V3.0.6_SignalProcessing.png
    alt: "Signal Processing Editor"
    title: "Signal Processing"
    excerpt: "The modular signal processing toolbox allows processing of raw signals, 
    absolute signals and temperature traces. Processing steps can be individually 
    set and arranged. Intermediate processing results can be visualized and analyzed with various plot tools.
    <br><br>[Learn more](/about){: .btn .btn--success }"
    url: "/assets/screenshots/2018-03-26_V3.0.6_SignalProcessing.png"
#    btn_label: "Zoom in"
#    btn_class: "btn--primary"


feature_row2:    
  - image_path: /assets/screenshots/2018-03-26_V3.0.6_AToolTemperature.png
    alt: "Analysis Tool: Temperature Fit"
    title: "Analysis Tool: Temperature Fit"
    excerpt: "Visualization of spectral temperature fitting using Planck's law. Temperature traces
    that are calculated in the SignalProcessing module can be analyzed and all fitting iterations can be visualized.
    <br><br>[Learn more](/about){: .btn .btn--success }"    
    url: "/assets/screenshots/2018-03-26_V3.0.6_AToolTemperature.png"
#    btn_label: "Zoom in"
#    btn_class: "btn--primary"

feature_row3:        
  - image_path: /assets/screenshots/2018-03-26_V3.0.6_ParameterAnalysis.png
    title: "Analysis Tool: Parameter Analysis"
    excerpt: "Experimental data can be systematically compared for various parameters
     (i.e., laser fluence, LII peak temperature, PMT gain voltage,...).
     <br><br>[Learn more](/about){: .btn .btn--success }"                                                        
    url: "/assets/screenshots/2018-03-26_V3.0.6_ParameterAnalysis.png"
#    btn_label: "Zoom in"
#    btn_class: "btn--primary"
    
feature_row4:
  - image_path: /assets/screenshots/2018-03-26_V3.0.6_FitCreator.png
    alt: "Fit Creator"
    title: "Fit Creator"
    excerpt: 'Select from a variety of heat transfer models and databases for simulation of LII signal
     traces and comparison with experimental data.
     <br><br>[Learn more](/about){: .btn .btn--success }'                                                                        
    url: "/assets/screenshots/2018-03-26_V3.0.6_FitCreator.png"
#    btn_label: "Zoom in"
#    btn_class: "btn--primary"

# green large "learn more"-button
#[Learn more](/about){: .btn .btn--success .btn--large }
---
                          
**Laser-induced incandescence (LII)** is a non-intrusive method of measuring 
soot particle volume fraction and primary particle sizes in flames.
Not only restricted to flames, this technique is recently used for characterization
 of **car engine exhaust**, **atmospheric black carbon** and **synthetic 
nanoparticles**. These new applications require the same basic signal processing, 
but at the same time individual databases for material (soot or non-soot) and 
gas compositions as well as individual heat transfer models for the 
determination of particle sizes. **LIISim** is a framework for basic signal processing 
and analysis of experimental LII data to help researches across the world to compare their 
experimental data. 
                  
The old LIISim.com web interface (by Max Hofmann) can be found [here](http://web.liisim.com/){:target="_blank"}. 
{: .notice--warning}             
                                      
**LIISim is a project of** <br>
<a href="http://www.uni-due.de/ivg/rf" target="_blank"><img src="/assets/logos/IVG-Reactive-Fluids.png"
alt="Institute for Combustion and Gas Dynamics - Reactive Fluids" style="height:100px"></a>
<a href="http://www.uni-due.de" target="_blank"><img src="/assets/logos/logo_UDE.png"
alt="University of Duisburg-Essen" style="height:100px"></a>
                                                                   
The software is described in the following paper:                                                                   
> R. Mansmann, T. Terheiden, P. Schmidt, J. Menser, T. Dreier, T. Endres and C. Schulz: \"LIISim - A modular signal processing toolbox for laser-induced incandescence measurements\"
> Appl. Phys. B, DOI <a href="https://doi.org/10.1007/s00340-018-6934-9" target="_blank">10.1007/s00340-018-6934-9</a> (2018)                 
                    
<br><br> 
{% include feature_row id="feature_row" type="left" %}

{% include feature_row id="feature_row2" type="right" %}

{% include feature_row id="feature_row3" type="left" %}

{% include feature_row id="feature_row4" type="right" %}                
