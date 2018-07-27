# thycotic

How to create Thycotic Secret Server certificate on Windows for lab enviroment

First edit 'cert-req.txt' file for customization

Command:

certreq -new "cert-req.txt"

On Windows Client Machine:

Run "certmgr.msc"

Import certificate file to Trusted Root Certification Authorities and Enterprise Trust Folders

