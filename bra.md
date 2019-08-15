Q: Can not find bra command after installing it for Go.

1. Add below part to _~/.bashrc_

  ```javascript
   export PATH=$PATH:$(go env GOPATH)/bin
  ```

2. Add below part to _~/.bash_profile_

  ```javascript
  if [ -f ~/.bashrc ]; then
      . ~/.bashrc
  fi
  ```
