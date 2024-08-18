# Basic PDF RAG using locally running Ollama Mistral model

## Getting Started

### Prerequisites

- [Conda](https://docs.conda.io/en/latest/miniconda.html) installed on your system.
- Python 3.10 or above.
- [Ollama](https://ollama.com/) installed on your system.

### Setup

1. **Clone the repository**

   ```bash
   git clone https://github.com/oracleArch/basic_rag.git
   cd basic_rag
   ```

2. **Create a new Conda environment**

   ```bash
   conda create -p venv python=3.10
   ```

3. **Activate the Conda environment**

   ```bash
   conda activate /path/to/myenv
   ```

4. **Install the required packages**

   ```bash
   pip install -r requirements.txt
   ```

5. **Download the Mistral model using Ollama**

   ```bash
   ollama pull mistral
   ```

6. **Run the Jupyter Notebook**