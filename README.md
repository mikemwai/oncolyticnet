# Oncolyticnet

This project aims to develop a machine learning model for detecting brain tumors from MRI scans using the VGG-19 architecture with transfer learning and data augmentation techniques to fine-tune the pre-trained model, enabling accurate and reliable brain tumor detection.

## Installation

1. Clone the repository:
    ```
    git clone https://github.com/mikemwai/oncolyticnet.git
    ```
2. Navigate to the project directory:
    ```
    cd oncolyticnet
    ```
3. Install the required packages:
    ```
    pip install -r requirements.txt
    ```

## Usage

- Run the following command to start the application:

  - On Windows:

    ```sh
        set FLASK_APP=app.py
        flask run
    ```

  - On Unix/Linux/Mac:

    ```sh
        export FLASK_APP=app.py
        flask run
    ```

- This will start a development server on http://127.0.0.1:5000/ where you can access the application.

## Dataset

- The dataset used for this project can be downloaded [here](https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection) or extract it from [here](dataset.zip).
  
- An additional dataset for image validation was downloaded from [here](https://www.kaggle.com/datasets/pankajkumar2002/random-image-sample-dataset?resource=download).
  
- The image validation model and detection model can be downloaded from [here](https://drive.google.com/drive/folders/1300P6O28YW1X2c6jmZ5Nai7jhdLcnIZT?usp=sharing).

## Contributions

If you'd like to contribute to this project:

- Please fork the repository.
- Create a new branch for your changes.
- Submit a [pull request](https://github.com/mikemwai/oncolyticnet/pulls).

Contributions, bug reports, and feature requests are welcome!

## Issues

If you have any issues with the project, feel free to open up an [issue](https://github.com/mikemwai/oncolyticnet/issues).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
