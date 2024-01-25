# Base image with Python 3.12
FROM python:3.12

# Working directory
WORKDIR /app

# Install dependencies
RUN pip install -U pip wheel
RUN pip install -U anl>=0.1.6

# Copy remaining project files
COPY . .

# expose anlv port
EXPOSE 8501


