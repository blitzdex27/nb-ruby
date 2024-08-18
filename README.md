# nb-ruby

## Install rbenv

```
brew install rbenv
rbenv init
```

Install ruby-build plugin
```
brew install ruby-build
```

Install ruby version
```
# list latest stable versions:
rbenv install -l

# list all local versions:
rbenv install -L

# install a Ruby version:
rbenv install 3.1.2
```

Set ruby version
```
rbenv global 3.1.2   # set the default Ruby version for this machine
# or:
rbenv local 3.1.2    # set the Ruby version for this directory
```

## References

- https://github.com/rbenv/ruby-build#readme
