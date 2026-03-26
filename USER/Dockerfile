FROM almalinux:9
RUN dnf install nginx -y
RUN useradd sivakumar

user sivakumar
CMD ["sleep", "infinity"] # This command keeps the container running indefinitely, allowing us to inspect the user when we run the container.