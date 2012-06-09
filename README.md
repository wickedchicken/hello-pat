hello-pat
=========

This is an [app engine](https://developers.google.com/appengine/) port of the
[pat](https://github.com/bmizerany/pat) 'hello world' example. Pat is the
'[sinatra](http://www.sinatrarb.com/) for [go](http://golang.org/)' written by
one of sinatra's original creators.

To get started, `git clone` this repository to a local directory. Follow the
[instructions](https://developers.google.com/appengine/docs/go/gettingstarted/devenvironment)
to download the app engine SDK for go and set it up in your environment. Finally
cd into the directory and run:

`dev_appserver.py ./`

You may have to run

`go get github.com/bmizerany/pat`

beforehand if you don't have the package installed.

Try the app out by visiting http://localhost:8080/hello/awesome.
