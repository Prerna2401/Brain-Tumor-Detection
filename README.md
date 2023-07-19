# Brain-Tumor-Detection
This project is a basic web application to detect whether a given patient has a brain tumour based on the uploaded MRI image sample. It has been implemented using Flask.

**Follow these Steps to run the project on your system**
  1. Clone or Download the zip file of this repository.
  2. Open the terminal/CMD in project directory
  3. Then create virtual environment using this command: 
      ```py -m venv env```
     
     If you face an error at this point(errno 13), delete the python application file in the Scripts directory of the env folder. That should resolve the issue.
     If not, change the permissions granted to users on the security tab by clicking on properties of the folder where you have stored this project.
  5. Activate virtual environment using: 
      ```env\Scripts\activate```
     
  7. Install all the requirements using: 
      ```pip install -r requirements.txt``` 
      
  8. After successful download of all the above requirements, run the app using
      ``` flask run ```
      
      Wait for few seconds till it shows like : ```Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)```
   9. Then open this URL in browser: http://127.0.0.1:5000/
