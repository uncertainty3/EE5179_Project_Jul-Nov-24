This is the Course Project for EE5179: Deep Learning for Imaging, where we had to restore images of the MVTec Dataset. 

Instructions for testing a sample image:
1. Open the Testing Notebook in Google Colab or any other system with access to a GPU, which is required to run the model. 
2. After this, replace the path to test images in the process_images() function and the GT_root path. Note that this code assumes that the test images follow the same directory structure as the MVTec train and validation dataset. 
3. Then, run all the cells in the notebook, and the PSNR and SSIM results are printed at the end. And images are stored in a separate output directory.

