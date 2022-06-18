PROJECT: CAR MODEL DETECTOR

# First
download:
- http://shuoyang1213.me/WIDERFACE/  #### Only Training
- https://www.kaggle.com/datasets/andrewmvd/car-plate-detection
- https://ai.stanford.edu/~jkrause/cars/car_dataset.html
- https://drive.google.com/file/d/1HwEsQn-VK2UyFEaCF8SbYGkZ9O8KoFmP/view?usp=sharing (and unzip directly in working directory)

move all files to:
- datasets/cars/
- datasets/plates/
- datasets/faces/

execute file:
- car_detection.ipynb
- plate_face_detection.ipynb

to test:
- eval_car_detection.ipynb
- eval_plate_face_detection.ipynb
- PLACAS.ipynb
- Face_Matching.ipynb

final code:
- yolov5/p_oficial.py

execute like:
cd yolov5
python3 p_oficial.py --source ../'image_file' --device "cpu" --weights runs/train/yolov5s_results3/weights/best.pt 
