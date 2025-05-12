# real-time-etl
## Local Development

### Using Docker (recommended)
```bash
# Build and start the containers
docker-compose up --build

# To run in detached mode
docker-compose up -d

# To stop the containers
docker-compose down
```

### Using Virtual Environment
```bash
# Install system dependencies first
brew install postgresql openssl python@3.11

# Create and activate virtual environment
python3.11 -m venv .venv
source .venv/bin/activate

# Install requirements
pip install --upgrade pip wheel setuptools
pip install -r requirements.txt
```