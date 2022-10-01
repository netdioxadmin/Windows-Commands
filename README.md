# Windows-Commands

Some usefull window Commands for Sys Admins 

Display IP Address

``` ipconfig```

Display IP Address and DNS details

``` ipconfig /all ```

To filter out the details 

``` ipconfig /all | findstr DNS ```

To Renew the DHCP IP Address or to get an new IP Address from DHCP server

``` ipconfig /release``` and ``` ipconfig /renew```

To Renew IP address for single Interface

``` ipconfig /release "Wi-Fi" ``` ``` ipconfig /renew ```

To know the DNS Details 

``` ipconfig /displaydns ```

To clip the command output to clipboard

``` ipconfig.exe /displaydns | clip ```

To flush the DNS Resolver Cache

```ipconfig /flushdns```

For NS lookup ( For getting IP and Nameserver Details 

``` nslookup google.com ```

Fors NS lookup up form google dns server

``` nslookup.exe  google.com  8.8.8.8 ```

To check DNS entries ( for TXT entries) 

`` nslookup.exe -type=txt google.com```

To Display MAC Address

``` getmac /v ```
