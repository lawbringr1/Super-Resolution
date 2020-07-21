# RGB image super-resolution
## In the project we implemented Super Resolution using Convolutional Neural Networks and Deep learning
There are very limited number of methods to enhance the resolution of the RGB image. We by using the most emerging deep learning technique which is SRCNN technique tried enhancing the image’s quality. SRCNN is a supervised technique, and we used around 91 images to train the model. From the trained SRCNN, a high-resolution image was generated from a lowresolution image. The original image was down scaled using bilinear interpolation and then was made to pass through our SRCNN model and the high-resolution image was generated as an output. We used several indexes other than visual difference, to measure the quality of the image generated like SSIM (Structural Similarity Index Module), PSNR (Peak Signal to Noise Ratio), and MSE (Mean Square Error). These measures help to understand the error difference between the original image and the generated ones.