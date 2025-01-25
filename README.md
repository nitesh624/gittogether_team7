## Deployment

This project uses GitHub Actions to deploy to Netlify. The deployment workflow is defined in [main.yml](.github/workflows/main.yml).

### Workflow

The workflow is triggered on:
- Push to the `main` branch
- Pull request targeting the `main` branch

### Jobs

- **build**: Runs on `ubuntu-latest` and checks out the repository using `actions/checkout@v2`.
