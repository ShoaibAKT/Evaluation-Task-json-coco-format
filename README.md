# Evaluation-Task-json-coco-format
You are required to convert VGG formatted JSON annotations file into COCO format. Additionally you are have to augment that images.

1. Fetch an image and data from VGG formatted JSON annotations

2. Load that image

3. Resize that image from resize scale percentage 60 to 100 randomly. Thats mean the resulting images will be between 60% to 100% of original size. Do forget to adjust the bounding boxes according to new resized image.

4. Add random brightness to that resized image.

5. Rotate that brighter image on an angle n. Don't forget to adjust bounding boxes according to the angle.

6. Save the resulting image on disk

7. Repeat step 3 to 6 for angles 0, 5, 10, 15, 20, ....., 350 and 355

8. Repeat step 1 to 7 for all remaining images too

9. Save the new annotations on disk.

You may follow the flow chart (flow_diagram.png is attached)

For testing you can use cat_dog.zip and for cat_dog.zip as input to your solution, your output should have exactly 504 images and 1 annotations json file. 
