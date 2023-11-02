# Breast-Cancer-Detection-using-Machine-Learning

Introduction:

Breast cancer is a significant global health concern, with millions of new diagnoses and thousands of deaths each year. Early detection plays a crucial role in reducing breast cancer mortality rates. Mammography is a widely used screening method for breast cancer, but it relies heavily on the expertise of radiologists, making it expensive and prone to false positives. To address these challenges, this GitHub project focuses on using machine learning to improve the automation of breast cancer detection in screening mammograms.

The goal is to assist radiologists in making more accurate and efficient diagnoses, ultimately enhancing patient care, reducing costs, and minimizing unnecessary medical procedures.

Dataset Description:

The dataset provided for this project includes radiographic breast images of female subjects. Each image is in DICOM format, and you can expect to find approximately 8,000 patients in the hidden test set. The dataset contains the following key attributes:

site_id: ID code for the source hospital.

patient_id: ID code for the patient.

image_id: ID code for the image.

laterality: Indicates whether the image is of the left or right breast.

view: Specifies the orientation of the image (e.g., craniocaudal, mediolateral oblique).

age: The patient's age in years.

implant: Indicates whether or not the patient has breast implants (only available at the patient level).

density: A rating for how dense the breast tissue is (A being the least dense, D being the most dense).

machine_id: An ID code for the imaging device.

cancer: The target value indicating whether the breast is positive for malignant cancer.

biopsy: Indicates whether a follow-up biopsy was performed on the breast.

invasive: If the breast is positive for cancer, indicates whether the cancer proved to be invasive.

BIRADS: A rating system (0 for follow-up required, 1 for negative for cancer, 2 for normal) only available in the training set.

prediction_id: The ID for the matching submission row, which is used for test data.

difficult_negative_case: A boolean value indicating if the case was unusually difficult, available only in the training set.

Project Objective:

The primary objective of this project is to develop a machine learning model capable of detecting breast cancer in mammograms with high accuracy. The model will be trained on the provided dataset, and the resulting algorithm will be used to predict breast cancer in the hidden test set. The project aims to reduce the reliance on manual human observation, improve the efficiency of breast cancer screening, and minimize false positives.

Impact:

By improving the automation of breast cancer detection, this project can have several important impacts:

Improved Early Detection: Early detection is crucial in reducing breast cancer mortality rates. Automating the screening process can help identify cases at an earlier stage, leading to more successful treatments.

Efficiency and Cost Reduction: Automating the detection process can make breast cancer screening more efficient and cost-effective, particularly in regions with a shortage of radiologists.

Reduced False Positives: Reducing the rate of false positive results can decrease patient anxiety, the need for follow-up care, and unnecessary medical procedures.

Wider Access: By using machine learning, this project can extend the benefits of early breast cancer detection to a broader population, ultimately contributing to the global fight against breast cancer.

