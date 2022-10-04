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

Create a new `results` folder to hold results. 
~~~
dir.create("./results")
~~~
{: .r}

## Project download

If you want to download your work at the end of the course, connect to your instance through the Terminal app on a Mac or Mobaxterm or PuTTy if you’re using Windows. In any case the user name and password are the same.

user name: eqtl   
password: eqtl2022

You will be assigned your own unique IP address for your instance. This IP address will be in the form XX.XX.XXX.XX, with the Xs replaced by digits.

In the Terminal app, type

`ssh eqtl@yourIPaddress`
`eqtl@yourIPaddress's password: eqtl2022`

{% include links.md %}
