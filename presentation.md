# Using Github Issues

!

# Issues and Pull Requests

- We use issues to track our work
- Pull requests are just a special type of issue

!

# Making a new issue

- [New Issue button](https://github.com/aboutdotme/main/issues) - drag to bookmarks bar
- Give a short title, and a long description
- Paste screenshots
- Making a TODO list
	- displays as a progress bar in list views
- Assignee (optional)
	- Andy will delegate unassigned tickets
- Add labels

!


# Labeling a new issue

## Issue type (pick one)

<span class="label feature">feature</span> <span class="label bug">bug</span> <span class="label chore">chore</span>

## Priority (optional - pick one)

<span class="label priority-high">priority: high</span> <span class="label priority-low">priority: low</span>

Medium priority is assumed unless otherwise labeled

## Area of responsibility (optional - pick one)

<span class="label fed">fed</span> <span class="label bed">bed</span>

## Browser (optional - pick all that apply)

<span class="label browser">browser: chrome</span>
<span class="label browser">browser: safari</span>
<span class="label browser">browser: firefox</span><br>
<span class="label browser">browser: explorer</span>
<span class="label browser">browser: android</span>
<span class="label browser">browser: ios</span>

!

# Managing your issues

## Viewing all issues

[https://github.com/aboutdotme/main/issues](https://github.com/aboutdotme/main/issues)

## Viewing your issues

[https://github.com/aboutdotme/main/issues/assigned/&lt;username&gt;](https://github.com/aboutdotme/main/issues/assigned/pascalpp)

Put that in your bookmarks bar

!

# Labeling your issues

## Update status as you work on issues

<span class="label status">0 - Backlog</span>
<span class="label status">1 - Ready</span>
<span class="label status">2 - Started</span>
<span class="label status">3 - Code Complete</span>
<span class="label status">4 - Released</span>

## Issue blockers

<span class="label issue-blocker">needs design input</span>
<span class="label issue-blocker">needs product input</span>

Add a comment explaining what you need so the person who opened the issue (or Trello card) will be notified. Don't reassign, or reassign to Andy for escalation if needed.

## Dead ends

<span class="label issue-deadend">can't reproduce</span> Reassign to the person who opened the issue for clarification.

<span class="label issue-deadend">duplicate</span> Reference the existing issue in a comment (duplicate of #333) and close the issue.

<span class="label issue-deadend">won’t fix</span> Explain why the issue won't be addressed and close it.

!

# Making a new pull request

- Tag the associated issue `[fixes #604]`
	- You can also tag issues in other repos!
	- `[fixes aboutdotme/me-node-api#304]`
- Describe the test procedure in a TODO list
- Add labels

!

# Labeling a new pull request

## PR Blockers

<span class="label pr-blocker">PR: needs code review</span>

Assign the PR to another dev to review your changes.

<span class="label pr-blocker">PR: needs design review</span>
<span class="label pr-blocker">PR: needs product review</span>

This PR needs to be reviewed on demo by a non-dev before merging.

<span class="label pr-blocker">PR: needs staging</span>

This PR contains changes that can only be tested properly in staging.

<span class="label pr-blocker">PR: needs test procedure</span>

You forgot to tell QA how to test the PR. You do bad.

!

# Labeling pull requests

## PR Greenlights

<span class="label pr-greenlight">PR: code reviewed</span>

If you've been assigned a PR to review and the code looks good, or all your<br>requested/suggested changes have been made, remove the <span class="label pr-blocker" style="position:relative;top:-1px;">PR: needs code review</span><br>label and add this one.

<span class="label pr-greenlight">PR: tested</span>

Used by QA to track PRs that have been tested. All todo items in the test procedure should be checked before this is added.

<span class="label pr-greenlight">PR: no test needed</span>

This PR doesn't require testing. Well aren't you fancy?

!

# fin
