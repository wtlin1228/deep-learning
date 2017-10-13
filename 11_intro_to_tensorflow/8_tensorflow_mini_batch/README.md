Let's use mini-batching to feed batches of MNIST features and labels into a linear model.

Set the batch size and run the optimizer over all the batches with the `batches` function. The recommended batch size is 128. If you have memory restrictions, feel free to make it smaller.