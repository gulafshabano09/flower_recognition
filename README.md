# flower_recognition
Machine Learning Project on Flower Recognition with Python.

## What is Flower Recognition?
There are many species of flowers in the world. Some species have many colours, such as roses. It is difficult to remember all the names of flowers and their information. Additionally, someone may be confused with similar flower species.

For example, white champaka and champak have similar names and petal shapes, but they have different colours and petal lengths.

At present, it is almost impossible to identify any particular flower or flower species in any way other than to seek information based on personal knowledge and expert experience. The availability of such experts can be an obstacle to this search for information.

Searching for such information on the Internet today is very limited to keyword research; word processor. Even then, the searcher has to come up with sufficiently useful keywords, which they cannot do, which is the crux of the matter.


## Machine Learning Project on Flower Recognition with Python
The dataset I am using here for the flower recognition task contains 4242 flower images. Data collection is based on Flickr data, google images, Yandex images. You can use this data set to recognize the flowers in the photo.

The images are divided into five classes: chamomile, tulip, rose, sunflower, dandelion. For each class, there are approximately 800 photos. The photos are not in high resolution, approximately 320×240 pixels. Photos are not reduced to one size, they have different proportions.


**Now let’s import the necessary Python libraries to get started with the task of Flower Recognition with Python:**

![f1](https://user-images.githubusercontent.com/95492893/144716358-f73a6cf0-4944-49a0-af0d-6cdcc42e88e3.PNG)

**Now the next step is to read each image in the data and create a label for each with the name of the folder:**

![f2](https://user-images.githubusercontent.com/95492893/144716390-eb5d58a5-5ab3-4a4e-9e94-b7e95f1736aa.PNG)

**Now let’s convert the data into numerical values:**
![f3](https://user-images.githubusercontent.com/95492893/144716429-e5d307a5-6d00-4916-a536-f6fb57aa38c2.PNG)

**Now let’s use the Label encoder and normalize the data:**
![f4](https://user-images.githubusercontent.com/95492893/144716470-1bd2375d-df67-4742-baa2-036b26800180.PNG)

The next step is to split the dataset into 80% training and 20% test sets:

**X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.20, random_state=10)**

**Now let’s build a neural network model for the task of Flower Recognition:**
![f5](https://user-images.githubusercontent.com/95492893/144716537-57276408-a1e5-4fac-8960-0612bd5db7a5.PNG)

**Before compiling the model we need to create more training images to prevent overfitting:**
![f6](https://user-images.githubusercontent.com/95492893/144716574-a73b1458-e954-4e56-9935-d7bcee04dedd.PNG)

**Now let’s compile the neural network model:**
![f7](https://user-images.githubusercontent.com/95492893/144716612-de33fd8e-65b9-4967-a004-ffa040effc4c.PNG)

**Now let’s let the model if it recognize flowers properly:**
![f8](https://user-images.githubusercontent.com/95492893/144716638-628d595b-f3b2-4482-aa2c-8806abafba19.PNG)

![image](https://user-images.githubusercontent.com/95492893/144716650-540f5c56-f7fe-481e-8ff9-1157aae3d757.png)










