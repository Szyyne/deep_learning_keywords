

Inspect layers of the network by referencing Layers property:
#indexing
(network)variable.Property
ly =  deepnet.Layers

Inspect an individual layer by indexing:
layer1 = ly(1)
layer2 = ly(2)
.
.
access the Inputsize of layer:
    layer1.InputSize

input size:
m x n x 3 #color
m x n     #greyscale


