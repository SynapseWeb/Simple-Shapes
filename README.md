# Simple-Shapes
## A Reconstruct Series made of Simple Shapes suitable for Development and Testing

This series is designed for rapid testing of code. The shapes are intentionally simple
to allow quick tracing and relatively easy examination and interpretation of the XML.

## Animation showing slices inside the original objects:
![SlicingAnimation](docs/frames.gif?raw=true "Slicing Animation")

# Usage Examples

## Understanding Closed Point-by-Point Drawing Mode (Reconstruct.exe)

The following two images show the points created with the "Closed Point-by-Point Drawing" tool in Reconstruct.exe version 1.1.0.0.

The top image shows the points that result from drawing the polygons with "simplify" ("Automatically simplify new closed traces after drawing") turned off. The numbers show the order and locations of the individual mouse clicks to create the trace. There is exactly one point per mouse click.

The bottom image shows result from the same process with "simplify" turned on (the default setting). Note the additional points that Reconstruct has inserted between the actual mouse clicks.

![SimplifyOff](docs/Corner_Points_Simplify_Off.png?raw=true "Simplify Off")

![SimplifyOn](docs/Corner_Points_Simplify_On.png?raw=true "Simplify On")
