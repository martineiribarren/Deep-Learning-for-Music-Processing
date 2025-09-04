# Deep Learning for Music Processing - Course Portfolio

This repository serves as a comprehensive portfolio for the "Deep Learning for Music Processing" course (SoSe 2025), taught by Ph.D. Ulf Krumnack. It encapsulates all practical implementations, analyses, and conceptual explorations covered throughout the curriculum, demonstrating an end-to-end understanding of modern AI applications in music.

## Project Overview

This repository is designed to showcase the practical application of deep learning techniques to various facets of music processing, from fundamental audio analysis to advanced generative models. It includes:

* **Interactive Notebooks**: Jupyter/Google Colab notebooks providing hands-on implementations and detailed explanations of core concepts, model architectures, and experimental results.
* **Code Implementations**: Python scripts and modules for tasks such as audio feature extraction, data preprocessing, model training, and inference.
* **Model Analysis**: Critical evaluations of AI models (e.g., MusicGen) focusing on their capabilities, limitations, and the nuances of human-machine interaction in creative processes.
* **Deployment Prototypes**: (Optional) Examples of how some models or analyses could be deployed as web applications or APIs for interactive use.
* **Generated Audio Samples**: A collection of audio outputs from various models and experiments conducted during the course, serving as tangible results of the implementations.
* **Resource Management**: Configuration files (`requirements.txt`, `Dockerfile`) to ensure reproducibility and ease of environment setup for all projects.

## Course Topics Covered

The materials in this repository address key topics in deep learning for music, including but not limited to:

* **Audio Feature Engineering**: Techniques for extracting meaningful features from raw audio signals (e.g., pitch, tempo, dynamics, spectrograms).
* **Conditional Music Generation**: Exploration of models like MusicGen and the theoretical and practical challenges of controlling AI-generated music.
* **Model Architectures**: Understanding transformer-based models, diffusion models, and their application to audio synthesis.
* **Evaluation Metrics**: Implementation and discussion of metrics for assessing the quality, controllability, and realism of generated audio.
* **Human-Machine Interaction**: A critical perspective on how AI tools influence and redefine creative workflows in music production.

## Getting Started

To explore the content of this repository:

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/martineiribarren/Deep-Learning-for-Music-Processing.git
    cd Deep-Learning-for-Music-Processing
    ```
    
2.  **Set up the environment**:
    It is highly recommended to use Google Colab for a quick setup, especially for notebooks requiring GPU access. Look for the "Open in Colab" badges within the `notebooks/` directory.

    Alternatively, for a local setup, install dependencies:
    ```bash
    pip install -r requirements.txt
    # And install ffmpeg manually if not already present on your system
    # For Debian/Ubuntu: sudo apt install ffmpeg
    ```

3.  **Navigate the notebooks**:
    Explore the `notebooks/` directory to find interactive examples and detailed analyses.

## Contributing

This repository serves as my personal portfolio. Feedback, suggestions, and bug reports are really welcome. Feel free to open an issue or submit a pull request!
