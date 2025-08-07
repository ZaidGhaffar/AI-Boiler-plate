# Project Name
![tech-stack](AI-tech.webp)

this is a boilerplate for AI projects, which includes a basic structure for organizing your code, configuration files, and model architecture. It is designed to be easily extendable and reusable across different AI projects.
# Features
- **Modular Structure**: The project is organized into separate directories for source code, configuration files, and model architecture, making it easy to navigate and maintain.
- **Configuration Management**: Configuration files are stored in the `Config` directory, allowing for easy adjustments to model and training parameters without modifying the code.
- **Model Architecture**: The `src/model_archi.py` file contains the model architecture, which can be easily imported and reused in different parts of the project. 
- **AWS Integration**: The `aws` directory contains scripts for deploying the model to AWS, making it easy to scale and manage your AI applications in the cloud.
# Usage
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```  
2. Navigate to the project directory:
   ```bash
   cd AI-Project-boilerplate
   ```
3. Install the required dependencies:
   ```bash
    pip install -r requirements.txt
    ```
4. Modify the configuration files in the `Config` directory to suit your project needs.
5. Run the model architecture script:
   ```bash
   python src/model_archi.py
   ```  
6. For AWS deployment, navigate to the `aws` directory and run the main script:
   ```bash
   python main.py
   ```

# Deleting git files
If you need to delete git files, you can use the following command:
```bash
Remove-Item -Recurse -Force .git
```


# Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue if you find any bugs or have suggestions for improvements.
# License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.   
