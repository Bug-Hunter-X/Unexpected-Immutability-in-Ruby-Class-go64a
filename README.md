# Unexpected Immutability in Ruby Class

This example demonstrates a common misconception when working with Ruby classes.  If a method only defines a getter (`value` method) and omits a setter, the object's attribute becomes effectively immutable, even though it appears like you have access to it.

This can lead to unexpected behavior and hard-to-debug errors if not properly understood.

The solution demonstrates how to properly define both getter and setter methods to allow modification of the attribute.