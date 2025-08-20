# Algorithmia SE — Organization Moved

**This organization has moved.**  
To keep development centralized and improve CI/CD, project structure, and collaboration flows, Algorithmia SE has moved [**here**](https://github.com/Algorithmia-SE).

---

## Why we moved
- Name originality and future improvements
- Consolidate active projects and content in one place.
- Use an updated repo layout and improved CI/CD (Vercel, Actions).
- Improve contributor onboarding, templates, and automation.
- Prepare for new features (project showcase, contributor dashboard).

---
<!--
## What you should do (if you have a local clone)

If you already cloned this old repository locally, update your `origin` remote to point to the new repository:

```bash
# Option A: update the origin remote (recommended)
git remote set-url origin git@github.com:Algorithmia-SE/NEW-REPO-NAME.git
# or (HTTPS)
git remote set-url origin https://github.com/Algorithmia-SE/NEW-REPO-NAME.git

# Verify
git remote -v
````

Or, clone the new repo fresh:

```bash
git clone git@github.com:Algorithmia-SE/NEW-REPO-NAME.git
# or (HTTPS)
git clone https://github.com/Algorithmia-SE/NEW-REPO-NAME.git
```

---

## I have an open issue or pull request

* **Open PRs**: If you opened a PR against this old repo, please either:

  * Re-create the PR against the new repo (preferred), or
  * Close this PR and open a new one in the new repository with the same branch; include the original PR link for context.
* **Open issues**: Issues that were not migrated can be re-opened in the new repository. We have (or will) migrate high-priority issues and “good first issues”.
* If you need help migrating a PR or issue, tag `@dohoudaniel` or open a new issue in the new repository with the label `migration-help`.

---

## If you are a maintainer or integrator — checklist

Follow these steps to finish the migration and avoid outages:

1. **Repository settings**

   * Transfer any required repository settings to the new repo.
   * Enable branch protection rules on `main`/`master`.
2. **CI / Actions**

   * Update GitHub Actions workflows or copy them to the new repo.
   * Ensure secrets used by workflows are recreated in the new repo (`Settings → Secrets`).
3. **Vercel / Deployment**

   * Update or create new Vercel project with the new repo.
   * Reconfigure environment variables (EmailJS keys, analytics, etc.) in Vercel.
4. **Webhooks & Integrations**

   * Re-add Slack/Discord webhooks, Dependabot, Sentry, Codecov, etc.
5. **Domain / DNS (if relevant)**

   * If a custom domain is pointed to the old repo site, update Vercel/hosting to use the new project.
6. **Badges & Links**

   * Update README badges and links in documentation to reference the new repo URL.
7. **Archive or redirect this repo**

   * Mark this repository as archived (optional) or keep a short README that links to the new repository and explains why it was moved.

---

## Quick copy-paste message for PRs / issues

If you need to reply to contributors, use this short message:

> Hi — thanks for contributing! We’ve moved this project to a new repository: `https://github.com/Algorithmia-SE/NEW-REPO-NAME`. Please rebase/submit your PR there. If you need help migrating your branch or PR, tell us and we’ll assist.

---

## Notes about forks & stars

* **Forks:** Forks of the old repo remain associated with it. Contributors who rely on forks should re-fork the new repository to ensure pull requests target the right upstream.
* **Stars:** Stars on the old repo will remain. If you want to preserve community signal, pin the new repo in organization settings and announce the move on social channels.

--->

## Contact / Help

If you run into any migration problems, reach out:

* Maintainer: **Daniel Dohou** — [https://github.com/dohoudaniel](https://github.com/dohoudaniel)
* Community: (Discord/Slack link)
* Or open an issue in the new repo: [https://github.com/Algorithmia-SE/NEW-REPO-NAME/issues](https://github.com/Algorithmia-SE/NEW-REPO-NAME/issues)

---

## Thank you

Thanks for being part of Algorithmia SE. We’re excited for the next phase — better workflows, clearer contribution paths, and more impact.

— The Algorithmia SE Team


<!--
---

## Extra suggested files to add now

1. **Put the above README in the old repo's `README.md`** (so visitors see the move instantly).
2. **Create a short `MIGRATION.md`** in the new repo with contributor-specific instructions (how to add a project, how to open a PR, “Good First Issues” list).
3. **Create a migration board or issue** in your new repository that tracks which issues/PRs need manual migration — label them `migrate`, `high-priority`, `good-first-issue`.

---

If you want, I can:
- Produce `MIGRATION.md` content now (with templates for PR migration).
- Create a ready-to-post announcement message for Twitter/Discord/GitHub Discussions.
- Produce a short `ARCHIVE_README.md` that auto-links to the new repo and includes the same instructions.
```
-->
