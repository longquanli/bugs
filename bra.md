Q: Can not find bra command after installing it for Go.

1. Add below part to ~/.bashrc

  ```javascript
   export PATH=$PATH:$(go env GOPATH)/bin
  ```

2. Add below part to ~/.bash_profile

  ```javascript
  if [ -f ~/.bashrc ]; then
      . ~/.bashrc
  fi
  ```
