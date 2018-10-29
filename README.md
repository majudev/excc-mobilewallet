# excc-mobilewallet - EXCC wallet Mobile

A Decred wallet library for mobile devices built from [exccwallet](https://github.com/exccoin/exccwallet)

## Build Dependencies

[Go( >= 1.10 )](http://golang.org/doc/install)  
[Dep](https://github.com/golang/dep/releases)  
[Gomobile](https://github.com/golang/go/wiki/Mobile#tools) (correctly init'd with gomobile init)  

## Build Instructions

To build this libary, Install dependencies with `dep` (`dep ensure`) and run `gomobile bind -target=android` or `gomobile bind -target=ios` for iOS in a mobilewallet repository directory. Mobilewallet library can also be built targeting different architectures of android which can be configured using the `-target` command line argument Ex. `gomobile bind -target=android/arm`, `gomobile bind -target=android/386`...
