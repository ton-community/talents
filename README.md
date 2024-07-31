### Joining into TON Talents Directory

#### Step 1: Submit a Pull Request
- **Developers:** Add your information to the `devs.json` file.  Example entry:
  ```json
  {
    "name": "Alice Smith",
    "summary": "Won the Best DApp Award at TOL Hackathon 2024",
    "tags": ["Smart-contracts", "dApps", "NFTs"],
    "projects": [{"name": "Awesome project", "link": "https://example.com"}],
    "contacts": {"website": "https://www.linkedin.com/in/alicesmith", "email": "alice.smith@example.com"}
  }
  ```
- **Teams:** To add your information to the `teams.json` file, you need to create an object structured as follows:
  ```json
  {
    "name": "Astralyx",
    "summary": "Company with big experience in TON and other chains development.",
    "tags": ["Smart-contracts", "Web 2.0 & Web 3.0 development"],
    "projects": [{"name": "XJetSwapBot", "link": "http://t.me/xjetswapbot"}],
    "contacts": {"website": "http://astralyx.dev", "email": "contact@astralyx.dev"}
  }
  ```

#### Step 2: Await Review
- After submitting your pull request, our team will review your submission to ensure it meets our standards and criteria. Review typically takes up to one week.

#### Step 3: Get Approved
- Once your submission is approved, you or your team will be featured in our directory at [TON Talents](https://ton.org/talents), connecting you with potential clients and projects.

---

Save this guide as a `README.md` file in the root directory of your project repository to provide clear instructions for potential contributors on how to add their profiles via GitHub.


## Updating Your PR

If the maintainers notice anything that we'd like changed, we'll ask you to edit your PR before we merge it. There's no need to open a new PR, just edit the existing one. If you're not sure how to do that,
[here is a guide](https://github.com/RichardLitt/knowledge/blob/master/github/amending-a-commit-guide.md) on the different ways you can update your PR so that we can merge it.
