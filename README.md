# docker-retag-push-latest

Re-tags image:sha to image:latest and pushes it back to the registry.

## Usage

```yaml
- uses: beeper/docker-retag-push-latest@main
  with:
    image: ${{ env.CI_REGISTRY_IMAGE }}
```
