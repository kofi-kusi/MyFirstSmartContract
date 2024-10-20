# Pushing Your First Smart Contract to GitHub from Remix IDE (GUI)

This guide explains how a beginner used the Remix IDE's built-in GitHub integration to push their first smart contract to GitHub from the `MyFirstSmartContract` workspace, using a token generated on GitHub.

## Prerequisites
Before you begin, ensure you have:
- A [GitHub](https://github.com/) account.
- [Remix IDE](https://remix.ethereum.org/) (Web-based).
- A **Personal Access Token** from GitHub (explained in Step 3).

## Step 1: Create a New Workspace in Remix IDE

1. Open [Remix IDE](https://remix.ethereum.org/).
2. In the **File Explorer** (on the left-hand side), click the drop-down arrow next to **File Explorer**.
3. Select **Create New Workspace**, name it `MyFirstSmartContract`, and click **OK**.

## Step 2: Write Your Smart Contract

1. Inside your new workspace, click the **New File** button and name the file `SimpleStorage.sol`.
2. Add the following smart contract code to `SimpleStorage.sol`.
3. Compile the contract by clicking the **Solidity Compiler** tab on the left, then click the **Compile** button.

## Step 3: Generate a Personal Access Token on GitHub

1. Log in to your GitHub account.
2. Click on your profile icon in the top-right corner and select **Settings**.
3. On the left sidebar, navigate to **Developer settings** > **Personal access tokens** > **Tokens (classic)**.
4. Click **Generate new token**.
5. Set the token's permissions. At a minimum, enable **repo** access for full control of repositories.
6. Generate the token and copy it. **Save this token securely**, as it will only be shown once.

## Step 4: Connect Your GitHub Account in Remix

1. In the Remix IDE, go to the **File Explorer**.
2. Right-click on the file `SimpleStorage.sol` and select **Share** > **GitHub**.
3. In the dialog box, paste the **Personal Access Token** you generated on GitHub when prompted for authentication.
4. You will now be connected to your GitHub account.

## Step 5: Set Up a GitHub Repository

1. Create a new repository on GitHub:
    - Click the **+** button in the top-right corner and select **New repository**.
    - Name your repository (e.g., `first-smart-contract`), and choose whether to make it public or private.
    - Click **Create repository**.

## Step 6: Push Your Smart Contract to GitHub Using Remix IDE

1. In Remix IDE, go to the **File Explorer** tab.
2. Right-click on the `SimpleStorage.sol` file and select **Share** > **GitHub**.
3. In the **Push to GitHub** dialog that appears:
    - **Repository URL**: Paste the URL of your GitHub repository.
    - **Branch**: Choose the branch to push to (typically `main` or `master`).
    - **Commit Message**: Type a descriptive message such as `"Add SimpleStorage smart contract"`.
    
4. Click **Push** to upload the file to your GitHub repository.

## Step 7: Verify Your Smart Contract on GitHub

1. Visit your GitHub repository page.
2. You should see the `SimpleStorage.sol` file along with the commit message.

## Conclusion

You have successfully written a smart contract in Remix IDE, connected your GitHub account using a Personal Access Token, and pushed the contract to your GitHub repository using the GUI.

### Additional Resources
- [Remix IDE Documentation](https://remix-ide.readthedocs.io/en/latest/)
- [GitHub Documentation](https://docs.github.com/)
- [Solidity Documentation](https://docs.soliditylang.org/en/v0.8.0/)
