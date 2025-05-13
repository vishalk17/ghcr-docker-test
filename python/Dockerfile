# Use Python image
FROM python:3.10-slim

# Set working directory
WORKDIR /app

# Create a basic HTTP server (optional)
RUN echo "Hello from Python HTTP server!" > index.html

# Expose port 8000
EXPOSE 8000

# Start long-running Python server
CMD ["python3", "-m", "http.server", "8000"]
