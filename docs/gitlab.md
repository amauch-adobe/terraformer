### Use with GitLab

Example:

```shell
./terraformer import gitlab --group=GROUP_TO_IMPORT --resources=projects --token=YOUR_TOKEN # or GITLAB_TOKEN in env
./terraformer import gitlab --group=GROUP_TO_IMPORT --resources=groups --base-url=https://your-self-hosted-gitlab-domain/api/v4
```

List of supported resources:

* `groups`
  * `gitlab_group_membership`
  * `gitlab_group_variable`
* `projects`
  * `gitlab_branch_protection`
  * `gitlab_project`
  * `gitlab_project_membership`
  * `gitlab_project_value`
  * `gitlab_tag_protection`
