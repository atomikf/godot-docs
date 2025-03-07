:github_url: hide

.. DO NOT EDIT THIS FILE!!!
.. Generated automatically from Godot engine sources.
.. Generator: https://github.com/godotengine/godot/tree/master/doc/tools/make_rst.py.
.. XML source: https://github.com/godotengine/godot/tree/master/doc/classes/ScrollBar.xml.

.. _class_ScrollBar:

ScrollBar
=========

**Inherits:** :ref:`Range<class_Range>` **<** :ref:`Control<class_Control>` **<** :ref:`CanvasItem<class_CanvasItem>` **<** :ref:`Node<class_Node>` **<** :ref:`Object<class_Object>`

**Inherited By:** :ref:`HScrollBar<class_HScrollBar>`, :ref:`VScrollBar<class_VScrollBar>`

Abstract base class for scrollbars.

.. rst-class:: classref-introduction-group

Description
-----------

Abstract base class for scrollbars, typically used to navigate through content that extends beyond the visible area of a control. Scrollbars are :ref:`Range<class_Range>`-based controls.

.. rst-class:: classref-reftable-group

Properties
----------

.. table::
   :widths: auto

   +---------------------------+----------------------------------------------------------+-------------------------------------------------------------+
   | :ref:`float<class_float>` | :ref:`custom_step<class_ScrollBar_property_custom_step>` | ``-1.0``                                                    |
   +---------------------------+----------------------------------------------------------+-------------------------------------------------------------+
   | :ref:`float<class_float>` | step                                                     | ``0.0`` (overrides :ref:`Range<class_Range_property_step>`) |
   +---------------------------+----------------------------------------------------------+-------------------------------------------------------------+

.. rst-class:: classref-section-separator

----

.. rst-class:: classref-descriptions-group

Signals
-------

.. _class_ScrollBar_signal_scrolling:

.. rst-class:: classref-signal

**scrolling** **(** **)**

Emitted when the scrollbar is being scrolled.

.. rst-class:: classref-section-separator

----

.. rst-class:: classref-descriptions-group

Property Descriptions
---------------------

.. _class_ScrollBar_property_custom_step:

.. rst-class:: classref-property

:ref:`float<class_float>` **custom_step** = ``-1.0``

.. rst-class:: classref-property-setget

- void **set_custom_step** **(** :ref:`float<class_float>` value **)**
- :ref:`float<class_float>` **get_custom_step** **(** **)**

Overrides the step used when clicking increment and decrement buttons or when using arrow keys when the **ScrollBar** is focused.

.. |virtual| replace:: :abbr:`virtual (This method should typically be overridden by the user to have any effect.)`
.. |const| replace:: :abbr:`const (This method has no side effects. It doesn't modify any of the instance's member variables.)`
.. |vararg| replace:: :abbr:`vararg (This method accepts any number of arguments after the ones described here.)`
.. |constructor| replace:: :abbr:`constructor (This method is used to construct a type.)`
.. |static| replace:: :abbr:`static (This method doesn't need an instance to be called, so it can be called directly using the class name.)`
.. |operator| replace:: :abbr:`operator (This method describes a valid operator to use with this type as left-hand operand.)`
