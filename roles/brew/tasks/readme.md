#Install homebrew

Install rvm as single user

https://wiki.archlinux.org/title/RVM#Installing_RVM

`curl -L get.rvm.io > rvm-install`

`bash < ./rvm-install`

`source ~/.zshrc`

`rvm install 2.6.8`

Add following to ~/.zshrc

`echo 'export PATH="$HOME/.rvm/rubies/ruby-2.6.8/bin:$PATH"' >> ~/.zshrc`

https://docs.brew.sh/Homebrew-on-Linux

`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

`echo 'eval "$(/home/linuxbrew/.linuxbrew/bin/brew shellenv)"' >> ~/.zshrc`

`eval "$(/home/linuxbrew/.linuxbrew/bin/brew shellenv)"`

`alias vi="vim"`
