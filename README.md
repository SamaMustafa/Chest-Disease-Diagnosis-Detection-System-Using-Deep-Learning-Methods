- Dataset:
A team of Researchers from Qatar University, Doha and Dhaka University along with their connections from Pakistan, Malaysia, in collaboration with doctors, have created the primary dataset with 4 classes(COVID-19, Lung-Opacity, Normal and Viral Pneumonia). 
The primary dataset has been collected from the Kaggle (COVID-19 Radiography Database). 
Some more contents added of Pneumonia and COVID-19 with it from various online resources . One more class has added with Tuberculosis with the 4 class dataset. 
The lateral view Chest X rays removed and added only the frontal view to the dataset 
- Classes:
1- COVID-19 :  4,189 
2- Lung-Opacity : 6,012 
3- Normal : 10,192 
4- Viral Pneumonia : 7,397
5- Tuberculosis : 4,897 

- Used Albumentations for different types of augmentation for data balancing.
- Used MobileNet V2 to classify the different type of diseases. 
