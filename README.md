# Pituitary-tumor Segmentation using UNET

Pituitary tumors are abnormal growths that develop in the pituitary gland, a small gland located at the base of the brain. These tumors can cause hormonal imbalances, vision problems, and other serious health issues. Accurate segmentation of pituitary tumors from medical images is an essential step in diagnosis and treatment planning.

In this project, we have used a deep learning technique called UNET for the segmentation of pituitary tumors from magnetic resonance imaging (MRI) scans. UNET is a convolutional neural network architecture that has been successfully used for medical image segmentation tasks. It is particularly useful for segmentation tasks where the object of interest is relatively small compared to the image size, as is the case with pituitary tumors.

The project involve the following steps:

<ul>
        <li>Data collection: We have collected a dataset of MRI scans that include pituitary tumors. The dataset is obtained from publicly available sources.</li>
        <li>Data preprocessing: The MRI scans have been preprocessed as they were in .mat format to numpy array. We have performed image normalization and scaling to make the data compatible with the UNET model.</li>
        <li>Model training: We have trained a UNET model using the preprocessed MRI scans. The model have learnt to identify and segment pituitary tumors from the background of the image.</li>
        <li>Model evaluation: We have evaluated the performance of the UNET model on a separate set of MRI scans that were not used for training. We have used standard metrics such as dice coefficient, sensitivity, and specificity to measure the accuracy of the segmentation.</li>
        <li>Results interpretation and visualization: The segmented pituitary tumors will be visualized using a 2D rendering tool to help physicians better understand the location and extent of the tumor.</li>
</ul>
