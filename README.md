# homebrew-core

For when you need an older-than-latest version of a brew package.

Find the version of the package you want:

https://github.com/Homebrew/homebrew-core/tree/master/Formula

Download it (make sure the filename matches the package name)

```sh
curl -o openjdk@11.rb https://raw.githubusercontent.com/Homebrew/homebrew-core/62b8cab92b253da54907a764b701225a533a7fa7/Formula/openjdk%4011.rb
```

Upload to the formula directory

Install:

```sh
brew tap richardjbaker/core
brew install richardjbaker/homebrew-core/openjdk@11
```
