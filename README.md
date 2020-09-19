# TermUNI
## National University of Engineering
Final Project of Advanced Artificial Intelligent

Team members:
- Condori Ccora Ed
- Cordova Vargas Paul
- Huaricacha Chuco Frak

![](https://scontent.flim8-1.fna.fbcdn.net/v/t1.0-9/119712303_3634698776542811_2232950030415329460_n.jpg?_nc_cat=103&_nc_sid=8024bb&_nc_eui2=AeFcYi-v0FLd3uCM5DHg5kUyV0iZb0KyPfNXSJlvQrI982qWmj4zQZwtUkB8QiHXqWBpP4C60xQcbZgZZGYUPTy8&_nc_ohc=C3XqmqxOULUAX9S2IPr&_nc_ht=scontent.flim8-1.fna&oh=4a099f886ea80eefc45fac53b1a4f674&oe=5F8BEE5A)

### Step 1
Finding the dataset to train a model, for this work we have used the data set found in the repository 
[Corona-virus-detection](https://github.com/contractorwolf/coronavirus-mask-detection/tree/master/images/ "Corona-virus-detection")
which contains a data set of people with and without masks.

### Step 3
Develop a model using Tensorflow and Keras, for this we use the parameters of Google's Coco model.

### Step 4
Convert the model created from a computer or laptop into a light version, for this we use Tensorflow functions to convert the model into a Tensorflow Light.

### Step 5
Set up the Raspberry Pi 4 to obtain temperature measurements, for this the Adafruit library was used.

### Step 6
At the end, the main program is developed that obtains frames with the Raspberry camera and that is evaluated with the TensorFlowLite model to determine whether or not it has a mask, on the other hand, the person's temperature is taken and thus evaluate if it is complying with the rules.
