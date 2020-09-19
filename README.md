# Image-Classification-using-VGG

Data set can be found [here](https://www.kaggle.com/vijaygiitk/multiclass-weather-dataset?select=dataset)
you might face problem while making X and y matrix, some images are shown as damaged by Python, i have used tqdm to know about that image and deleted it from dataset.

Dataset consists of images and images are labelled as weather_type_number.jpg, now to feed it into our model, we need to have a X matrix and a y matrix.
and also size of all images is not similar,
so i have resized images, made X vector by 2 different methods and trained VGG
