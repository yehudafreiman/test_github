FROM python:3.13
WORKDIR /streamlit_minikube_app

# Install the application dependencies
COPY requirements.txt ./
RUN pip install --no-cache-dir -r requirements.txt

# Copy in the source code
COPY . .
EXPOSE 8080

# Run the program
CMD ["streamlit", "run", "main.py", "--server.port=8080", "--server.address=0.0.0.0"]

