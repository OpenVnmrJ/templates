#Userlib/templates
This repository contains the userlib/templates contributions for VnmrJ
as packaged in VnmrJ 4.2

##NOTES & CAUTIONS
* Many of these contributions were incorporated into the core VnmrJ
software years ago, so may be redundant with core capabilities
* Most of the contributions are obsolete.
* Though many contributions work, there is often a better way of doing
things in the more modern software
* These contributions are not guaranteed to work
* These tools may work on some systems but not others. Many will only
work with certain versions of VnmrJ, VNMR, RHEL, or Solaris.
* Use these tools at your own risk. Some of them, such as pulse sequences,
could potentially damage hardware, and neither Agilent nor UO is
responsible for such damage.
* Though this is the User Library, users' contributions are mixed
with those from Varian and Agilent staff. On Spinsights, similar
Agilent-provided materials like Chempack are available in Toolkit, and
shared materials from users/customers are here in User Library. Agilent
staff still do contribute to the currently active User Library, but,
like all other contributions, those are personal materials that they
have developed and find useful, and they are not officially supported by
Agilent or guaranteed to work.
* The last update to this file was performed on February 1, 2013, and it
will not be updated again.
* This initially should only contain contributions from Agilent and/or
Varian but your contributions are welcome

##Downloading
You may download this repository from GitHub at:
https://github.com/OpenVnmrJ/templates.git

##Updating and adding
- Fork on GitHub
- Do not add your contribution to the master branch
- If updating contribution, checkout the tag of the contribution, update
and commit on the contribution branch
- If adding a new contribution, checkout a new branch with the name of
the contribution, push the new branch to your repository, add and commit
on the new branch
- Tag your update of change with the name of the contribution, followed
by a version, for example, mymacro-v1.1
- Push your branch to your fork; remember to push the tags too
- Make a pull request to the OpenVnmrJ repository

##Contributions

Below is a list of each contribution. To access a contributions, check
out its tag

##stars
>"templates/stars" contains a set of panels for the use of STARS
in VnmrJ 1.1. The original interface for VNMR (the contents of
"templates/stars61b.tar.Z") is also present with a few bug fixes. The
VnmrJ panels are contained in a fourth tab "ANALYZE". They are named
"STARSsetup" and "STARSdata". Also included is a macro "rtcmx" for
loading Spinsight data along with the conversion program "convertcmx".

---
To install the contribution, checkout the tag stars-v1.0:

    git checkout stars-v1.0

then read stars.README

Usually use extract to install the contribution:

    extract templates/stars

