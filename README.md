### Steps to Set Up a Python Environment

1. **Install Python (only Version 3.11.XXX)**

2. **Create and Activate a Virtual Environment in Python**

    a. **Create a Folder for Your Project and Navigate to It:**
    
       ```bash
       cd tutorial
       ```

    b. **Create a Virtual Environment:**
    
       - **macOS:**
       
         ```bash
         python3 -m venv virenv
         ```
         
       - **Windows:**
       
         ```bash
         python -m venv virenv
         ```

    c. **Update pip Version:**
    
       ```bash
       pip install --upgrade pip
       ```

    d. **Activate the Virtual Environment:**
    
       - **macOS/Linux:**
       
         ```bash
         source virenv/bin/activate
         ```
       
       - **Windows:**
       
         ```bash
         virenv\Scripts\activate
         ```
