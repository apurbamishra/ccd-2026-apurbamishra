
# 1. Use the official lightweight Python image
FROM python:3.11-alpine

# 2. Set the working directory inside the container
WORKDIR /app

# 3. Copy our Python server into the container
COPY server.py .

# 4. Document the port used by our web server
EXPOSE 8080

# 5. Start the Python web server
CMD ["python", "server.py"]
