# stars
 stars - "templates/stars" contains a set of panels for the use of STARS
 in VnmrJ 1.1. The original interface for VNMR (the contents of
 "templates/stars61b.tar.Z") is also present with a few bug fixes. The
 VnmrJ panels are contained in a fourth tab "ANALYZE". They are named
 "STARSsetup" and "STARSdata". Also included is a macro "rtcmx" for
 loading Spinsight data along with the conversion program "convertcmx".

 Copyright 2016 University of Oregon

 Licensed under the Apache License, Version 2.0 (the "License");
 you may not use this file except in compliance with the License.
 You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

 Unless required by applicable law or agreed to in writing, software
 distributed under the License is distributed on an "AS IS" BASIS,
 WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 See the License for the specific language governing permissions and
 limitations under the License.

                                SUBMISSION FORM

Your name:         Dave Rice, Agilent

Date submitted:    2002-11-30

File name:         stars.tar.Z
Directory:         templates
Description:       "templates/stars" contains a set of panels for the use of
                   STARS in VnmrJ 1.1. The original interface for VNMR (the
                   contents of "templates/stars61b.tar.Z") is also present
                   with a few bug fixes. The VnmrJ panels are contained in a
                   fourth tab "ANALYZE". They are named "STARSsetup" and
                   "STARSdata". Also included is a macro "rtcmx" for loading
                   Spinsight data along with the conversion program
                   "convertcmx".

                   Known problems: The load button which formerly loaded
                   Spinsight datasets has been disabled in VnmrJ. The Locator
                   does not import Spinsight datasets at present. Users should
                   use the command
                        rtcmx('filename')
                   on the command line to load Spinsight data.

Existing VnmrJ / VNMR files which are superseded or
otherwise affected by this submission:  bin/convertcmx, maclib/rtcmx,
                   templates/dg/default, templates/layout/default,
                   templates/vnmrj/interface, templates/vnmrj/protocols


**This software has not been tested on OpenVnmrJ. Use at your own risk.**

To install this user contribution:  
Download the repository from GitHub and checkout the tag of the contribution you want.
Typically tags end in the version (e.g. -v1.0)

     git clone https://github.com/OpenVnmrJ/templates  
     cd templates  
     git checkout stars-v1.0


You may also download the archive directly from github at

    https://github.com/OpenVnmrJ/maclib/archive/stars-v1.0.zip

Read stars.README for installation instructions.

In most cases, move the contribution to /vnmr/userlib/templates 
then use extract to install the contribution:  

    extract templates/stars