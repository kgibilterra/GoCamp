# GoCampNYC Schedule

## Morning Track: Learning Go Fundamentals
###*Paul Burt, EBay*
_@thatmightbepaul_ on Twitter and _pgburt_ on GitHub

The workshop will be focused towards folks with little or no programming experience. They will need a Mac, Linux machine, or a Windows machine built within the last 3 years. For Windows users, we'll help them install an Ubuntu VM as part of the first session.

###*First session* 
is all about the command line, how to pass commands arguments, and how to find help. We'll make sure everyone is setup to do some Go, here.

###*Second session* 
is a little bit of C (for history), and then a basic app in Go. We'll cover data types, pointers, importing, and functions. It'll end with folks downloading, compiling, and running a Go program from Github.

###*Third session* 
is about some of the rest of the programming essentials. We'll talk about If-Thens, Loops, and then finish by building a simple web app.

###*Fourth session
is about tackling a challenging problem. I'll ask anyone if they know how to calculate Pi (I expect they'll say No), and then we'll work together as a group to figure it out in Go. The goal is to show them that first, 99% of programming doesn't involve any Math. Up until this point it's all been just how to 'organize' things. And second, when they do run into a Math problem (like calculating Pi), it's actually not that hard if you just ask for help.

## Lunch

Outside in East River Patio lookout

# Afternoon

##"How a gopher juggles dependencies: vendoring" (Beginner)
###*Filippo Valsorda, Cloudflare*
_@filosottile_ on Twitter & GitHub

We'll look at how Go's approach to dependencies is different from other
languages, and what tools are available for it.

Vendoring is here to stay, but the etiquette is not yet consolidated.
For example we are starting to agree that libraries should never vendor
other libraries, because types would then conflict with the ones the
consumer can access.

##"Calling Go from other languages" (Intermediate+)
###*Filippo Valsorda, Cloudflare*
_@filosottile_ on Twitter & Github

One of my most popular blog posts is "Building Python modules with Go
1.5". It was mostly an experiment to play with the new option to build C
libraries. The post imported the Python API directly to prove you can go
end-to-end. However, building a pure C library and then using FFI you
can elegantly import Go code from most other languages, including
Python, Ruby and Javascript We'll have a look at how and what are the
pitfalls.

## Valor, An open platform for Writing
###*Faraz Fazli
_Faraz Fazli is currently 19 and has been coding since age 9. He has previously spoken at the UN for several other Open Source camps (DevOps Camp, NextGen Camp, Android Camp), and given talks at Priceline, DigitalOcean, eBay, and various tech companies throughout NYC. Passionate about bringing developers together, he organizes the a monthly tech meetup in NYC which has over 900 members._

##Expvarmon -TermUI based monitor for Go apps using expvars (/debug/vars). Quickest way to monitor your Go app(s)
###*Ivan Daniluk*
_@idanyliuk_ on Twitter, divan on Github

##How to write a Go tool. 
###Fatih Arslan
_@fatih_ on Twitter & Github

Go tools are very powerful and yet simple to use. How are Go tools created? In this talk we'll going to answer this question by showing the various Go parser family packages (`go/token`, `go/scanner`, `go/parser`, etc...) and how to use them to implement a new Go tool from scratch.
