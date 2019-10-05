# vimgostarter 

```
cd ~

git clone https://github.com/truedeity/vimgostarter.git
rm -rf vimgostarter/.git
mv vimgostarter/{.,}* .

chmod +x install.sh
sudo ./install.sh -go https://dl.google.com/go/go1.13.1.linux-amd64.tar.gz
sudo ./install.sh -vim
cp vice.vim ~/.vim/colors/vice.vim
cd ~
rm -rf vimgostarter
```

