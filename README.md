# Dockerfile Build Error: No such file or directory

This repository demonstrates a common error when building Docker images: attempting to copy a file that doesn't exist in the build context.

The `Dockerfile` attempts to copy `requirements.txt`, which is missing.

The `DockerfileSolution` provides the correct solution.