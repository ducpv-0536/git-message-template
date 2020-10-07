## Github

```sh
mkdir -p .github && curl -fsSL https://raw.githubusercontent.com/ducpv-0536/git-message-template/main/.github/pull_request_template.md > .github/pull_request_template.md
```

## Gitlab

```sh
mkdir -p .gitlab/merge_request_templates && curl -fsSL https://raw.githubusercontent.com/ducpv-0536/git-message-template/main/.gitlab/merge_request_template/Default.md > .gitlab/merge_request_templates/Default.md
```

When creating new merge request, choose the *Default* template from the *Choose a template* dropdown in *Description* section.

![mr](./gitlab_mr.png)
