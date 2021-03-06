#title 0.5: Single page app

browser-->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/spa

server-->browser: HTML-code

browser-->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/main.css

server-->browser: main.css

browser->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/spa.js

server-->browser: spa.js

note over browser:
browser starts executing js-code
that requests JSON data from server 
end note

browser->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/data.json

server-->browser: [{content: "m . ", date: "2021-03-05T10:59:01.339Z"},…]

note over browser:
browser executes the event handler
that renders notes to display
end note

#image link: https://www.websequencediagrams.com/cgi-bin/cdraw?lz=dGl0bGUgMC41OiBTaW5nbGUgcGFnZSBhcHAKCmJyb3dzZXItLT5zZXJ2ZXI6IEhUVFAgR0VUIGh0dHBzOi8vc3R1ZGllcy5jcy5oZWxzaW5raS5maS9leGFtcGxlYXBwL3NwYQoAOQYtLT4ASwc6IEhUTUwtY29kZQAfR21haW4uY3NzAFgTABIJAIFHCQCBED8uagBTFAASBwpub3RlIG92ZXIgAIFlCACCQAggc3RhcnRzIGV4ZWN1dGluZyBqcwCBfgZ0aGF0IHJlcXVlc3RzIEpTT04gZGF0YSBmcm9tIACCdgYgCmVuZCBub3QAgicLAIJbPGRhdGEuanNvbgCDChNbe2NvbnRlbnQ6ICJtIC4gIiwgZGF0ZTogIjIwMjEtMDMtMDVUMTA6NTk6MDEuMzM5WiJ9LOKApl0AgWEdAIFxBmVzIHRoZSBldmVudCBoYW5kbGVyAIF4CG5kZXJzAIFfBXMgdG8gZGlzcGxheQCBbgsK&s=default

![0 5_ Single page app](https://user-images.githubusercontent.com/76932317/110193499-23d8be80-7e2c-11eb-82a3-762b279f6920.png)


