## HTML POLL
	This repository has the front end to anwser poll

## Install

- First, you need to install [api-poll](https://github.com/matt987/api-poll2)

- Clone repository
```
	git clone git@github.com:matt987/matt987.github.io.git
```

- Use a http webserver like SimpleHTTPServer from python 2.7
```
	cd ./matt987.github.io.git
	python2.7 -m SimpleHTTPServer
```

- Go to browser
```
	localhost:8000
```

If you install api-poll2 like tutorial, you don´t need to do anymore, but if you need to change the url when you up your api-poll2 server, just change in index.html the config var with yout URL
```
  var config={
    url:"[your_url_here]/",
    poll_id:1
  };
```


