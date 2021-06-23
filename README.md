# .github
Community Health Files for the `im-funding` organization.

Each repository within this organization will inherit these default files unless the repository has defined their own.

## Workflow Templates

This repository contains a `workflow-templates` folder.  The templates defined in this folder have been customized for our build processes and standards.  By including them in this repository, users can [add a workflow] to their repo by clicking a button.

### Modifying and Creating Templates

Files inside of `./workflow-templates` that are prefixed with `im-` or `im_` are managed at the Enterprise level.  The source of truth for these files is the [im-practices/.github] repository.  Any changes to these files should be made via PR to [im-practices/.github], not directly in this repository.  When changes are merged in to [im-practices/.github], they are replicated to each of the `.github` repos in the Enterprise.  If changes have been made in this repository to any of the `im` template files they will be overwritten when the syncing happens.

If there are new templates that can be used across many organizations, please make a PR to [im-practices/.github] so they can be shared with each organization.  

Templates that are specific to an organization can be added directly to this repository and those files should contain the `org-` prefix.  These files will not be touched when syncing happens.

For detailed info around creating or modifying the templates see [Sharing workflows with your organization].

[add a workflow]: https://docs.github.com/en/actions/guides/setting-up-continuous-integration-using-workflow-templates
[Sharing workflows with your organization]: https://docs.github.com/en/actions/learn-github-actions/sharing-workflows-with-your-organization
[im-practices/.github]: https://github.com/im-practices/.github
