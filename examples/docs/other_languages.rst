***************
Other Languages
***************

Regular Python Examples
=======================

.. py:function:: my_function


.. py:function:: python_function(arg1: BaseClass) -> SomeClass

   This is a very cool function but then in Python.

   :param str arg1: Awesome parameter.


.. py:function:: some_other_function(x: int, y: int, z: int) -> int

   :param int x:
   :param int y:
   :param int z:
   :rtype: int

.. py:class:: BaseClass

.. py:class:: SomeClass(const_arg: int)

   Bases: :py:class:`BaseClass`

   Documentation of a class

   :param x: An input

   .. py:method:: get_stuff() -> bool

      :returns: True if there is stuff

   .. py:property:: some_property

      :type: int


Above is some info about for example :py:func:`my_function`

.. py:function:: function_types_test(x, y, z: int, w)

   :param int x: Variable X
   :param y: Variable Y
   :type y: int
   :param z: Variable Z
   :param w: Variable W
   :type w: str


Regular C++ Examples
====================

.. cpp:class:: BaseClass

.. cpp:class:: MyClass : public BaseClass

   I am an inherited class

   .. cpp:function:: bool get_ready() const

.. cpp:function:: bool my_cpp_function(const int& x)

   :param x: This is the only input to the function.

.. cpp:function:: double function_with_types(int x, float y, bool z, MyClass my_object)

.. cpp:struct:: MyStruct

   I am a structure.

   .. cpp:member:: int x

   .. cpp:member:: int y

Reference to :cpp:func:`my_cpp_function`.
