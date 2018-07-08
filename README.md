# IguanaTexMac

## Install

```bash
# install AppleScript
mkdir -p '~/Library/Application Scripts/com.microsoft.Powerpoint'
cp ./IguanaTex.scpt '~/Library/Application Scripts/com.microsoft.Powerpoint/IguanaTex.scpt'

# install IguanaTexHelper
sudo mkdir -p '/Library/Application Support/Microsoft/Office365/User Content.localized/Add-Ins.localized'
sudo cp ./libIguanaTexHelper.dylib '/Library/Application Support/Microsoft/Office365/User Content.localized/Add-Ins.localized/libIguanaTexHelper.dylib'
```
start PowerPoint, Tools > PowerPoint Add-ins... > '+' , select IguanaTexMac.ppam


Original README
===============

# IguanaTex

(C) Jonathan Le Roux and Zvika Ben-Haim
Website: http://www.jonathanleroux.org/software/iguanatex/

IguanaTex is a PowerPoint add-in which allows you to insert LaTeX equations into your PowerPoint presentation on Windows. It is distributed completely for free, along with its source code.

This repository hosts the source code in a form that can be easily tracked, shared and discussed.

For those interested in using IguanaTex, please download the add-in as a .ppam or .pptm file from http://www.jonathanleroux.org/software/iguanatex/.