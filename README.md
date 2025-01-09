# My Django Project

## Setup Instructions

### Prerequisites

- Python 3.12
- pip
- virtualenv

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yourusername/your-repo.git
   cd your-repo
   
    ```powershell
      git clone https://github.com/yourusername/your-repo.git
      cd your-repo


2. **Create and activate a virtual environment**:

    ```bash
    python3 -m venv venv 
    source venv/bin/activate

    ```powershell  
      python -m venv venv
      .\venv\Scripts\Activate


3. **Install dependencies**:

   ```bash
   pip install -r requirements.txt

    ```powershell  
    pip install -r requirements.txt


4. **Run migrations**:

   ```bash
   python manage.py makemigrations 
   python manage.py migrate


    ```powershell  
      python manage.py makemigrations
      python manage.py migrate



5. **Run The development server**:

   ```bash
    python manage.py runserver

    ```powershell  
      python manage.py runserver

