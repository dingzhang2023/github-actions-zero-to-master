# github-actions-zero-to-master

```yaml
name: First Workflow
on: workflow_dispatch # This is a manual trigger
jobs: # This is a list of jobs
    first-job: # This is the name of the job
        runs-on: ubuntu-latest # This is the OS
        steps: # This is a list of steps
            - name: Print greeting
              run: echo "Hello, world!" # This is the command to run
            - name: Run multi-line script
              run: |
                  echo "Goodbye, world!"
                  echo "Second output!"
```
