# dev-cookbook
* JAMStack Repo for netlify
* JAM (Javascript, APIs and Markup)
* JAMStack is a javascript architecture 

## Install 
* https://jekyllrb.com/docs/installation/ubuntu/
```
sudo apt-get install ruby-full build-essential zlib1g-dev
``` 
* _set up a gem installation directory for your user account_ 
* reload .profile with: `source .profile`
```
export GEM_HOME="$HOME/gems"
export PATH="$HOME/gems/bin:$PATH"
```
* now install jekyll. with the settings above, jekyll will be located in `~/gems/bin/jekyll`
```
gem install jekyll bundler
```

## Uninstall
```
sudo apt remove ruby
sudo apt remove ruby-full
sudo gem uninstall jekyll bundler
rm -rf ~/gems/
```

## Jekyll 
* follow instructions on: https://www.netlify.com/blog/2020/04/02/a-step-by-step-guide-jekyll-4.0-on-netlify/
``` 
sudo gem install jekyll
jekyll new project
```
