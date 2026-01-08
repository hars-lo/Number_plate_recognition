Number Plate Recognition

**This project performs automatic license plate detection and recognition on a sample video.

**Sample video link:
https://www.pexels.com/video/traffic-flow-in-the-highway-2103099/

**How it works

The pipeline runs in three steps:

-Detection & OCR
Run main.py with an input video.
This will detect cars and license plates, run OCR, and save results to test.csv.

-Interpolation
Run add_missing_data.py to fill in missing bounding boxes or OCR values.
This generates a new file called test_interpolated.csv.

-Visualization
Finally, run visualize.py.
This overlays the recognized plates on the original video and saves the output.

**Usage

--Place your input video (e.g. sample.mp4) in the project folder.

--Run all three scripts in order as described above.

--The final annotated video will be saved as out.mp4.
