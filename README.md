# Homebrew Tap

Consolidated Homebrew tap for all steffakasid projects.

## Installation

### Add the tap

```bash
brew tap steffakasid/tap
```

### Available Tools

#### awsclean

AWS resource cleanup tools with two commands:

```bash
# Install awsclean
brew install steffakasid/tap/awsclean

# Install amiclean (AMI cleanup specific tool)
brew install steffakasid/tap/amiclean
```

**awsclean**: Efficiently clean up unused AWS resources (snapshots, volumes, instances, etc.)  
**amiclean**: Specialized tool for cleaning up unused AMI images

#### dof

Kubernetes deployment configuration checker and validator

```bash
brew install steffakasid/tap/dof
```

**dof** validates and checks Kubernetes deployment manifests for best practices and common issues.

#### govital

Kubernetes Vitality Operator for pod health monitoring and management

```bash
brew install steffakasid/tap/govital
```

**govital** manages pod lifecycle and health checks in Kubernetes clusters.

#### helmfile-dependency-checker (hdc)

Analyzes Helmfile dependencies and checks for issues

```bash
brew install steffakasid/tap/hdc
```

**hdc** scans Helmfile configurations for outdated dependencies, version conflicts, and maintenance issues.

#### kubectl-co

Kubectl plugin for cluster operations and configuration management

```bash
brew install steffakasid/tap/kubectl-co
```

**kubectl-co** extends kubectl with additional cluster operations and configuration utilities.

#### trivyops

GitLab trivy results scanner and analyzer

```bash
brew install steffakasid/tap/trivyops
```

**trivyops** scans GitLab for trivy vulnerability scanning results and provides analysis and reporting.

#### wiper

Kubernetes resource cleanup and management tool

```bash
brew install steffakasid/tap/wiper
```

**wiper** removes unused Kubernetes resources and helps manage cluster cleanup.

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
