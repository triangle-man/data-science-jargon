# Neural network

A neural network is a kind of computational model -- a way of building a machine -- that is somewhat analogous to the network of neurons in a biological brain.

It consists of a number of "units". Each unit receives signals from a collection of other units, combines these signals together, and uses the result to decide on its own output signal. That output can be sent to any number of other units.

Typically the signals are just numbers, and the way a unit combines its inputs together is to multiply each input by a number called a "weight", and then add the result together.

To use a neural network, particular units are designated as "inputs" and others as "outputs" -- one sends an input signal (for example, the colour of pixels in an image) to the input units and reads off the output (for example, whether this is an image of a cat) from the output units. The idea is that by suitably adjusting the way the units are connected together and by carefully choosing the weights, the entire system will work to turn inputs to outputs in a useful way.

What makes neural networks an example of *machine learning* is that it's possible to automate the process of choosing the weights. That is, the machine is repeatedly presented with inputs and the desired outputs and the weights are adjusted to improve the machine's performance in generating an output which is close to the desired one.

Some notes:

- We don't usually build actual "neural units"; instead they are simulated on a normal computer.
  
- Neural networks were popular early on in AI research, before the 1970s, and provided a different approach to the "logical reasoning" systems that were prevalent, although they did not seem to be sufficiently general to be useful. Research dried up in the general "AI winter" of the late 1970s. At this time there was a breakthrough in the way we were able to train complex neural networks but still other approaches seemed to be faster. More recently, neural nets have again risen to prominence as we have been able to deploy large-scale computational resources, especially in problems like image and speech regonition.

- I think "*deep learning*" means "neural network with more than two layers"



