# python-code-for-splitting-a-downloaded-dataset-into-train-and-test
We sometimes download a dataset of images that is not split into train and test. However, the dataset includes some .meta files which have already indexed images as 'train' or 'test' data. this project uses the .meta and .json files and splits the dataset into train and test folders.

The dataset which was used in this example is: food101 which I downloaded from the following link:
https://www.kaggle.com/dansbecker/food-101

The dataset folder name is "...\desktop\Food101" on my computer.

since there is another subfolder named food-101" and my goal is to split the code into train/test, I used the "split_dataset(download_dir/'food-101')" for splitting the data.
