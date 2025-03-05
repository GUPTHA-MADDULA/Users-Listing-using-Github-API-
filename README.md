## Listing GitHub Users using GitHub API

In this repository, you will find how to list users belonging to a GitHub account through GitHub API calls.

### Traditional Approach
- Organizations commonly use the GitHub UI to check their members, their roles, and permissions such as read, write, or deleted status.
- This method is widely used by DevOps engineers to collaborate on projects and manage users.

### New Approach
- The new approach utilizes GitHub API to list users and their permissions along with identifying admins of the GitHub account.
- This process is automated using a shell script, which can be executed anytime to view the required information.

### Prerequisites
- Export the GitHub username to an environment variable.
  - Command: `export user="user_name"`
- Generate a personal access token from GitHub under Developer Settings in the Classic Token tab.
  - Carefully select the required scopes while generating the token.
  - Delete the token after usage to maintain security.
  - Command: `export token="enter_the_token"`

### Running the Shell Script
- Ensure the shell script has executable permissions.
- Command: `./shellscript.sh <argument_1> <argument_2>`
- `argument_1`: GitHub account name.
- `argument_2`: GitHub repository name.

### Execution Output
- The script will display the list of users belonging to the GitHub account along with their permissions.
- This method enhances automation and eliminates the need for manual user verification through the GitHub UI.

