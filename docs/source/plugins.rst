cogitare.plugins
================

Plugins are high-level objects (any callable object, such as classes with
``__call__``, user defined functions, and lambdas) that are used to inspect the
model during training, to provide feedbacks to the user, and to interact with the model.

For example, you can register a plugin to  plot train and validation loss
during each epoch, along with an early stopping algorithm that watches the
validation loss and save/stop the model if the loss is not decreasing.

We start by exemplifying who to use your own plugin, and then describe the
plugins already implemented in Cogitare.

If you have a plugin implementation/idea/request, contributions are welcome!


Custom Plugin
-------------

TODO


Official Plugins
----------------

.. automodule:: cogitare.plugins
    :members: