# Devfest MD 2017 - Go Code Lab

## Welcome!

In this code lab, we're going to learn enough Go to create command line applications and HTTP servers/clients.

What you'll need for this lab:

1. a terminal
2. Go installed
3. a text editor, preferably with Go support
4. a GitHub account
5. a willingness to learn the Go way

What you'll learn:

1. [Building command line applications](https://github.com/jboursiquot/go-cli-workshop)
2. [Building HTTP servers](https://github.com/jboursiquot/go-web-app-workshop)

## Why Go?

Go was created to...

## Test your installation

Let's begin by ensuring that you have Go installed properly. Open a terminal...

```
$ go version
go version go1.8 darwin/amd64
```

You should have at least version 1.8 installed, you might have 1.9 if you downloaded it or upgraded recently. If you do not have Go installed, head to the [https://golang.org/dl/](https://golang.org/dl/).

## Your workspace, the `$GOPATH`

The `$GOPATH` is your workspace. It's where the go toolchain looks for source code (yours and third-party code you download), keeps compilation artifacts, and stores executables you `go install` or `go get`.

### Check
On your terminal, check if you have a `$GOPATH` environment variable defined:

```
$ go env
...
GOPATH="/Users/jboursiquot/dev/go"
..
```

You should see a list of variables, among them should be the `GOPATH`. Got it? Good, let's proceed. Don't got it? Go to SETUP.md for more instructions.

