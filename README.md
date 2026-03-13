- Hi, I’m @angiethebulldog.
- I’m interested in code development.
- I’m partnering with different AI models with my codes.
- Currently, am obeying my lower back as it is "speaking" to me...so this is what am creating now...

## GitHub Copilot for Xcode Setup

### URL to add in Xcode

When setting up GitHub Copilot in Xcode, use the following URL:

```
https://github.com
```

If you are using a GitHub Enterprise account, replace it with your organization's enterprise URL (e.g., `https://your-org.ghe.com`).

### Token type (Classic vs Fine-grained)

Use a **classic personal access token (PAT)**. Classic tokens have the broadest compatibility with Copilot integrations.

To generate one:
1. Go to **GitHub Settings → Developer settings → Personal access tokens → Tokens (classic)**
2. Click **Generate new token (classic)**
3. Select the required scopes: `read:user` and `user:email`
4. Copy the token and paste it when prompted in the Copilot for Xcode app

> **Note:** If you prefer a fine-grained token for better security, you can use one by enabling the **"Copilot"** permission when creating it. However, classic tokens are the most straightforward option and are fully supported.
