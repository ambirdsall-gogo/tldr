# gh run

> View, run and watch recent workflow runs from GitHub Actions.
> More information: <https://cli.github.com/manual/gh_run>.

- View the latest workflows, interactively select a workflow to see information about the jobs:

`gh run view`

- Display information about a specific workflow:

`gh run view {{workflow_number}}`

- Display information about the steps of a specific job:

`gh run view --job={{job_number}}`

- Display the log of a specific job:

`gh run view --job={{job_number}} --log`

- Rerun a specific workflow:

`gh run rerun {{workflow_number}}`

- Check workflow and exit with non-zero status if run failed:

`gh run view {{workflow_number}} --exit-status && echo "run pending or passed"`
