# Chrome Cast Receiver App

Using the Google Cast Receiver libray, this single HTML page reads the Chromecast message bus `urn:x-cast:com.my.cast`, gets the URL and navigate to it.

The await format of message is:
```
{
  "url": "https://disney.com",
  "user": "john.doe",
  "password": "secret"
}
```

It supports Basic Authentication.