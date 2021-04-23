<b>Example: List devices that are not covered or having an expiring soon contract status from Intersight</b>

Pre-reqs:

-Intersight API Keys

-Python 3.x

Usage:

Modify API key in contractstatus.py to your API key

Modify SecretKey.txt to your API private key

Example Output:

>#python contractstatus.py

>Serial #      Status        Expiration Date        Model         Name

>---------------------------------------------------------------------------------------

>SALXXXXXXXX , Not Covered, 0001-01-01T00:00:00Z , UCS-FI-6332, PRODOMAIN1 FI-A

>SALXXXXXXXY , Not Covered, 0001-01-01T00:00:00Z , UCS-FI-6332, PRODOMAIN1 FI-B

>SSIYYYYYYYY , Not Covered, 0001-01-01T00:00:00Z , UCS-FI-6248UP, LABDOMAIN1 FI-A

>FCHXXXXXXXX , Not Covered, 0001-01-01T00:00:00Z , UCSB-B200-M3, LABDOMAIN1-1-4

>WZPXXXXXXXX , Expiring Soon, 2021-04-30T00:00:00Z , UCSC-C240-M5SX, LABDOMAIN1-8

>FCHXXXXXXXX , Not Covered, 0001-01-01T00:00:00Z , UCSB-B200-M3, LABDOMAIN1-1-3
