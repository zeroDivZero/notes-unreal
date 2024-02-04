# DATA TYPES

Supports primitive types:

![Primitive Data Types](/assets/Blueprint/primitive-data-types.png)

Combined to form structs or classes/objects.

## Struct

Small object copied around (no referencing).

### Examples

* Vector
* Rotator
* Transform

Even if two have same data shape, cannot assign one to another; semantic meaning matters.

## Object

Typically larger and more complex data shape. Passed by reference.

### Examples

* Actor
  * Cube
  * Blueprint instance
* Component
  * StaticMeshComponent

In Blueprint, pins color-coded to provide visual clue of data type and which ones can connect.
