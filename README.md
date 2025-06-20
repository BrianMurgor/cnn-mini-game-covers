# Cnn-mini-game-covers
CNN project classifying video game cover images into genres

This project uses a 6-layer CNN in PyTorch to classify video game cover images into five categories: `Indie`, `Puzzle`, `Platform`, `Fighting`, `Sport`.

## Dataset
Custom dataset containing resized game covers.

## Model Details
- 6 convolutional layers
- ReLU activations
- Max Pooling
- Adam optimizer
- 20 epochs

## Performance
- Final test accuracy: **24.80%**
- No data augmentation used

