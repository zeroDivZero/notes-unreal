# GLOSSARY

## Event Graph

Canvas for Blueprint.

## Node

Premade functionality.

## Event

"When" node. Triggers action when something happens.

## Pin

Node socket that can be connected.

Can drag pin to empty space to create node.

### Input Pin

When to run this node.

### Output Pin

What to run after.

Both input and output pins also called **Execution Pins**.

### Data Pin

Input or output data for node.

## Connection

Wire connecting pins.

### Example

![Blueprint example](/assets/Blueprint/blueprint-example.png)

## Object

Collection of data and functionality.

## Actor

Object in level.

## Component

Object that can go on actor.

## Reference

Where to find object. Expensive to copy object, instead refer to same object using reference (address).

In level view, select actor. Then in Event Graph, right click and select **Create a Reference to [Name]** to create node that references that actor.

Can then get component from that reference and query its values.

![Reference example](/assets/Blueprint/blueprint-reference.png)
