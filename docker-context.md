docker build -t gcr.io/gcp-atif/game-2048:$GITHUB_RUN_ID .
docker push gcr.io/gcp-atif/game-2048:$GITHUB_RUN_ID
