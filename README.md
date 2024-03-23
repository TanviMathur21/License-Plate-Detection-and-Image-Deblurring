# License-Plate-Detection-and-Image-Deblurring

This project focuses on the concept of Super Resolution enhancing the quality of low-resolution car images with a license plate by employing deep learning techniques. Beginning with the plate detection and extraction of license plate details, it proceeds to apply image deblurring methods using the Super-Resolution Convolutional Neural Network (SRCNN). Pytesseract facilitates the extraction of license plate information, serving as input for deblurring procedures. The goal is to restore image details and mitigate blur or noise, resulting in high-resolution images akin to ground truth. Through this process, the project aims to improve the overall clarity and quality of car images, demonstrating the efficacy of deep learning in image enhancement tasks.

The flow of the project:
	Taking a high-resolution image of a car as the input image
	Detecting the number plate in the image and creating a bounding box
	Extracting the license number from the number plate using pytesseract
	Saving the image of the number plate and making it an input image for the image deblurring
	Adding a noise/blur to the image
	Recovering the pixels or image details by using SRCNN

Thank You ! :)
