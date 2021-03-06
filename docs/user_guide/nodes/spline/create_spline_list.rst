Create Spline List
==================

Description
-----------

This node is used to create an arbitrary list of splines. A new spline can be added with the *New Input* button. A new spline can also be added by plugging it into the transparent socket.

.. image:: images/create_spline_list_node.png
   :width: 160pt

Inputs
------

- **Element** - A spline at the index 0.
- **Element** - A spline at the index 1.
- **Element** - ...

Outputs
-------
- **spline list** - A list that contains all the input splines.

Advanced Node Settings
----------------------

- **Change type** - Changes the type of the spline list to another list type.
- **Hide Inputs** - Hides all the inputs in the node.
- **Remove Unlinked Inputs** - Removes all the inputs that are not connected to another node.

Caution
-------

A warning will pop up when you use the *Remove Unlinked Inputs* button in the node, while if you used the the *Remove Unlinked Inputs* button in the *Advanced Node Settings* the inputs will be removed without a warning.

Examples of Usage
-----------------

.. image:: gifs/connect_splines_node_example.gif
