# How to Contribute

We'd love to accept your patches and contributions to this project. There are
just a few small guidelines you need to follow.

## Reporting Issues

Please use the issue tracker to report bugs or suggest new features. When creating a new issue, please include:

*   A clear and descriptive title.
*   A detailed description of the problem or feature request.
*   Steps to reproduce the bug (if applicable).
*   Expected and actual behavior.
*   Any relevant error messages.

## What We're Looking For

- **Fixes**: Typos, outdated info, broken links
- **Improvements**: Better explanations, additional examples, clearer organization
- **New content**: Helpful guides, missing information, translations

## Content Guidelines

- Use clear, concise language
- Check spelling and grammar
- Keep formatting consistent with existing pages
- Verify links work and information is current
- Include sources for factual claims



## Set up your Local Development Environment

Follow the following instructions to start contributing.

**1.** Fork [this](https://github.com/layer5io/exoscale-academy) repository.

**2.** Clone your forked copy of the project.

```
git clone --depth=1 https://github.com/<your-username>/exoscale-academy.git
```

**3.** Navigate to the project directory.

```
cd exoscale-academy
```

**4.** Add a reference(remote) to the original repository.

```
git remote add upstream https://github.com/layer5io/exoscale-academy.git
```

**5.** Check the remotes for this repository.

```
git remote -v
```

**6.** Always take a pull from the upstream repository to your master branch to keep it at par with the main project (updated repository).

```
git pull upstream master
```

**7.** Create a new branch.

```
git checkout -b <your_branch_name>
```

**8.** Install the dependencies for running the site.

```
make setup
```

**9.** Make the desired changes.

**10.** Run the site locally to preview changes.

```
make site
```


## Before Submitting

- [ ] Content is accurate and well-written
- [ ] Formatting matches existing style
- [ ] Links are functional
- [ ] Changes are clearly described in your PR

## <a name="commit-signing">Signing-off on Commits (Developer Certificate of Origin)</a>

To contribute to this project, you must agree to the Developer Certificate of
Origin (DCO) for each commit you make. The DCO is a simple statement that you,
as a contributor, have the legal right to make the contribution.

See the [DCO](https://developercertificate.org) file for the full text of what you must agree to
and how it works [here](https://github.com/probot/dco#how-it-works).
To signify that you agree to the DCO for contributions, you simply add a line to each of your
git commit messages:

```
Signed-off-by: Jane Smith <jane.smith@example.com>
```

In most cases, you can add this signoff to your commit automatically with the
`-s` or `--signoff` flag to `git commit`. You must use your real name and a reachable email
address (sorry, no pseudonyms or anonymous contributions). An example of signing off on a commit:
```
$ commit -s -m “my commit message w/signoff”
```

To ensure all your commits are signed, you may choose to add this alias to your global ```.gitconfig```:

*~/.gitconfig*
```
[alias]
  amend = commit -s --amend
  cm = commit -s -m
  commit = commit -s
```
Or you may configure your IDE, for example, Visual Studio Code to automatically sign-off commits for you:

<a href="https://user-images.githubusercontent.com/7570704/64490167-98906400-d25a-11e9-8b8a-5f465b854d49.png" ><img src="https://user-images.githubusercontent.com/7570704/64490167-98906400-d25a-11e9-8b8a-5f465b854d49.png" width="50%"></a>



## Code reviews

All submissions, including submissions by project members, require review. We
use GitHub pull requests for this purpose. Consult
[GitHub Help](https://help.github.com/articles/about-pull-requests/) for more
information on using pull requests.

## Community Guidelines

This project follows
[Google's Open Source Community Guidelines](https://opensource.google.com/conduct/).

## Need Help?

Open an issue with questions or check the existing documentation. Thanks for contributing! 🎉