# Setting up a Python Django Project

## Step 1: Create a Virtual Environment
```bash
# On Windows
python -m venv myenv

# Activate the virtual environment
myenv\Scripts\activate

# On Linux/Mac
python3 -m venv myenv

# Activate the virtual environment
source myenv/bin/activate

# Navigate to the project folder
cd path/to/your/project

# Install project dependencies
pip install -r requirements.txt

# Run Django development server
python manage.py runserver
