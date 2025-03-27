# this private repo is for the OpenGraph project


# SUI


# tensorflowsui

phase 1:
standalone move package and TypeScript sdk to auto publish

move package has 2 files:
graph.move
tensor.move


graph.move has all things related layer, graph, activation, etc.

1. node
- SignedFixedLayer
    -get_weight_tensor
    -get_bias_tensor
    -get_layer_in_dim
    -get_layer_out_dim
    -get_layer_name
    
- SignedFixedGraph
    -create_signed_graph
    -share_graph
    -get_layer_at

2. layer
    - DenseSignedFixed
    - ReLU
    - Softmax
    - Activation

3. graph
4. activation




tensor.move has all things related to tensor, operations, arithmetic, etc.






