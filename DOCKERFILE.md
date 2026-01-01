The dockerfile downloads requirements from the requirements.txt file 
and runs the app using the CMD command ["streamlit", "run", "main.py", "--server.port=8080", "--server.address=0.0.0.0"]