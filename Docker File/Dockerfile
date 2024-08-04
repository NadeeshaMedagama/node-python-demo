# Use the official Python image as the base image
FROM python:3.11-slim

# Set the working directory
WORKDIR /app

# Copy the Python script into the container
COPY app.py .

# Install Flask
RUN pip install Flask

# Expose the port that the app runs on
EXPOSE 5000

# Specify the command to run the script
CMD ["python", "app.py"]

