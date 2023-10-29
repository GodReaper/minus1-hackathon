# Synthetic Indian Road Dataset Generation using Diffusion Models 🛣️🚗

## Project Overview
This repository contains code for generating a synthetic Indian road dataset using diffusion models. The project involves creating photorealistic images of Indian roads with potholes, crowds, and cars using a diffusion-based generative model. The generated dataset can be used for various computer vision tasks, such as object detection and segmentation.

## Challenges
### Challenge 1: Creating Synthetic Indian Road Dataset 🌟
The main challenge of this project was to create a synthetic dataset that accurately represents Indian roads. This involved generating images with realistic road conditions, including potholes, diverse crowds, and different types of vehicles.

## Code Overview
The project is implemented using Python and PyTorch. Here's an overview of the key components of the code:

- **Diffusion Model Setup**: The code sets up a diffusion model using the `diffusers` library and loads a pre-trained model for image generation.
- **Indian Roads Dataset**: The Indian roads dataset is downloaded using the `opendatasets` library. The dataset contains diverse images of Indian roads.
- **Data Preprocessing**: The dataset is preprocessed and transformed into appropriate formats for training the generative model.
- **Generator and Discriminator Networks**: The generator and discriminator networks are defined using convolutional neural networks (CNNs) in PyTorch. These networks are trained adversarially to generate realistic road images.
- **Training Loop**: The training loop consists of training the discriminator and generator networks iteratively to improve the quality of generated images.
- **Image Generation**: The trained generator is used to generate synthetic Indian road images, which are saved for evaluation and use.

## How to Use
1. **Clone the Repository**:
git clone https://github.com/username/synthetic-indian-road-dataset.git
cd synthetic-indian-road-dataset

2. **Install Dependencies**:
  Use the provided google collab jupyter notebooks to install dependencies


3. **Download the Pre-trained Model**:
Download the pre-trained diffusion model from the Hugging Face model hub and place it in the project directory.

4. **Download and Preprocess Dataset**:
Run the notebook or script to download the Indian roads dataset, preprocess the images, and create the data loaders.

5. **Training**:
Train the generator and discriminator networks using the provided training loop. Adjust hyperparameters as needed.

6. **Generate Images**:
Use the trained generator to generate synthetic Indian road images by providing appropriate prompts.

## Results
Below are some generated images showcasing the diversity and realism achieved by the generative model:

![6954915200](https://github.com/GodReaper/minus1-hackathon/assets/147949773/3b51c47a-1082-4684-bff1-09a245da18c3)
![7213717958](https://github.com/GodReaper/minus1-hackathon/assets/147949773/b48e1ecc-55e6-4184-ae1d-ee4e9eb5
![6877356977](https://github.com/GodReaper/minus1-hackathon/assets/147949773/c9c85be3-4cec-477a-90a2-89777b1a5b9f)
baf2)
![6886853693](https://github.com/GodReaper/minus1-hackathon/assets/147949773/26849b3d-3d5d-4933-9d96-0670e907bb76)
![3824581663](https://github.com/GodReaper/minus1-hackathon/assets/147949773/45027eb8-d7c2-4d42-ad52-88bce88fedaa)




## Acknowledgments 🙌
- Thanks to the [diffusers](https://github.com/stabilityai/diffusers) library for providing the stable diffusion model.
- The Indian roads dataset used in this project is sourced from [Kaggle](https://www.kaggle.com/datasets/mitangshu11/indian-roads-dataset).

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Feel free to contribute, report issues, and use the generated dataset for research and development purposes. Happy coding! 🚀
