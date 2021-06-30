# gitlab-templates
Collection of Gitlab templates I found useful

# Details
This are a use at your own risk templates. I will be customizing them as I continue testing and finding ways to integrate into build pipelines.

# Usage
If you are a gitlab user, you can share these templates by creating a public project and including the templates in ci.yml file:

```
include:
  - project: 'gitlab-templates'
    file: 'security/DAST.yml'
```

# Gitlab Supported Documentation 
https://gitlab.com/gitlab-org/gitlab-foss/-/blob/master/doc/development/cicd/templates.md

# Gitlab Supported Templates
https://gitlab.com/gitlab-org/gitlab-foss/-/tree/master/lib/gitlab/ci/templates/Security
https://gitlab.com/gitlab-org/gitlab-foss/-/tree/master/lib/gitlab/ci/templates/Jobs
