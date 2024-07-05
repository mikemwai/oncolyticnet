# Oncolyticnet

This project develops a machine learning system for detecting brain tumors from MRI scans using the VGG-19 architecture with transfer learning and data augmentation techniques to fine-tune a pre-trained model, enabling accurate and reliable brain tumor detection.

## Installation

Install project dependencies on your virtual environment:

```sh
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

The dataset used for this project can be downloaded [here](https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection) or extract it from [here](dataset.zip).
An additional dataset for image validation was downloaded from [here](https://www.kaggle.com/datasets/pankajkumar2002/random-image-sample-dataset?resource=download).
The image validation model can be downloaded from [here](https://drive.google.com/drive/folders/1AJeFVIDUZvvbtH9iNxcm4PT5nBoyWEjL).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
