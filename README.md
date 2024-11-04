# Image Classification: Dog Breed Project

This project was developed by Udacity as part of the AI Programming with Python Nanodegree program.

## Getting Started

Follow the steps below to set up and run the project.

### Prerequisites

Make sure you have Python installed on your system. You will also need to install the following packages:

```bash
pip install torch torchvision Pillow==7.1.2
```

### Set Up a Local Virtual Environment

1. **Create a virtual environment**:
   ```bash
   virtualenv venv
   ```

2. **Activate the virtual environment**:
   ```bash
   source venv/bin/activate
   ```

3. **Deactivate the environment** when you're done:
   ```bash
   deactivate
   ```

### Navigate to the Application Folder

Change to the application directory:

```bash
cd intropyproject-classify-pet-images
```

### Run the Application

To run the application using a single CNN architecture model, execute the following command:

```bash
python check_images.py --dir pet_images/ --arch vgg --dogfile dognames.txt
```

### Run the Application with All CNN Models

To execute the application on the `pet_images` folder with all three CNN architecture models and print the results, use:

```bash
sh run_models_batch.sh
```

To run the application on the `uploaded_images` folder with all three CNN models and print the results, use:

```bash
sh run_models_batch_uploaded.sh
```

