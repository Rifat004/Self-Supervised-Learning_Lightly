# The HAM10000 dataset, a large collection of multi-source dermatoscopic images of common pigmented skin lesions

Training of neural networks for automated diagnosis of pigmented skin lesions is hampered by the small size and lack of diversity of available dataset of dermatoscopic images. We tackle this problem by releasing the HAM10000 ("Human Against Machine with 10000 training images") dataset. We collected dermatoscopic images from different populations, acquired and stored by different modalities. The final dataset consists of 10015 dermatoscopic images which can serve as a training set for academic machine learning purposes. Cases include a representative collection of all important diagnostic categories in the realm of pigmented lesions: Actinic keratoses and intraepithelial carcinoma / Bowen's disease (akiec), basal cell carcinoma (bcc), benign keratosis-like lesions (solar lentigines / seborrheic keratoses and lichen-planus like keratoses, bkl), dermatofibroma (df), melanoma (mel), melanocytic nevi (nv) and vascular lesions (angiomas, angiokeratomas, pyogenic granulomas and hemorrhage, vasc).

More than 50% of lesions are confirmed through histopathology (histo), the ground truth for the rest of the cases is either follow-up examination (follow_up), expert consensus (consensus), or confirmation by in-vivo confocal microscopy (confocal). The dataset includes lesions with multiple images, which can be tracked by the lesion_id-column within the HAM10000_metadata file.

Due to upload size limitations, images are stored in two files:

HAM10000_images_part1.zip (5000 JPEG files)
HAM10000_images_part2.zip (5015 JPEG files)

## Additional data for evaluation purposes
The HAM10000 dataset served as the training set for the ISIC 2018 challenge (Task 3), with the same sources contributing the majority of the validation- and test-set as well. The test-set images are available herein as ISIC2018_Task3_Test_Images.zip (1511 images), the ground-truth in the same format as the HAM10000 data (public since 2023) is available as ISIC2018_Task3_Test_GroundTruth.csv..


## Results

-  KNN Accuracy: 73%