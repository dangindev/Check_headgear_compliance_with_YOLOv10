# Check Headgear Compliance with YOLOv10

This project aims to develop a system that utilizes the YOLOv10 object detection algorithm to check headgear compliance in various scenarios. The system will be able to detect whether individuals are wearing the required headgear, such as helmets or hard hats, in real-time.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction
Headgear compliance is crucial in many industries to ensure the safety of workers. This project leverages the YOLOv10 algorithm, a state-of-the-art object detection model, to detect and classify headgear in images or video streams. By using this system, organizations can automate the process of checking headgear compliance, saving time and improving safety measures.

## Installation
To use this project, follow these steps:

1. Clone the repository: `git clone https://github.com/your-username/check-headgear-compliance.git`
2. Install the required dependencies: `pip install -r requirements.txt`
3. Download the YOLOv10 pre-trained weights: [link to weights]
4. Place the downloaded weights in the `weights/` directory.

## Usage
To run the headgear compliance check, execute the following command:

```
python detect_headgear.py --image path/to/image.jpg
```

Replace `path/to/image.jpg` with the path to the image you want to analyze. The script will output the image with bounding boxes around detected headgear.

## Contributing
Contributions are welcome! If you have any ideas or improvements, please submit a pull request. Make sure to follow the project's coding style and guidelines.

## License
This project is licensed under the [MIT License](LICENSE).
