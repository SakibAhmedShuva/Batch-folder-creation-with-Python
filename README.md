# Batch Folder Creation with Python

A simple yet powerful Python script to automate the creation of multiple folders or directories at once. This tool is ideal for quickly setting up project structures, organizing files, or handling any task that requires creating numerous folders from a list.

## ✨ Features

  - **Bulk Creation**: Create multiple folders from a predefined list.
  - **Custom Directory**: Specify a target parent directory for all new folders.
  - **Safe Execution**: Automatically checks if folders already exist to prevent errors.
  - **Clear Logging**: Provides real-time feedback on which folders were created or already exist.
  - **Easy to Customize**: Modify a simple Python list to change the folder names.

-----

## 🚀 Demo

Here is a quick look at the script in action, creating a set of departmental folders in a target directory.

-----

## 📋 Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites

  - **Python 3.x** must be installed on your system. You can download it from [python.org](https://www.python.org/).

### Installation

1.  **Clone the repository** to your local machine:
    ```sh
    git clone https://github.com/SakibAhmedShuva/Batch-folder-creation-with-Python.git
    ```
2.  **Navigate to the project directory**:
    ```sh
    cd Batch-folder-creation-with-Python
    ```

-----

## ⚙️ How to Use

Using the script is straightforward. You only need to edit two variables to fit your needs.

1.  **Open the `folder_creator.ipynb` file** in a Jupyter Notebook environment or convert it to a `.py` script.

2.  **Customize the variables**:

      - `parent_directory`: Change the value of this variable to the path where you want to create the new folders.

    > **Note**: Use a raw string (`r"..."`) or double backslashes (`"\\"`) for Windows paths to avoid issues with escape characters.

      - `bot_folders`: Edit the Python list to include all the folder names you want to create.

    <!-- end list -->

    ```python
    import os

    # 1. SET YOUR PARENT DIRECTORY
    # ---
    # Example for Windows:
    parent_directory = r"F:\Your\Target\Path"
    # Example for macOS/Linux:
    # parent_directory = "/Users/your_user/Desktop/My_Folders"
    # ---

    # 2. DEFINE THE FOLDER NAMES
    # ---
    # Add or remove folder names from this list as needed.
    bot_folders = [
        "Accounts",
        "Finance",
        "Sales",
        "Marketing",
        "Admin",
        "Production",
        "Human Resources",
        "IT_Support"
    ]
    # ---
    ```

3.  **Run the script**. If you are using a `.py` file, run it from your terminal:

    ```sh
    python your_script_name.py
    ```

    The script will then create the specified folders inside the parent directory and print the status of each operation.

-----

## 🤝 Contributing

Contributions are welcome\! If you have suggestions for improving the script, feel free to fork the repository and submit a pull request.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

-----

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
