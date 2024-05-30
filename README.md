# some basic code for the hack the box challenges

```bash
curl 'http://94.237.62.221:54896/search.php?search=flag' -H 'Authorization: Basic YWRtaW46YWRtaW4='~


curl -X POST -d '{"search":"flag"}' -b 'PHPSESSID=nhi8b45vnkipqffnhggfo8e0ea' 'http://94.237.62.221:52695/search.php'  -H 'Content-Type: application/json'

```