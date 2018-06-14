# Simple-Shapes
## A Reconstruct Series made of Simple Shapes suitable for Development and Testing

This series is designed for rapid testing of code. The shapes are intentionally simple
to allow quick tracing and relatively easy examination and interpretation of the XML.

## Animation showing slices inside the original objects:
![SlicingAnimation](docs/frames.gif?raw=true "Slicing Animation")

# Usage Examples

## Understanding Closed Point-by-Point Drawing Mode (Reconstruct.exe)

The following two images show the points created with the "Closed Point-by-Point Drawing" tool in Reconstruct.exe version 1.1.0.0.

This first image shows the points that result from drawing the polygons with "simplify" ("Automatically simplify new closed traces after drawing") turned off. The numbers show the order and locations of the individual mouse clicks to create the trace. There is exactly one point per mouse click.

![SimplifyOff](docs/Corner_Points_Simplify_Off.png?raw=true "Simplify Off")

This second image shows the points that result from the same process with "simplify" turned on (the default setting). Note the additional points that Reconstruct has inserted between the actual mouse clicks.

![SimplifyOn](docs/Corner_Points_Simplify_On.png?raw=true "Simplify On")

This image shows some close up views of the newly inserted points.

![SimplifyOnDetail](docs/Extra_Points_Detail.png?raw=true "Detailed View of Simplify On case")
