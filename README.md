## 環境構築

```
$ curl -L git.io/nodebrew | perl - setup
$ echo 'export PATH=$HOME/.nodebrew/current/bin:$PATH' >> ~/.bash_profile
$ source ~/.bash_profile
$ nodebrew install v13.12.0
$ nodebrew use v13.12.0

$ npm install --global install yarn
$ echo 'export PATH="$PATH:$(yarn global bin)"' >> ~/.bash_profile
$ source ~/.bash_profile

$ git clone https://github.com/YuichirouSeitoku/YoutubeMyBest.git
$ yarn
$ yarn run dev
```
