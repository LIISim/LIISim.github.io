---
title: "Downloads"
layout: single
permalink: /downloads

sidebar:
  nav: "side_nav"
---


| System requirements |
| ------------------------------------------- | ----------------------------------------------------- |
| Operating system                            | Windows 7/8/10 |
| Memory	| 8 GB RAM |
| Hard drive | 500 MB free hard disk space |
| Screen resolution | 1920 x 1080 or higher (scaling problems can occur for small notebook displays with high resolution) |
| Software | Microsoft Visual C++ 2013 Redistributable (<a href="https://www.microsoft.com/en-us/download/details.aspx?id=40784" target="_blank">download here</a>) |



We are currently in BETA development phase, release is scheduled for Spring 2018. Please feel free to request a BETA release for testing purposes.
{: .notice--info}

Pre-compiled binaries are available for Windows 7/8/10 platforms (32bit and 64bit). 

| Platform | Version | File |
| ------------------------------------------- | ----------------------------------------------------- |
| Windows 7/8/10 (x64) | 3.0.6 | [Request BETA version](mailto:raphael.mansmann@uni-due.de?subject=LIISim%20BETA%20request%20&body=Hi%20Raphael%2C%0A%0Aplease%20send%20me%20a%20BETA%20version%20of%20LIISim%20for%20testing.){: .btn .btn--info } |
| Windows 7/8/10 (x32) | 3.0.6 | [not yet available](#){: .btn .btn--info }|



{{site.github}}

{% for repository in site.github.public_repositories %}
  * [{{ repository.name }}]({{ repository.html_url }})
  * {{repository.releases_url}}  
{% endfor %}


## Documentation

| Document | Version | File |
| ------------------------------------------- | ----------------------------------------------------- |
| User manual | 0.0.1 (26.03.2018) | [on request](#){: .btn .btn--primary } |
| Developer's guide | 0.0.1 (26.03.2018) | [not yet available](#){: .btn .btn--primary } |


## Source code
The latest source code can be obtained from [GitHub](https://www.github.com/LIISim/LIISim3). Please see the developer's guide for further instructions on compiling the source code and required libraries.




## License
LIISim is free software: you can redistribute it and/or modify it under the terms 
of the GNU General Public License as published by the Free Software Foundation, 
either version 3 of the License, or (at your option) any later version.

LIISim is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; 
without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. 
See the [GNU General Public License](http://www.gnu.org/licenses/){:target="_blank"}  for more details.