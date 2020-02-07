# mac setups

* CLT xcode: 

  ```
  xcode-select --install
  ```

  

* homebrew: 

  ```
  mkdir homebrew && curl -L https://github.com/Homebrew/brew/tarball/master | tar xz --strip 1 -C homebrew
  ```

  

* ZSH:

  * prezto: https://github.com/sorin-ionescu/prezto 
  * task warrior: 

  ```
  brew install task
  ```

  * neofetch: 

  ```
  git clone https://github.com/dylanaraps/neofetch.git
  ```

  * tmux: 

  ```
  brew install tmux
  ```

  * musikcube: 
    
    ```
    brew tap clangen/musikcube 
    brew install musikcube
    ```

* docker animation: 
  
  ```
  defaults write com.apple.dock autohide-delay -int 0
  defaults write com.apple.dock autohide-time-modifier -float 0.4
  killall Dock
  ```
  
  
  
  ```
  defaults write com.apple.Finder AppleShowAllFiles True/False
  killall Finder
  ```
  
  
