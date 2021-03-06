# Requirements  
* Python>=3.7.0  
* tensorflow==2.8.0  
* pip install -r requirements.txt

# Dataset
The dataset is available on download [here](https://www.kaggle.com/datasets/kritikseth/fruit-and-vegetable-image-recognition)

# Train
`python train.py --path path/to/dataset --epochs 12 --model_dir path/for/model`
### Parameters:
* path: path to dataset  
* epochs: number of epochs  
* model_dir: path where weights will be saved

# Test
`python test.py --path path/to/dataset --model path/for/trained/model`      
The result on test data will be printed.
### Parameters:
* path: path to dataset  
* model: path to model

# Inference
`python inference.py --image path/to/image --model path/for/trained/model`  
The result of inference will be printed.
### Parameters:
* image: path, image from dataset  
* model: path to model

# 2D images projections
`python image_projection.py --path path/to/data --model path/for/trained/model`  
The resulted image will be shown on a new window.
### Parameters:
* path: path to test data, or data which will be projected   
* model: path to model

# Flask
`cd flask`  
`python run.py --path path/for/trained/model`
### Parameters:
* path: a required path to weights   

# Results
Refer to [youtube](https://youtu.be/-pc2rZE890k).
### Test
| Name          | Test accuracy | Model  |
| ------------- |:-------------:| -----: |
| ResNet50      | 0.9821        | [model](https://drive.google.com/file/d/1_KYOiTaZ3MHnKI_Ee3pru1RvXhp2YsUt/view?usp=sharing)  |

### Images projections
![Canvas](media/images/mess.png)
