# Plain-Autoencoder
Plain autoencoder applied on MNIST dataset to evaluate the performance.

Plain autoencoder of 3 neurons in its bottleneck layer is applied to reconstruct MNIST data.
Precisely, the layers and respective neurons are as below :
Input (28 * 28), 128, 64, 12, 3 (bottleneck), 12, 64, 128, Output (28 * 28).

Just 3 layers on each side of the bottleneck works quite well approaching low reconstruction loss.

Also, checkpoint-restart logic is implemented to commence from any interrupted point during training.
