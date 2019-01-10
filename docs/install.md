# Install Python 3

To run this service, you must have Python 3.6+ installed. It's also a good
idea to create a virtual-environment to avoid polluting your system-wide
Python packages.

Please read [these instructions][installpython] to get you setup.

[installpython]: https://docs.chaostoolkit.org/reference/usage/install/#install-python

# Install From Distribution

Run the following command from your virtual-environment:

```
$ pip3 install -U chaosplatform-scheduling
```

# Install From Source

Clone the repository:

```
$ git clone https://github.com/chaostoolkit/chaosplatform-scheduling.git
```

Now, simply run the following from your virtual environment:

```
$ pip3 install -U -r requirements.txt
$ python3 setup.py install
```
