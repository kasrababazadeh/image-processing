# Image Processing with Motion Blur, Noise, and Wiener Filter

This repository contains a Python implementation of common image processing techniques, specifically motion blur, Gaussian noise addition, and Wiener filtering. This code can be particularly useful in medical imaging applications where noise reduction and image restoration are critical.

## Features

- **Motion Blur**: Simulates the effect of motion blur using a simple averaging kernel.
- **Gaussian Noise**: Adds Gaussian noise to an image, simulating real-world conditions.
- **Wiener Filter**: Applies Wiener filtering to restore the image and reduce noise.
- **Grayscale Conversion**: Converts RGB images to grayscale for processing.
- **Mean Squared Error Calculation**: Computes the MSE between images to evaluate restoration quality.

## Requirements

- Python 3.x
- NumPy
- SciPy
- OpenCV
- Matplotlib

You can install the required packages using pip:

```bash
pip install numpy scipy opencv-python matplotlib
```

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/kasrababazadeh/image-processing.git
   cd image-processing
   ```

2. Update the process_image function call with your image path:

   ```bash
   process_image('/path/to/your/image.jpg', kernel_size=15, noise_sigma=100)
   ```

3. Run the script to see the effects of motion blur, noise addition, and Wiener filtering.

## MSE Results

- **MSE between original and noisy image**: 6505.30
- **MSE between original and filtered image**: 3172.42

## Notes

- Make sure to use grayscale images or convert your images to grayscale using the provided `rgb2gray` function.
- Adjust the kernel size and noise parameters as necessary based on your specific use case.
- This implementation can be extended for more advanced image processing techniques.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

You can also view the full text of the MIT License [here](https://opensource.org/licenses/MIT).
