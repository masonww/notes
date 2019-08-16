# notes

Curl
  -A/--user-agent <agent string>/n
  -H/--header <header>
  -k/--insecure #for insecure ssl
  -o/--output <file>
  -x/--proxy <proxyhost[:port]>
  -X #explicit method 
  -d #data to send
  #example curl <URL> -H "content-type: application/json" -d "{ \"woof\": \"bark\"}" #Curl post send json
  #example curl -u $username:$password http://repo.dennyzhang.com/README.txt #upload with creds
  
  
  
