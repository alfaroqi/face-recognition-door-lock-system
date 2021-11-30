# face-recognition-door-lock-system
this is a simple project of face detection using images that are in the dataset folder or you can also use your face by creating a folder in the dataset using ``python shot.py``

## Hardware
1. Raspberry pi for this test using raspberry pi 4 
2. usb camera
3. relay module
4. selenoid

### clone this repo and install dependencies
``` 
git clone https://github.com/alfaroqi/face-recognition-door-lock-system
cd face-recognition-door-lock-system
pip install -r requirements.txt
```
### make virtualenv
```
virtualenv Env
source Env/bin/activate 
```
or window with :
``` 
virtualenv Env
Env\Scripts\activate
```
### then
```python face_lock.py ``` to use an existing object, notes. to use it first replace the variable name

```python face_shot.py ``` to take a new object face, which then train using ```train_model.py ```

