# hugo-mock-landing-page
For CIS 3500 HW02

This repository uses GitHub Actions to automatically build and deploy the Hugo website whenever changes are pushed to the main branch. The workflow checks out the repository with all submodules, sets up Hugo 0.144.1 (extended version), builds the site with draft content included while applying minification for optimal performance, and finally deploys the generated static files to the gh-pages branch. This automation eliminates the need for manual builds and deployments, ensuring that the published website always reflects the latest content in the repository.
