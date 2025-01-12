# Use a base Go image
FROM golang:1.18.0

# Set the working directory inside the container
WORKDIR /app

# Copy everything from the local directory into the container
COPY . .

# Install Go dependencies
RUN go mod tidy

# Define the command to run when the container starts
CMD ["go", "run", "example/hello.go"]
