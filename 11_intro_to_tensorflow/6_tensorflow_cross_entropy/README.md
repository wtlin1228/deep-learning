## Cross Entropy in TensorFlow

As with the softmax function, TensorFlow has a function to do the cross entropy calculations for us.

![sigmoid_formula](./image/cross-entropy-diagram.png)

Let's take what you learned from the video and create a cross entropy function in TensorFlow. To create a cross entropy function in TensorFlow, you'll need to use two new functions:

+ `tf.reduce_sum()`

+ `tf.log()`

### Reduce Sum

`x = tf.reduce_sum([1, 2, 3, 4, 5])  # 15`

The tf.reduce_sum() function takes an array of numbers and sums them together.

### Natural Log

`x = tf.log(100.0)  # 4.60517`

This function does exactly what you would expect it to do. tf.log() takes the natural log of a number.

### Quiz

Print the cross entropy using softmax_data and one_hot_encod_label.

