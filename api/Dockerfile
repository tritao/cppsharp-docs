FROM caddy:latest

# Set the working directory inside the container
WORKDIR /data

# Copy the folder of files into the container
COPY ./*.md /data
COPY ./api/ /data/api/

# Expose the default Caddy HTTP port
EXPOSE 80

# Start Caddy to serve the static files
CMD ["caddy", "file-server", "--browse", "--root", "/data"]
