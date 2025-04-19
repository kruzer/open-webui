Steps to build:
- frontend
    - npm ci
    - npm run build
- backend and run:
    - uv venv
    - FRONTEND_BUILD_DIR=build GLOBAL_LOG_LEVEL="DEBUG" uv run open-webui serve --port 8888