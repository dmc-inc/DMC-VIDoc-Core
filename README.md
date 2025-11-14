# DMC CLI Confluence Documentation

This repository contains the code to generate Confluence Documentation based off of LabVIEW source files.

This uses a g-cli call in the form:

g-cli (optional)--lv-ver [LV_Year] (optional)--timeout [ms Timeout] "DMC CLI Confluence Documentation" -- [arguments]

This must be called from the working directory you want to analyze.

-------required arguments-------
-settings <absolute or relative to working directory relative path to Doc Settings file. defaults to Default.json included with app>
-pageid <Page ID for the top level Confluence Page that documentation will be generated under>

-------optional arguments-------
-git <Flag to include Git History in the documentation>
-gittype <Indicates which Git repo type the Git History would check. Defaults to GitLab, also allows GitHub and BitBucket>
-source <comma seperated string of all relative file paths within working directory to include. Recursive search. Defaults to whole working directory>
-c-settings <Flag to indicate use the Confluence connection settings from within the Doc Settings File>
-c-ini <Flag to indicate using the Login INI file for Confluence connections>
-c-dc <Indicates Confluence type. If flag present then uses Data Center, otherwise uses Cloud>
-url <Confluence URL>
-email <Confluence Email>
-token <Confluence Access Token>
-help <Returns this help information>

# [Wiki Homepage](../../wikis/Home)

# Author(s), Contributors
* Contributor 1
* Contributor 2


# License
All software in this repository is licensed under the license found in [..\Build\License\](../master/Build/License/). 


---

This project was created 2023-10-24 12:44:06.304161 by copying https://git.dmcinfo.com/DMC/labview/dmc-templates/gitlab-template.

---

This project was created 2025-09-11 12:30:01.140842 by copying https://git.dmcinfo.com/DMC/labview/dmc-templates/DMC-Lib-Project-Template.