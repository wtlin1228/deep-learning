## nstructions

Open quiz.py.

+ Implement `get_weights` to return a `tf.Variable` of weights

+ Implement `get_biases` to return a `tf.Variable` of biases

+ Implement `xW + b` in the linear function

Open sandbox.py

+ Initialize all weights

+ Since `xW` in `xW + b` is matrix multiplication, you have to use the `tf.matmul()` function instead of `tf.multiply()`. Don't forget that order matters in matrix multiplication, so `tf.matmul(a,b)` is not the same as `tf.matmul(b,a)`.