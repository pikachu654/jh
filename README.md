# Hello docker action

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

### `time`

The time we greeted you.

## Example usage

```yaml
uses: actions/hello-world-docker-action@main
with:
  who-to-greet: 'Mona the Octocat'
```
