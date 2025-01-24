# To Reinstall Virtual Environment And Dependencies After Pulling:

1. Navigate to the parent folder containing the Django project and app.
2. Create a new virtual environment by running "py -m venv myenv"
   (Replace "myenv" with the desired name of your virtual environment).
3. Activate the virtual environment by running "myenv\Scripts\activate.bat" in your terminal.
4. Then, Run the command "pip install -r requirements.txt" in your terminal to reinstall the required dependencies.
5. Also, Run the command "py manage.py collectstatic" in your terminal to recollect all the static files.
