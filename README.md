# FindGitHubEmail
### Find the email address of any GitHub User

It's a well-known fact (or at least it should be) that everything you push to a public GitHub repository is *public*. This includes a lot of information other than just source files. Since both Git and GitHub require you to provide an email address, it should be no surprise that this information is public as well. **FindGitHubEmail** (catchy title, I know) is a simple script that queries the [GitHub API](http://developer.github.com/v3/) and guesses a given user's email address based on their public activity. The script is a bit of a hack; sorry if your eyes are bleeding.

**FindGitHubEmail** makes it easy to get in contact with open source developers. Please use it for good, not evil.

## Usage

Run this:

```sh
git clone https://github.com/hodgesmr/FindGitHubEmail.git ~/FindGitHubEmail
bash ~/FindGitHubEmail/findGitHubEmail hodgesmr
```

If you're not looking for me, replace `hodgesmr` with another GitHub username.

## A Matt Hodges project

This project is maintained by [@hodgesmr](http://twitter.com/hodgesmr).
