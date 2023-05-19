# FairFaceRecognition
Project for Algorithmic Fairness course at the IT University of Copenhagen, spring 2023.


<br>

The folder structure is as follows:

**code (folder)**
* THE_NOTEBOOK.ipynb (Includes all code from the project)
* sliding_cover.ipynb (Example of how we made our own Captum like algorithm)

**data (folder)**
* **celeb_dataset (folder)**
    * pred_on_all_augmentations.csv (full table of attributes and which we detected faces with different augmentations)

    * not_found.p (pickle file with which we detected faces on full 200.000 images)
    * **img_align_celeba (folder)**
        * list_attr_celeba.csv (attributes which are used in THE_NOTEBOOK.ipynb)

        * list_bbox_celeba.csv (from dataset, not used in project)
        * list_eval_partition.csv (from dataset, not used in project)
        * list_landmarks_align_celeba.csv (from dataset, not used in project)
        * **normal (folder of original dataset)**
        * **brighter (folder of augmented images)**
        * **contrast (folder of augmented images)**
        * **darker_skin (folder of augmented images)**
        * **lighter_skin (folder of augmented images)**

**figures (folder)**
* (figures and tables)

**litterature (folder)**
* (articles and exam guidelines)

