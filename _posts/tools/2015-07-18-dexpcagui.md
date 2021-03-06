---
layout: page
subheadline: "GUI"
title:  "DexpCAgui - DeXPeriX Cellular Automata"
teaser: "This application is intended for experienced users who have already created a pseudorandom number generators (PRNG). The output is a PRNG on a cellular automata."
categories: tools
tags:
    - tools
    - gui
    - crossplatform
    - qt
    - pseudorandom
header:
    image_fullwidth: "head/lhca.png"
image:
   thumb: "thumb/dexpcagui.png"
#   title: "other/cagui/info.png"
buttons:
    - caption: "Download DexpCAgui binary"
      url: "{{ site.release_url }}v.2015-07-18/DexpCAgui.zip"
      class: "info"
    - caption: "DexpCAgui for Android"
      url: "{{ site.release_url }}v.2015-07-18/DexpCAandroid-debug.apk"
      class: success
comments: true
---

![DexpCAgui - Info]({{ site.urlimg }}other/cagui/info.png "DexpCAgui - Info")

> Cellular automata provide simple discrete deterministic mathematical models for physical, biological and computational systems. An "elementary" cellular automaton consists of a sequence of sites carrying values 0 or 1 arranged on a line. The value at each site evolves deterministically with time according to a set of definite rules involving the values of its nearest neighbours. 


"Vector" tab indicates a mathematical basis of cellular automata, where the calculation process is shown. There you can see the auxiliary matrix, rules vector conversion, verification of the polynomial for irreducibility.

![DexpCAgui - Vector]({{ site.urlimg }}other/cagui/vector.png "DexpCAgui - Vector")


"Heur.Brute" tab will help you find the correct rules vectors, such that generators can produce the maximum length sequence.

![DexpCAgui - Heur.Brute]({{ site.urlimg }}other/cagui/brute.png "DexpCAgui - Heur.Brute")


"Modelling" tab can simulate the functioning of a cellular automata.

![DexpCAgui - Modelling]({{ site.urlimg }}other/cagui/model.png "DexpCAgui - Modelling")


You can generate VHDL or C/C++ code of cellular automata on the "Schematic" tab. Also you can see general view of your automata.

![DexpCAgui - Schematic]({{ site.urlimg }}other/cagui/sch.png "DexpCAgui - Schematic")


The utility has an Android version:

![DexpCAgui - Android]({{ site.urlimg }}other/cagui/android.jpg "DexpCAgui - Android")


{% include buttons %}


## Other Tools
{: .t60 }
{% include list-posts tag='tools' %}
