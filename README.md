# semantic-release-example

A repository that use semantic release versioning

## To create hotfix release

Create a branch from a version tag:

```bash
git checkout -b 1.1.x v1.1.0
```

Continue to make changes and commit the changes. Run `Run Semantic Release` to create the hotfix version.
Once its done, then create PR to main so that the fixes are available in trunk.

## To create beta pre-release

Commit changes into a branch named `beta` and run `Run Semantic Release` workflow in Actions tab.

## To create alpha pre-release

Commit changes into a branch named `alpha` and run `Run Semantic Release` workflow in Actions tab.
