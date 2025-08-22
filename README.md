# nvim
This is my neovim config, don't touch it  


Leaving the aside first do:  
sudo add-apt-repository ppa:neovim-ppa/unstable -y  
sudo apt update  
sudo apt install make gcc ripgrep unzip git xclip neovim  

then:  
In terminal:  
```bash
cd ~/.config
git clone https://github.com/Taiyo0004/nvim.git

```
In another terminal:   
```bash
cd home/yourusername
ls
```

if you see a folder named personal then don't do the next step skip to the step after it   
```bash
mkdir personal
cd personal
git clone https://github.com/ThePrimeagen/harpoon.git
```

now if you have folder named personal then just cd into it and clone the harpoon:   
```bash
cd personal
git clone https://github.com/ThePrimeagen/harpoon.git
```

now this step is for those whose lua version is below 5:   
```bash
sudo apt update
sudo apt install lua5.4 liblua5.4-dev
```
