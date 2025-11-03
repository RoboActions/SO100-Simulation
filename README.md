# SO100 Simulation

This repository contains the SO100 simulation environments bundled as a Python package (`gym-so100`).

## From-Scratch Setup with uv

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-org/SO100-Simulation.git
   cd SO100-Simulation
   ```

2. **Install uv (if not already installed)**

   Follow the instructions at [https://astral.sh/uv](https://astral.sh/uv). For macOS/Linux you can use:

   ```bash
   curl -Ls https://astral.sh/uv/install.sh | sh
   ```

   Ensure `uv` is on your `PATH` (restart your shell or `source ~/.profile` if necessary).

3. **Install Python 3.10 via uv**

   ```bash
   uv python install 3.10
   ```

4. **Create and activate a virtual environment**

   ```bash
   uv venv --python 3.10 .venv
   source .venv/bin/activate
   ```

5. **Install project dependencies**

   ```bash
   uv pip install -e .
   ```

6. **Run the example script**

   ```bash
   python scripts/example.py
   ```

