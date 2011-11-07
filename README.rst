################
Drupal bootstrap
################

This project provides tools to bootstrap a Drupal deployment.
It uses `drupalindustry.templates`_ utilities.

*****
Usage
*****

* Set up a server to host a Drupal site:

  * `Drupal requirements`_
  * Python 2.6 or 2.7

* Push or pull the sources on the server.
  To get the source, you can use Git:
  ::

    # Get the source
    git clone ssh://TRIGRAM@cgit.makina-corpus.net/home/users/bbr/git/drupal-bootstrap.git

* On the server, run:
  ::

    bin/bootstrap

  .. note::

    You can execute bootstrap from anywhere, with a relative or absolute
    path, i.e. the command could be "/PATH/TO/bin/bootstrap".

**********
References
**********

.. target-notes::

.. _`drupalindustry.templates`: https://github.com/makinacorpus/drupalindustry.templates/
.. _`Drupal requirements`: http://drupal.org/requirements