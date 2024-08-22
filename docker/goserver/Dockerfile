FROM debian:stable-slim

# Copy source destination
COPY goserver /bin/goserver

# Set the port
ENV PORT=8080

# Run the server
CMD ["/bin/goserver"]
