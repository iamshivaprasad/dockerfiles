ARG VERSION
FROM almalinux:${VERSION:-9}
ARG course=docker \
    trainer=shiva \
    author=shiva
 RUN echo "Course: ${course}, Trainer: ${trainer}, Author: ${author}, Version: ${VERSION}"
 CMD ["sleep", "infinity"] # This command keeps the container running indefinitely, allowing us to inspect the environment variables when we run the container.