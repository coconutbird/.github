# Security policy

This policy applies to every repository that the GitHub account `coconutbird` owns.
It also applies to the crates that I publish from those repositories.
A repository can replace this policy with its own `SECURITY.md` file.

For napbat projects, use the [napbat security policy](https://github.com/napbat/.github/blob/main/SECURITY.md).

## Security maintainer

I maintain these projects, and I receive and handle each vulnerability report.

| Name | GitHub | crates.io |
| --- | --- | --- |
| Jon-Luke Biddle | [@coconutbird](https://github.com/coconutbird) | [coconutbird](https://crates.io/users/coconutbird) |

## Report a vulnerability

Report each vulnerability privately through GitHub.
Do not report a vulnerability in a public issue, pull request, or discussion.
A public report can expose users before a fix is available.

Only you and I can see a private report.
GitHub adds you to the report as a collaborator.

To report a vulnerability, do these steps:

1. Open the repository on GitHub.
2. Select the **Security and quality** tab.
3. Select **Report a vulnerability**.
4. Complete the form.
5. Submit the form.

If the repository does not show **Report a vulnerability**, use the form in the `coconutbird/.github` repository:

```text
https://github.com/coconutbird/.github/security/advisories/new
```

Write the affected repository name in the form.

### What to include

Give the information that follows, if you have it:

- The affected repository or crate.
- The affected version, release tag, or commit.
- The steps that reproduce the vulnerability.
- A proof of concept.
- The effect that an attacker can get.
- Your plan for public disclosure.

A report with steps that reproduce the vulnerability is faster to assess.

## What happens after you report

1. I acknowledge your report within 5 business days.
2. I assess the report and tell you if I accept it as a vulnerability.
3. I develop the fix privately.
4. I can ask you to test the fix.
5. I release the fix.
6. For a vulnerability in released code, I publish a GitHub security advisory.
7. For a vulnerability in released code, I request a CVE identifier.

I give you credit when I publish information about the vulnerability.
If you do not want credit, tell me in the report.

I send you a status update at least every 14 days until I release the fix.

## Disclosure

Keep the vulnerability private until I release the fix.
If I do not release a fix within 90 days of your report, you can disclose the vulnerability.
If I need more time, I ask you before the 90 days end.
Then I agree on a new date with you.

## Supported versions

I fix vulnerabilities in the latest release of each project.
For a crate, the latest release is the newest version on crates.io.
I also fix vulnerabilities in the default branch of each repository.
I fix an older release only when the advisory identifies that release as fixed.

## Scope

These items are in scope:

- Source code in repositories that `coconutbird` owns.
- Crates that I publish from those repositories.

These items are not in scope:

- A vulnerability in a third-party dependency.
  Report it to the project that owns the dependency.
  If my project uses the dependency in a way that makes the vulnerability exploitable, report that use to me.
- A vulnerability in the original code of a fork.
  Report it to the original project.
  Report a vulnerability to me only if my change caused it.
- A report that does not show a security effect.
  For example, scanner output without a proof of concept is not in scope.

## Safe harbor

This section applies to research that you do in good faith and that obeys this policy.

- I consider the research to be authorized.
- I do not start legal action against you because of the research.
- I do not report the research to law enforcement.
- If a third party starts legal action against you because of the research, I tell them that the research obeyed this policy.

You must still obey all laws that apply to you.
If you are not sure that an action obeys this policy, ask me in a report before you do it.

## Rewards

I do not have a bug bounty program.
I do not pay for reports.
