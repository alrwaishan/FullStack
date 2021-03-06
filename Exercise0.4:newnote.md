#title 0.4: new note

browser->server: HTTP POST https://studies.cs.helsinki.fi/exampleapp/new_note

server-->browser: Status Code 302

browser->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/notes

server-->browser: HTML-code 

browser->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/main.css

server-->browser: main.css

browser->server: HTTP GET https://studies.cs.helsinki.fi/exampleapp/main.js

server-->browser: main.js

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

#Link to Image:
https://www.websequencediagrams.com/cgi-bin/cdraw?lz=dGl0bGUgMC40OiBuZXcgbm90ZQoKYnJvd3Nlci0-c2VydmVyOiBIVFRQIFBPU1QgaHR0cHM6Ly9zdHVkaWVzLmNzLmhlbHNpbmtpLmZpL2V4YW1wbGVhcHAvbmV3XwBKBQA_Bi0tPgBQBzogU3RhdHVzIENvZGUgMzAyAFkXR0UAQi1vdGVzAFkTSFRNTC1jb2RlIAAiRW1haW4uY3MAVhQAEgkAH0lqAE4ZanMKCm5vdGUgb3ZlciAAglEIAIMxCCBzdGFydHMgZXhlY3V0aW5nIGpzAIF_BQp0aGF0IHJlcXVlc3RzIEpTT04gZGF0YSBmcm9tIACDaAYgCmVuZACDbB0AgmsuZGF0YS5qc29uAIN2E1t7Y29udGVudDogIm0gLiAiLCBkYXRlOiAiMjAyMS0wMy0wNVQxMDo1OTowMS4zMzlaIn0s4oCmXQCBYR0AgXEGZXMgdGhlIGV2ZW50IGhhbmRsZXIAgXgIbmRlcnMAhWgFcyB0byBkaXNwbGF5AIFvCg&s=default
![0 4_ new note (1)](https://user-images.githubusercontent.com/76932317/110193299-1e2ea900-7e2b-11eb-8985-9e38b1d52d01.png)

