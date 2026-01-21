# Kopia

A self-hosted kopia application.

## Installation

### Option 1: Quick Install
```bash
curl -q -LSsf "https://raw.githubusercontent.com/composemgr/kopia/main/docker-compose.yaml" | docker compose -f - up -d
```

### Option 2: Git Clone
```bash
git clone "https://github.com/composemgr/kopia" ~/.local/srv/docker/kopia
cd ~/.local/srv/docker/kopia
docker compose up -d
```

### Option 3: Using composemgr
```bash
composemgr install kopia
```

## Configuration

See docker-compose.yaml for environment variables and configuration options.

## Documentation

Check the official project documentation for detailed setup and usage information.
