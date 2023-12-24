# Dockerfile
FROM python:3.10.7

ENV PYTHONUNBUFFERED=1
WORKDIR /djangocalc

# Copy the project files
COPY . .

# Install dependencies
RUN pip3 install -r requirements.txt

# Expose port
EXPOSE 8000

# Command to run the application
CMD ["python", "manage.py", "runserver", "0.0.0.0:8000"]