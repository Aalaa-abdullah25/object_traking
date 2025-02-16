# Object Tracking Application


![header_mots]([https://github.com/user-attachments/assets/2bf53fbc-544a-4087-85c9-fcbc73a919b5](https://camo.githubusercontent.com/49a959cf8e98786d0653c286ecbab962b0c1e3e45ad7cbd1d6ef618c20d90100/68747470733a2f2f692e6962622e636f2f374e79726d304a2f6f626a6563742d747261636b696e672d66726f6d2d736372617463682d6f70656e63762d616e642d707974686f6e2d6f626a6563742d646574656374696f6e2d776974682d796f6c6f2d373638783634382e706e67))


This project is an object tracking application that uses OpenCV and Streamlit to process and display video files with object tracking.

## Features

- Upload video files in MP4, AVI, or MOV format.
- Apply background subtraction to detect moving objects.
- Draw bounding boxes around detected objects.
- Display the processed video frames in a web interface.

## Requirements

- Python 3.x
- OpenCV
- Streamlit
- NumPy

## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/yourusername/Object_tracking_project2.git
   cd Object_tracking_project2
   ```

2. Install the required packages:
   ```sh
   pip install -r requirements.txt
   ```

## Usage

1. Run the application:

   ```sh
   streamlit run app.py
   ```

2. Open your web browser and go to `http://localhost:8501`.

3. Upload a video file and see the object tracking in action.

## File Structure

- [app.py](http://_vscodecontentref_/0): Main application file.
- [README.md](http://_vscodecontentref_/1): Project documentation.
- [.gitattributes](http://_vscodecontentref_/2): Git configuration file.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements

- [OpenCV](https://opencv.org/)
- [Streamlit](https://streamlit.io/)
- [NumPy](https://numpy.org/)

## Demo

This project is deployed [HERE](https://objecttrackingproject2.streamlit.app/)
