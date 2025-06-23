# HTB CBBH

## WEB REQUESTS

### curl options
`curl -k https://inlanefreight.com`  
`-k` or `--insecure`: Disable SSL/TLS certificate verification  
`-v`: Verbose  
`-vvv`: More verbose  
`-I`: Sends a HEAD request to get and only display reponse headers   
`-i`: Sends any request we specify and prints the headers as well  
`-H`: Set request headers  
`-A`: Set Userger Agent  
`-X`: Specifies the HTTP method (e.g., GET, POST, PUT, DELETE) use with `-d "username=admin&password=admin"`   
`-b` or `--cookie`: Sends cookies (`name=value;another=val`) `-b 'PHPSESSID=c1nsa6op7vtk7kdis7bcnbadf1'` can also be sent as a header `-H 'Cookie: PHPSESSID=c1nsa6op7vtk7kdis7bcnbadf1'`  

