# Use an official lightweight image as a base (Alpine is small and efficient)
FROM alpine:3.18

# Define a build argument with a default value
ARG NAME="World"

# Make the build argument accessible as an environment variable
ENV NAME=${NAME}

# Set the command to print "Hello {build arg}" when the container is run
CMD echo "Hello ${NAME}"