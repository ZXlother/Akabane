# Akabane
A neural network based trading application focusing on cyrptocurrency market.

Dependency Installation guide (steps to get it working on the Windows Subsystem for Linux) as of 12/31/2017

#Download python incase you somehow don't have it already
sudo apt-get install python3-pip python3-dev
#Download tensorflow with cpu support. Latest as of 12/31/17. Go to https://www.tensorflow.org/install/install_linux#the_url_of_the_tensorflow_python_package for other packages
sudo pip3 install --upgrade \
 https://storage.googleapis.com/tensorflow/linux/cpu/tensorflow-1.4.0-cp34-cp34m-linux_x86_64.whl
 
#sample repo to make sure tensorflow works. Try this for the image recognition sample.
git clone https://github.com/tensorflow/models.git
cd models/tutorials/image/imagenet
python classify_image.py
#Google Trends Module called pytrends by GeneralMills
#https://github.com/GeneralMills/pytrends

pip3 install Requests pandas
sudo apt-get install python3-lxml
pip3 install lxml
pip3 install pytrends
curl -s https://raw.githubusercontent.com/GeneralMills/pytrends/master/examples/example.py | python3
