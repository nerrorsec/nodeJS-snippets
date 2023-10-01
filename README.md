## Originally named: nodeJS-snippets, This repository was a part of OWASP KTM 0x02 CTF.
## You can find the writeup [here](https://web.archive.org/web/20230709071759/https://veshraj.medium.com/heres-how-we-exploited-the-github-workflow-a-walkthrough-of-owasp-kathmandu-ctf-6e3063a0c8f).


## Collection of useful NodeJS code snippets.
Example:
```nodejs
var http = require('http');

http.createServer(function (req, res) {
  res.writeHead(200, {'Content-Type': 'text/plain'});
  res.end('Hello World!');
}).listen(8080);
```

`PS: Code snippets will be added soon.`

