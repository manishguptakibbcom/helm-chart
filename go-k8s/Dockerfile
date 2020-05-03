
# Start from the latest golang base image

FROM golang:alpine

# Add Maintainer Info
LABEL maintainer="abcd"

# Set the Current Working Directory inside the container
WORKDIR /app


# Copy the source from the current directory to the Working Directory inside the container
COPY app-code/http-sample /app/http-sample

# Expose port 8080 to the outside world
EXPOSE 3000

# Command to run the executable
CMD ["/app/http-sample"]




