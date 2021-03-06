# gogit - A tool to keep committed to open source while at work
[![Build Status](https://travis-ci.org/ru-lai/gogit.svg?branch=master)](https://travis-ci.org/ru-lai/gogit)

> Stores git profile credentials; can create directories with specific git credentials to commit to any account from anywhere!

## Install
1. [Install Golang](https://golang.org/doc/install)
2. [Set up your GOPATH and GOBIN variables](https://github.com/golang/go/wiki/SettingGOPATH)
3. [Add your goDir/bin to your path](https://codevenue.wordpress.com/2015/07/26/golang-setting-up-go-development-environment/)
4. Install the package
```
$ go get github.com/ru-lai/gogit
```

5. change your dir to src/github.com/ru-lai/gogit 
```
$ cd goDir/src/github.com/ru-lai/gogit
```
and
```
$ go install
```

You should now be able to run the gogit command from the command line.

## Note
If your GOBIN is set up incorrectly, or if the GOPATH/bin directory is not included in the path of your shell, you will not have access to golang built repositories.


## Left TODO
Todos are in the Todo.md file

## License

MIT © Tyler Boright
