---
title: Setup
---
## Software installation

Windows

Ask the JAX IT Service Desk to download and install MobaXterm or PuTTY.

macOS

The default shell in all versions of macOS is Bash, so no need to install anything. You access Bash from the Terminal (found in /Applications/Utilities).
 
## Package installation

1. Connect to your RStudio instance, a URL in the form http://XX.XX.XXX.XXX:XXXX. 

2. Install `AnnotationHub` and `rtracklayer` by copying and pasting 
the following code in the R console.

~~~
BiocManager::install("AnnotationHub")
BiocManager::install("rtracklayer")
~~~
{: .r}


## Project organization

1. Create a new `results` folder to hold results. 
~~~
dir.create("./results")
~~~
{: .r}



{% include links.md %}
