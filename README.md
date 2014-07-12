Installation for use with tutorial: Sarah Guido, [Hands-On Data Analysis with Python](http://www.oscon.com/oscon2014/public/schedule/detail/34254).

### Installation on Mac OS 10.9.4

 * **Python 2**: 

        virtualenv v_env2
        . v_env2/bin/activate
        pip install -Ur requirements_py27.txt

   As of 20140711 this is sufficient.

 * **Python 3**: 

        virtualenv v_env3 --python=python3.4
        . v_env3/bin/activate

   Following http://askubuntu.com/questions/449326/installation-error-in-sklearn-for-python3, (dated 201404; accessed 20140711) use:

        pip install numpy
        sudo pip3 install git+https://github.com/scikit-learn/scikit-learn.git
        pip install -Ur requirements_py34.txt

   Information about non-`pip` dependencies is available at http://stackoverflow.com/questions/2213551/installing-scipy-with-pip.

[end]
