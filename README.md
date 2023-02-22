# Container Deployment Action
GitHub action for deploying updates to a Paperspace container deployment.

This action tracks the deployment of 

## Inputs

### `apiKey`

**Required** Your Paperspace API key.

### `deploymentId`

**Required** The ID of the deployment you are updating.

## Outputs

### `externalApplied`

The time the deployment was updated

### `externalApplied`

The time the deployment was updated

## Example usage

```yaml
uses: paperspace/container-deployment@v1.1
with:
  apiKey: <someApiKey>
  deploymentId: b0e779e5-365f-450f-bd4d-bfeddfbf45b1
```