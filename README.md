# dev-machine
How I like to set up my computer for software development

##Mac OS Applications

[Sublime Text 3] (https://www.sublimetext.com/3)

[iTerm 2] (https://www.iterm2.com/) - Set preferences: Profiles / Default / Colors / Color Presets... Pastel (Dark Background)

[XCode] (https://itunes.apple.com/us/app/xcode/id497799835?ls=1&mt=12)

##Command Line Utilities

Homebrew `$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`

Node `brew install node`

Python `$ brew install python libjpeg`
`$ export PATH=/usr/local/bin:/usr/local/share/python:$PATH`

Ruby `$ brew install ruby`
`$ gem install nokogiri premailer`

Less `$ npm install less less-plugin-clean-css -g`

Tmux `$ brew install tmux`

n `$ npm install -g n`

##Config Files

###Bash Profile

`$ cd ~` `$ touch .bash_profile`

Copy raw text from this repo at: `config/dot-bash_profile`

`$ nano .bash_profile` 

`Command-V` `Ctrl-x` `Enter` 

`$ source .bash_profile`
