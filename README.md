## Steps to Set Up a Python Environment

1. **Install Python (only Version 3.11.XXX)**

2. **Create and Activate a Virtual Environment in Python**

    a. **Create a Folder for Your Project and Navigate to It:**
    
       ```
       cd tutorial
       ```

    b. **Create a Virtual Environment:**
    
       - **macOS:**
       
         ```
         python3 -m venv virenv
         ```
         
       - **Windows:**
       
         ```
         python -m venv virenv
         ```

    c. **Update pip Version:**
    
       ```
       pip install --upgrade pip
       ```

    d. **Activate the Virtual Environment:**
    
       - **macOS/Linux:**
       
         ```
         source virenv/bin/activate
         ```
       
       - **Windows:**
       
         ```
         virenv\Scripts\activate
         ```
