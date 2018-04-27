# Slides

A sample slide setup for creating presentations with hugo and revealjs

The steps are simple:

1. Clone the new repository
2. Enable gh-pages (the url should be `<username>.github.io/<repo_name>`)
3. Add the desired sub domain in `travis/prepare_static_files.sh` in the `CNAME` variable
4. Enable travis-ci for this repository
5. Add an environment variable to travis-ci name `GITHUB_TOKEN` with a Token from GitHub with the following rights `public_repo, repo:status, repo_deployment`
6. Add a CNAME entry to `<username>.github.io` inside the DNS


You are pointing the CNAME to your generic URL and the `CNAME` file inside the repository configures what repo will be served
