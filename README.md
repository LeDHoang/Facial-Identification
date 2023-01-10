# Facial-Identification using Machine Learning with pre-trained model

## A Facial Identification Jupyter notebook using Facenet framework by Google Researchers on Pytorch

Program can run on both photo files and a live webcam

Program is tested on photo database from VKIST in Hanoi,Vietnam that are collected during their events 

Photos are taken at different angles to improve the accuracy overall 

Photo database can be found here [Database](https://mega.nz/folder/0d5lSKyT#mtZUzzMC_hpP5aPVpzvZZw)

Photo files are seperated to 4 files (poliface_orign,poliface_test, poliface_run and poliface_run_max) with different functions

- `poliface_origin` is used to first identified the face

- `poliface_test` is the files used to test the AI on identifying face with more unknown subject

- `poliface_run` is the result photo files seperated with the name of the subject as the folder name

- `poliface_run_max` is the result photos including with frame over detected photos and name that program is identifying them with 

To test run, download the photos database from above link into the root directory 

Run the notebook inside IDE and result should be as above

![Result](https://res.cloudinary.com/dypitsv20/image/upload/v1673326394/Capture_gnwiso.jpg)

## To use live webcam feed to test

Run the last cell to test, press `ESC` to close the webcam window

Press the spacebar to save photo

![Result](https://res.cloudinary.com/dypitsv20/image/upload/v1673326956/Capture_1_ycpr7z.jpg)





