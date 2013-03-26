In your python project working folder, place ``bootstrap.py`` to create automatically virtualenv instance :

::

    $ curl -O https://raw.github.com/harobed/virtualenv-bootstrap/master/bootstrap.py

Next, append this ``bootstrap.py`` file in your repository, example :

::

    $ git add bootstrap.py
    $ git commit -m "Append bootstrap.py file to install create easily virtualenv instance"
    $ git push

Now, when you clone your projet, you can start to hack on your project like this :

::

    $ git clone http://...
    $ python bootstrap.py
    $ bin/pip install -r requirements.txt
