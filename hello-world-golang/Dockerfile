# Use the offical golang image to create a binary.
FROM golang:1.17-buster

# Create and change to the app directory.
WORKDIR /app

#COPY go.* ./
#RUN go mod download

# Copy local code to the container image.
COPY . /app

# Build the binary.
#RUN go build -v -o app

# Expose the port.
EXPOSE 3002

# Run the web service on container startup.
CMD ["go", "run", "app.go"]
