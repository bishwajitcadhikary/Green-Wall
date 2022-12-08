# [Green Wall](https://green-wall.vercel.app/)

_Take a picture 📸 of your GitHub contributions, then share it!_

Green Wall is a web site tool that help you review the contributions you have made on GitHub :octocat: over the years, so you can generate the image to save and share.

<a href="https://green-wall.vercel.app/">
  <img alt="Green Wall Screenshot" src="https://user-images.githubusercontent.com/47730755/189281945-c61c9044-0cd7-473d-8bee-d442695103a4.png">
</a>

💡 This project is inspired by [GitHub Contributions Chart Generator](https://github-contributions.vercel.app/).

## Run this project

This project uses the [GitHub API](https://docs.github.com/en/graphql) to fetch data, so you need a personal access token for authentication. For more information, see "[Creating a personal access token](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token) ."

After creating personal access token, create a file named `.env.local` at the top of this project, then paste the token into it.

```sh
# .env.local

# The format should be: GITHUB_ACCESS_TOKEN="[YOUR TOKEN]"

# Example:
GITHUB_ACCESS_TOKEN="ghp_eQ81YcyFcwVjdJwBgUj150VPnxBf1N48Sep7"
```

Now you are ready to run `yarn dev` to develop.
