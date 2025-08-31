# actions-collection

A collection of useful Github Actions

| name                 | description                                                                                                                                                                                                                                |
| -------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| generate-javadoc.yml | generates a java doc via javac                                                                                                                                                                                                             |
| release-builder.yml  | triggered by commit message keywords: `#patch`, `#minor`, `#major`; builds a new release using semver-versioning; tags the commit with latest version; in release message includes all commit messages since last commit and contributores |
| github-pages.yml     | builds a react based project; pushes to a gh-pages branch and deploys via github pages                                                                                                                                                     |
