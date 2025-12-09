# nvim
This is my neovim config, don't touch it  


Leaving that aside first do:  
```bash
sudo add-apt-repository ppa:neovim-ppa/unstable -y  
sudo apt update  
sudo apt install make gcc ripgrep unzip git xclip neovim  
```

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

now this step is for those whose lua version is below 5 and don't have lua rocks:   
```bash
sudo apt update
sudo apt install lua5.4 liblua5.4-dev -y
sudo apt install luarocks -y
```
now this is the next step installing node and npm so if you have that you don't have to do this step:   
```bash
sudo apt update
sudo apt upgrade -y
sudo apt install nodejs npm
```

now this is stupid linux system come python3 install but not venv so if you don't have that so do this step:   
```bash
sudo apt update
sudo apt install python3-venv -y
```

and even after this you get this error search it online google it and get gud.




______________________________________________________________________________________ThankYOU________________________________________________________________
