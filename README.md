# python-scraping

####Chapter 01
Before you run file `Chapter1\2-beautifulSoup.py`, you must install [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/) by typing command:
```
pip3 install beautifulsoup4
```

####Chapter 03
To avoid error
```
raceback (most recent call last):
  File "/Library/Frameworks/Python.framework/Versions/3.6/lib/python3.6/urllib/request.py", line 1318, in do_open
    encode_chunked=req.has_header('Transfer-encoding'))
  File "/Library/Frameworks/Python.framework/Versions/3.6/lib/python3.6/http/client.py", line 1239, in request
    self._send_request(method, url, body, headers, encode_chunked)
  File "/Library/Frameworks/Python.framework/Versions/3.6/lib/python3.6/http/client.py", line 1285, in _send_request
    self.endheaders(body, encode_chunked=encode_chunked)
  File "/Library/Frameworks/Python.framework/Versions/3.6/lib/python3.6/http/client.py", line 1234, in endheaders
    self._send_output(message_body, encode_chunked=encode_chunked)
  File "/Library/Frameworks/Python.framework/Versions/3.6/lib/python3.6/http/client.py", line 1026, in _send_output
    self.send(msg)
  File "/Library/Frameworks/Python.framework/Versions/3.6/lib/python3.6/http/client.py", line 964, in send
    self.connect()
  File "/Library/Frameworks/Python.framework/Versions/3.6/lib/python3.6/http/client.py", line 1400, in connect
    server_hostname=server_hostname)
  File "/Library/Frameworks/Python.framework/Versions/3.6/lib/python3.6/ssl.py", line 401, in wrap_socket
    _context=self, _session=session)
  File "/Library/Frameworks/Python.framework/Versions/3.6/lib/python3.6/ssl.py", line 808, in __init__
    self.do_handshake()
  File "/Library/Frameworks/Python.framework/Versions/3.6/lib/python3.6/ssl.py", line 1061, in do_handshake
    self._sslobj.do_handshake()
  File "/Library/Frameworks/Python.framework/Versions/3.6/lib/python3.6/ssl.py", line 683, in do_handshake
    self._sslobj.do_handshake()
ssl.SSLError: [SSL: CERTIFICATE_VERIFY_FAILED] certificate verify failed (_ssl.c:749)
```
In macOS, go to `/Applications/Python 3.6`, to execute file `Install Certificates.command`, type command
```
./Install\ Certificates.command
```
