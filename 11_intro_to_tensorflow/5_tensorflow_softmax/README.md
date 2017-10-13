## TensorFlow Softmax

We're using TensorFlow to build neural networks and, appropriately, there's a function for calculating softmax.

`x = tf.nn.softmax([2.0, 1.0, 0.2])`

Easy as that! `tf.nn.softmax()` implements the softmax function for you. It takes in logits and returns softmax activations.

### Quiz

Use the softmax function in the quiz below to return the softmax of the logits.