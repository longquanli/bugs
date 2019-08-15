Q: Can not find bra command after installing it for Go.

1. Add

  ```javascript
   export PATH=$PATH:$(go env GOPATH)/bin
  ```
  
  to ~/.bashrc

2. Add

  ```javascript
  if [ -f ~/.bashrc ]; then
      . ~/.bashrc
  fi
  ```
  
  to ~/.bash_profile
