# DeepSeek-LLamaCpp

DeepSeek-LLamaCpp is a project that integrates DeepSeek models with the llama.cpp framework, enabling efficient inference of large language models (LLMs) in C/C++ environments. This integration facilitates running DeepSeek models on various hardware configurations with minimal setup.

## Features

- **Efficient Inference**: Leverages the optimized performance of llama.cpp for running DeepSeek models.
- **Hardware Flexibility**: Supports a wide range of hardware, including CPUs and GPUs, ensuring adaptability to different environments.
- **Minimal Dependencies**: Built with minimal external dependencies, simplifying installation and deployment processes.

## Prerequisites

Before setting up DeepSeek-LLamaCpp, ensure you have the following installed:

- **Python**: Version 3.7 or higher, for running auxiliary scripts and tools.

## Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/RafaelXokito/deepseek-llamacpp.git
   cd deepseek-llamacpp
   ```

2. **Set Up the Environment**:

   - **Using Conda**:

     ```bash
     conda env create -f conda_environment.yml
     conda activate deepseek-llamacpp
     ```

   - **Using pip**:

     ```bash
     pip install -r requirements.txt
     ```

## Usage

The project includes several Jupyter notebooks to assist with indexing and querying:

- **Graph Indexer** (`graph_indexer.ipynb`): For creating graph-based indices.
- **Vector Indexer** (`vector_indexer.ipynb`): For creating vector-based indices.
- **Query** (`query.ipynb`): For querying the indices.

To use these notebooks:

1. **Launch Jupyter Notebook**:

   ```bash
   jupyter notebook
   ```

2. **Open the Desired Notebook**: Navigate to the notebook of interest and follow the instructions within.

## Configuration

The project uses environment variables for configuration. Copy the example environment file and modify it as needed:

```bash
cp .env.example .env
```

Edit the `.env` file to set your configuration parameters.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [llama.cpp](https://github.com/ggerganov/llama.cpp): For providing the foundational framework for LLM inference in C/C++.
- [DeepSeek](https://github.com/deepseek-ai): For developing the DeepSeek models integrated into this project.

For more information on DeepSeek models and their integration with llama.cpp, refer to the [llama.cpp repository](https://github.com/ggerganov/llama.cpp) and the [DeepSeek AI organization](https://github.com/deepseek-ai). 
