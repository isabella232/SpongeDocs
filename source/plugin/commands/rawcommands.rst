====================
Writing Raw Commands
====================

.. javadoc-import::
	org.spongepowered.api.command.Command.Raw


.. note::
    
    While Sponge provides the ability for you to control the string parsing yourself, it is recommended that you use
    :doc:`parameterized/index <the parameterized commands instead>`, so that client completions are supported with
    minimal effort from you.
    

.. tip::

    :javadoc:`Command.Raw` replaces API 7's ``CommandCallable``.

Raw commands are simple. Ish.