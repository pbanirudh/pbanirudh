# ⚡ GitHub Profile Setup Guide

Follow these quick steps to make your GitHub bio go live:

### 1. Create your Special Repository
1. Go to [GitHub New Repository](https://github.com/new).
2. Set the **Repository name** to match your exact **GitHub username** (e.g., if your handle is `octocat`, name the repository `octocat`).
3. Set the repository visibility to **Public**.
4. Check **Add a README file** (or create it with our provided `README.md`).

---

### 2. Configure Your Profile README
1. Copy the contents of [`README.md`](./README.md) into your repository's `README.md`.
2. Do a quick search-and-replace for these placeholders:
   - `YOUR_GITHUB_USERNAME` $\rightarrow$ Your GitHub handle
   - `YOUR_LINKEDIN` $\rightarrow$ Your LinkedIn profile username
   - `YOUR_HUGGINGFACE` $\rightarrow$ Your Hugging Face handle
   - `YOUR_KAGGLE` $\rightarrow$ Your Kaggle profile handle
   - `YOUR_TWITTER` $\rightarrow$ Your X/Twitter handle
   - `your_email@example.com` $\rightarrow$ Your contact email
3. Commit the changes. Your profile page will immediately update with the glowing neon cyberpunk theme!

---

### 3. (Optional) Activate the Animated Contribution Snake Game
To enable the animated snake eating your contribution commits:
1. In your repository, create the path `.github/workflows/snake.yml` and paste the contents from [`.github/workflows/snake.yml`](./.github/workflows/snake.yml).
2. Go to **Settings** > **Actions** > **General** in your repository.
3. Scroll down to **Workflow permissions**, select **Read and write permissions**, and click **Save**.
4. Go to the **Actions** tab, click **Generate Snake Contribution Grid** on the left, and click **Run workflow**.
5. Once complete, it creates an `output` branch with the dynamic SVGs, and your README will display the animated snake!
