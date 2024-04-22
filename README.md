# Setting Up a Python Project from a Git Repository

Follow these steps to set up a Python project from a Git repository and install its dependencies:

1. **Clone the Repository**: Use the `git clone` command to clone the repository to your local machine:
```sh
git clone <repository-url>
```
2. **Navigate to the Project Directory**: Use `cd` to navigate into the directory of the cloned repository:
```sh
cd <repository-directory>
```
3. **Create a Virtual Environment**: Create a new virtual environment using either `venv` or `virtualenv`:
- Using `venv`:
  ```sh
  python3 -m venv venv  # Create a virtual environment named 'venv'
  ```
- Using `virtualenv`:
  ```sh
  virtualenv venv  # Create a virtual environment named 'venv'
  ```

4. **Activate the Virtual Environment**: Activate the virtual environment. The method depends on your operating system:
- For Unix/Linux:
  ```sh
  source venv/bin/activate
  ```
- For Windows:
  ```sh
  venv\Scripts\activate
  ```

5. **Install Dependencies**: Once the virtual environment is activated, install the dependencies listed in the `requirements.txt` file using `pip`:
```sh
pip install -r requirements.txt
```
Now your Python project is set up with its dependencies installed in a virtual environment!

Remember to deactivate the virtual environment when you're done working on the project:

Now your Python project is set up with its dependencies installed in a virtual environment!

Remember to deactivate the virtual environment when you're done working on the project:
```sh
deactivate
```
