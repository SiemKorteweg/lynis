# Contributions

## Pull Requests
We welcome any contribution to improve Lynis. Contributions to the Lynis project can
be submitted as a pull request. The upstream project can be found in our [GitHub repository](https://github.com/CISOfy/lynis).

By submitting a [Pull Request](https://help.github.com/articles/using-pull-requests/)
to this repository, you agree that you:

1. Own the contribution that you are providing or have obtained permission from
   the contribution owner

2. Allow your contribution to be licensed under the license of the target
   project (GPLv3)

3. Allow your contribution to be freely distributed to the Lynis community

4. Allow the project the [Unlimited Rights](#Unlimited-Rights) to your contribution

If you have questions regarding development, send us an e-mail at [lynis-dev](mailto:lynis-dev@cisofy.com)

## Unlimited Rights
Our project is licensed under GPLv3. By providing a contribution to the project, it
will be used for the purpose of the project. Unlimited rights includes the rights to
use, modify, reproduce, release, perform, display, or disclose computer software or
computer software documentation in whole or in part, in any manner and for any
purpose whatsoever, and to have or authorize others to do so.

If you want to be named in as a contributor in the CONTRIBUTOR file, then include
this notition in your pull request. Preferred format: Full Name, with optional the
company name and/or your e-mail address).

## Developer Guidelines

To ensure all pull requests can be easily checked and merged, here are some tips:
* Your code should work on other platforms running the bourne shell (/bin/sh), not just BASH.
* Properly document your code where needed. Besides the 'what', focus on explaining the 'why'.
* Check the log information (lynis.log) of your new test or changed code, so that it provides helpful details for others.
* Most variables should be capitalized, with underscore as word separator (e.g. PROCESS_EXISTS=1)
