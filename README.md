# Publish RDS using AAD AP(Azure AD application proxy)

The instructions below apply to the scenario where :

>RD gateway	- Not published to public network yet ( doesn't have public IP )

>External url of RD gateway - you don’t have ssl cert issued from public CA, you will use the default external url generated by AAD AP by default

>Internal url of RD gateway	- You don’t want it to be exposed to public network , external url is different from the internal one


Server required in the deployment :

>Domain controller	* 1 (Windows server 2016+)

>RD Gateway Server * 1 (Windows server 2016+)

>RD session host + broker + licensing on a single server	* 1 (Windows server 2016+)
