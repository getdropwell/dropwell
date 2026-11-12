# Labels

The issue forms set `bug` or `feature`. The other 2 are set by hand when an issue is triaged.

| Label | Color | Description |
| --- | --- | --- |
| `bug` | `d73a4a` | Something in Dropwell does not work as it should |
| `feature` | `0e8a16` | An idea or a request for something new |
| `bank-statement` | `1d76db` | About reading or exporting a bank statement layout |
| `needs-info` | `fbca04` | Waiting for details from the person who opened the issue |

Create them (or update them to these colors and descriptions; `--force` changes a label that already exists, such as GitHub's default `bug`):

```sh
gh label create bug --repo getdropwell/dropwell --color d73a4a --description "Something in Dropwell does not work as it should" --force
gh label create feature --repo getdropwell/dropwell --color 0e8a16 --description "An idea or a request for something new" --force
gh label create bank-statement --repo getdropwell/dropwell --color 1d76db --description "About reading or exporting a bank statement layout" --force
gh label create needs-info --repo getdropwell/dropwell --color fbca04 --description "Waiting for details from the person who opened the issue" --force
```

GitHub's other default labels (`documentation`, `duplicate`, `enhancement`, `good first issue`, `help wanted`, `invalid`, `question`, `wontfix`) can stay or go. `enhancement` and `good first issue` do not fit a closed source app; to remove them:

```sh
gh label delete enhancement --repo getdropwell/dropwell --yes
gh label delete "good first issue" --repo getdropwell/dropwell --yes
gh label delete "help wanted" --repo getdropwell/dropwell --yes
```
