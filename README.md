# Number_plate_recognition_system
Detect ,Recognition and extract number from vehicle number plate with current time.


Objective:
Client try to analyse howmuch time the vehicle stay at his place including time IN and Out, finally differemce bw them.

Implementation Module:
1. Yolov8 for medium.
2. OCR technique.
3. Timetable module.
4. SQL
5. Nvidia GPU

Working Steps:
1. Collecting buch of images in different angle of vehicle.
2. Annotated the image using makesense.ai tools.
3. Train the model for detected the number plate.
4. Implement OCR for cropped and extract the text from Number Plate Images.
5. Store Number text into SQL database with time.
6. Repeat same for backside of vehicle number plate with time.
7. Find difference bw time. This is Final objective. 
