# Hydropanics-CNN
using CNN for classifying types of root
## DISCRIPTION
>  we will investigate a practical use case of applying deep learning to hydroponics, a type of method used to grow plants without soil using mineral-rich nutrient solutions in a water solvent.Specifically, you will learn how to train a Convolutional Neural Network (CNN) using Keras to automatically classify root health without having to physically touch the plants.
## DATASET
> Our dataset of 1,524 root images includes:
> * Hairy: 748 images (left)
> * Non-hairy: 776 images (right)
> The original images were captured at a higher resolution of 1920×1080 pixels; however , I’ve resized them to 256×256 pixels ,such as below:
![sample-dataset](https://user-images.githubusercontent.com/53394692/111520112-08937a80-876d-11eb-8959-9b0a4e2fe0e1.PNG)
## STRUCTURE of This Project
> Our `dataset` directory consists of `hairy_root` , `non_hairy_root` and `test`  images.
>
> The `pyimagesearch` directory is a Python module containing `simplenet.py` . The `SimpleNet`  architecture is a Keras deep learning architecture I designed for root health classification. 
> 
> We’ll then train our network with `train_network.py` , producing `plot.png` , our training plot.
## Training Procedure
> for starting the train procedure ,you can run following command :
```
python train_network.py --dataset dataset
```
> after ending, you can able to see the results,such as below :
>
![plot](https://user-images.githubusercontent.com/53394692/111522023-11854b80-876f-11eb-9cbf-f617ff290abc.png)
>
> and see results as below :
> 
![result](https://user-images.githubusercontent.com/53394692/111522209-4c877f00-876f-11eb-8ee9-be165d44d843.PNG)

## License
> [Deep learning, hydroponics, and medical marijuana](https://www.pyimagesearch.com/2018/10/15/deep-learning-hydroponics-and-medical-marijuana/) by Adrian Rosebrock








