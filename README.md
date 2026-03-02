# p6m7g8-actions/gh-token-normalize

- [p6m7g8-actions/gh-token-normalize](#p6m7g8-actionsgh-token-normalize)
  - [Usage](#usage)

## Usage

```yml
    - name: Normalize GitHub token
      id: token
      uses: p6m7g8-actions/gh-token-normalize@main
      with:
        preferred-token: ${{ inputs.git_token }}
        fallback-token: ${{ inputs.gh_token }}
        default-token: ${{ github.token }}
```
