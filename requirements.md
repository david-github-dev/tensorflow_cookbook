##### setup environment

Python
```
sudo apt-get install python-pip python-dev
```

Tensorflow
```
download link,  https://pypi.python.org/pypi/tensorflow
1）CPU
pip install https://pypi.python.org/packages/d3/7f/9d7a7f3642888fd2360bc38b3d820347d315fa6492485895bf51e794c3ff/tensorflow-1.2.0rc0-cp27-cp27mu-manylinux1_x86_64.whl#md5=495ac6712cfe6acc6bc8fd3185dea076

2）GPU(CUDA SDK required) 
pip install https://storage.googleapis.com/tensorflow/linux/gpu/tensorflow-0.5.0-cp27-none-linux_x86_64.whl
```

python test.py
```
# File Name: test.py    
# Run Command:     
import tensorflow as tf
sess = tf.Session()
a = tf.constant(10)
b = tf.constant(22)
print(sess.run(a + b)) 
print "tensorflow version is %s " %tf.VERSION
```

tensorflow
numpy
scipy
sklearn
requests
jupyter
matplotlib
