# License Plate Recognition 🚗

![](./license_detection.gif)

## License Plate Detection and Extraction with YoloV8 and EasyOCR

Using both the `COCO Model` to detect the vehicles and the `License Plate Model` to recognize the plate, and then with EasyOCR to extract the info from the cropped plate image.


## Check-it out
Test it by running the `app.py` file, built with `Streamlit`.

## Add Folder
Create and Add Models floder and  Inside that folder keep best.pt for Number plate or Licence plate detection file and yolov8.pt file chose which ever model you want to use for care detection you can also make custome model for care detection

## Run
```sh
streamlit run app.py
```

## Resources
- Licenses Plates Dataset: https://universe.roboflow.com/roboflow-universe-projects/license-plate-recognition-rxg4e/dataset/4
