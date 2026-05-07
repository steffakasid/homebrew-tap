# Homebrew Tap

Consolidated Homebrew tap for all steffakasid projects.

## Installation

### Add the tap

```bash
brew tap steffakasid/tap
```

### Available Tools

#### awsclean

AWS cleanup tools for stale AMIs and other unused EC2 resources:

```bash
# Install awsclean
brew install steffakasid/tap/awsclean

# Install amiclean (AMI cleanup specific tool)
brew install steffakasid/tap/amiclean
```

**awsclean**: Clean up unused AMIs, unattached EBS volumes, and other stale AWS resources.  
**amiclean**: Remove unused AMIs that are older than a configurable age.

#### dof

Manage dotfiles in a bare Git repository

```bash
brew install steffakasid/tap/dof
```

**dof**: Initialize, sync, and check out dotfiles stored in a bare Git repository.

#### govital

Review Go project dependencies for freshness and maintenance

```bash
brew install steffakasid/tap/govital
```

**govital**: Scan Go dependencies for outdated versions and inactive maintenance.

#### helmfile-dependency-checker (hdc)

Check Helmfile chart dependencies for updates and maintenance status

```bash
brew install steffakasid/tap/hdc
```

**hdc**: Verify declared Helm chart dependencies are up to date and actively maintained.

#### kubectl-co

Switch between separate kubeconfig files without merging them

```bash
brew install steffakasid/tap/kubectl-co
```

**kubectl-co**: Register, list, and switch isolated kubeconfig files from the kubectl CLI.

#### trivyops

Inspect GitLab Trivy results across groups and subgroups

```bash
brew install steffakasid/tap/trivyops
```

**trivyops**: Collect Trivy job results from GitLab projects and flag missing `.trivyignore` files.

#### wiper

Delete configured files and folders from a directory tree

```bash
brew install steffakasid/tap/wiper
```

**wiper**: Remove files and directories by name or pattern, with optional Trash support.

## Upgrade All

To upgrade all steffakasid tools:

```bash
brew upgrade steffakasid/tap/awsclean steffakasid/tap/amiclean steffakasid/tap/dof steffakasid/tap/govital steffakasid/tap/hdc steffakasid/tap/kubectl-co steffakasid/tap/trivyops steffakasid/tap/wiper
```

Or simply:

```bash
brew upgrade
```

## Issues & Support

For issues with specific tools, please file issues in their respective repositories:

- [awsclean](https://github.com/steffakasid/awsclean)
- [dof](https://github.com/steffakasid/dof)
- [govital](https://github.com/steffakasid/govital)
- [helmfile-dependency-checker](https://github.com/steffakasid/helmfile-dependency-checker)
- [kubectl-co](https://github.com/steffakasid/kubectl-co)
- [trivyops](https://github.com/steffakasid/trivyops)
- [wiper](https://github.com/steffakasid/wiper)

## License

Each tool is licensed under its own license. See individual repositories for details.
