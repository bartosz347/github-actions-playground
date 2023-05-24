# GitHub Actions playground

TEST

This is a demo repository for various GitHub Actions workflows.
Currently the following scenarios are implemented:
 - `commit.yml` – committing files to the repository. 
 - `simple-workflow-demo.yml` – simple workflow triggered by push and pull request, presenting the possibility to ignore changes in certain files. 
 - `containers.yml` – creating containers in a declarative way and accessing them directly and from steps run in container.
 - `test.yml` – executing steps despite failure of a previous step. 
 - `push-to-branch.yml` – a manually run workflow that pushes to a branch and triggers `on-push.yml`
