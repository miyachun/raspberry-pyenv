
curl https://pyenv.run | bash  
sudo nano ~/.bashrc  

下面3行新增到文件最後  
export PATH="$HOME/.pyenv/bin:$PATH"  
eval "$(pyenv init --path)"   
eval "$(pyenv virtualenv-init -)"  
  
CTRL + S  
CTRL + X  
  
exec $SHELL  
  
sudo apt-get install --yes libssl-dev zlib1g-dev libbz2-dev libreadline-dev libsqlite3-dev llvm libncurses5-dev libncursesw5-dev xz-utils tk-dev libgdbm-dev lzma lzma-dev tcl-dev libxml2-dev libxmlsec1-dev libffi-dev liblzma-dev wget curl make build-essential openssl  
  
pyenv update  
  
pyenv install --list  
  
pyenv install 3.7.12  
  
pyenv shell 3.7.12  
  
pyenv global 3.7.12  
  
rm -fr ~/.pyenv  
Remove lines from .bashrc  

python3 -m pip install virtualenv  
python3 --version  
python3.7 -m venv tf  
source tf/bin/activate  
git clone https://github.com/tensorflow/examples --depth 1  
cd /home/pi/examples/lite/examples/object_detection/raspberry_pi  
sh setup.sh  



