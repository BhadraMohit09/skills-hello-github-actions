![Wave Animation](https://capsule-render.vercel.app/api?type=waving&color=9823f5&height=150&section=header)

<header>

> ## Hello GitHub Actions ™️👋🏻👋🏻

_*Create and run GitHub Actions workflow*_

</header>

> ### Step 1: Create a workflow file:-📌

> _Welcome to "Hello there in GitHub Actions!" :wave:_

**What is _GitHub Actions_??**: GitHub Actions is a flexible way to automate nearly every aspect of your team's software workflow. You can automate testing, continuously deploy, review code, manage issues and pull requests, and much more. The best part, these workflows are stored as code in your repository and easily shared and reused across teams. To learn more, check out these resources *

- The GitHub Actions feature page, see [GitHub Actions](https://github.com/features/actions)...!
- The "GitHub Actions" user documentation, see [GitHub Actions](https://docs.github.com/actions)...!

**What is a _workflow_??**: A workflow is a configurable automated process that will run one or more jobs. Workflows are defined in special files in the `.github/workflows` directory and they execute based on your chosen event. For this exercise, we'll use a `pull_request` event...!

- To read more about workflows, jobs, and events, see "[Understanding GitHub Actions](https://docs.github.com/en/actions/learn-github-actions/understanding-github-actions)".
- If you want to learn more about the `pull_request` event before using it, see "[pull_request](https://docs.github.com/en/developers/webhooks-and-events/webhooks/webhook-events-and-payloads#pull_request)".

To get you started, we ran an Actions workflow in your new repository that, among other things, created a branch for you to work in, called `welcome-workflow`.

### :keyboard: Activity:: Create a workflow file-📌

1. Open a new browser tab, and navigate to this same repository. Then, work on the steps in your second tab while you read the instructions in this tab.
1. Create a pull request. This will contain all of the changes you'll make throughout this part of the course...

   Click the **Pull Requests** tab, click **New pull requestr̥**, set `base: main` and `compare:welcome-workflow`, click **Create pull request**, then click **Create pull request** again.

1. Navigate to the **Code** tab.
1. From the **main** branch dropdown, click on the **welcome-workflow** branch!
1. Navigate to the `.github/workflows/` folder, then select **Add file** and click on **Create new file**.
1. In the **Name your file** field, enter `welcome.yml` - 
1. Add the following content to the `welcome.yml` file -

   ```yaml copy
   name: Post welcome comment📬
   on:
     pull_request:
       types: [opened]
   permissions:
     pull-requests: write
   ```

1. To commit your changes, click **Commit changes**!!💬
2. Type a commit message, select **Commit directly to the welcome-workflow branch** and click **Commit changes**...!🎊
1. Wait about 20 seconds, then refresh this page (the one you're following instructions from). A separate Actions workflow in the repository (not the workflow you created) will run and will automatically replace the contents of this README file with instructions for the next step<>

<footer>

---
> [!Important]
> Get help: [Post in our discussion board](https://github.com/orgs/skills/discussions/categories/hello-github-actions) &bull; [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2023 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)
-- Update Patch #1
</footer>
