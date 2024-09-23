# Virtual Environment Setup
To set up and activate a virtual environment called `case-env`, follow these steps:

1. **Navigate to your project directory:**
    ```sh
    cd ~/codeway
    ```

2. **Create the virtual environment:**
    ```sh
    python3 -m venv case-env
    ```

3. **Activate the virtual environment:**

    - On macOS and Linux:
        ```sh
        source case-env/bin/activate
        ```
    - On Windows:
        ```sh
        .\case-env\Scripts\activate
        ```

4. **Install dependencies from `requirements.txt`:**
    ```sh
    pip install -r requirements.txt
    ```

5. **Run Jupyter Notebook:**
    ```sh
    jupyter notebook
    ```

6. **Deactivate the virtual environment when done:**
    ```sh
    deactivate
    ```

Now your virtual environment `case-env` is set up and ready to use!