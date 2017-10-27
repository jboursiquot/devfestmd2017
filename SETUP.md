# Setting up

You're here because you don't have a `$GOPATH` set up. Check it:

```
$ go env
...
GOPATH=
...
```

If there's nothing set, proceed.

## Set your `$GOPATH`

### Linix or Mac

```
$ mkdir $HOME/go
$ export GOPATH=$HOME/go
```

> Feel free to export this variable however your shell environment sets variables on start so you don't have to keep exporting it each time you open a new terminal window.

### Windows:
1. From a command prompt: `mdkir "%USERPROFILE%\go`
2. Go to `Control Panel` > `System` > `Advanced` > `Environment Variables`
3. Add a new `User` variable with name `GOPATH` and value `%USERPROFILE%\go`
4. You may need to restart your computer `¯\_(ツ)_/¯`

## `src`, `pkg`, `bin`

Now create three subdirectories in your $GOPATH:

* `src` - where source code goes
* `pkg` - where built package archives
* `bin` - where executables you `go install` or `go get` go

## Put your `bin` on you `$PATH`

### Linux or Mac

Lastly, a nice convenience is to ensure that `$GOPATH/bin` in on your `PATH`.

```
$ export PATH=$PATH:$GOPATH/bin
```

> Feel free to export this variable however your shell environment sets variables on start so you don't have to keep exporting it each time you open a new terminal window.

### Windows

1. Go to `Control Panel` > `System` > `Advanced` > `Environment Variables`
2. Edit "Path" under `System` variables and add `;C:\go\bin`
3. You may need to restart your computer `¯\_(ツ)_/¯`
