#Install homebrew
Install rvm as single user
https://www.digitalocean.com/community/tutorials/how-to-install-ruby-on-rails-on-arch-linux-with-rvm
rvm install 2.6.8
curl -L get.rvm.io > rvm-install
bash < ./rvm-install
rvm install 2.6.8

/home/jeffersons/.rvm/rubies/ruby-2.6.8/bin

https://docs.brew.sh/Homebrew-on-Linux
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
echo 'eval "$(/home/linuxbrew/.linuxbrew/bin/brew shellenv)"' >> ~/.zshrc
eval "$(/home/linuxbrew/.linuxbrew/bin/brew shellenv)"


sudo visudo
$USER ALL=(ALL) NOPASSWD: ALL

export PATH="$HOME/.rvm/rubies/ruby-2.6.8:$PATH"
eval "$(/home/linuxbrew/.linuxbrew/bin/brew shellenv)"
alias vi="vim"
