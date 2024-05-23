FROM maven:3.6

# Add your files
COPY entrypoint.sh /entrypoint.sh

# Ensure the entrypoint script is executable
RUN chmod +x /entrypoint.sh

ENTRYPOINT ["/entrypoint.sh"]
