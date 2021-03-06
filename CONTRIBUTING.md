## How to contribute to software.opensuse.org

#### **Did you find a bug?**

* **Do not open up a GitHub issue if the bug is a security vulnerability
  in the application**, and instead contact the [security team](mailto:security-team@suse.de).

* **Ensure the bug was not already reported** by searching on GitHub under [Issues](https://github.com/openSUSE/software-o-o/issues).

* If you're unable to find an open issue addressing the problem, [open a new one](https://github.com/openSUSE/software-o-o/issues/new). Be sure to include a **title and clear description**, as much relevant information as possible, including screenshots of what you see in your browser. You can attach screenshots to the text by drag and dropping them.

#### **Did you write a patch that fixes a bug?**

* Open a new GitHub pull request with the patch.

* Ensure the PR description clearly describes the problem and solution. Include the relevant issue number if applicable.
* Screenshots are appreciated for visual changes.

#### **Did you fix whitespace, format code, or make a purely cosmetic patch?**

With the rubocop version we are pinned to, there should be no warnings, and the only way to fix "pending" violations we have with rules is to disable some "ignored" issues in '.rubocop_todo.yml', re-run rubocop, fix those issues, and commit both '.rubocop_todo.yml' and the fixes at the same time. Please have one commit per "cop" type.

If you are not going to fix all issues of a certain type on all files, but just on a subset, you can as well disable the ignore in '.rubocop_todo.yml' locally, fix the issues in a few files, and commit those, without committing '.rubocop_todo.yml', so that it keeps ignoring the files that still have the issue.

If you fix rubocop issues like the ones above, you can submit it with a GitHub pull request.

Other changes that are cosmetic in nature and do not add anything substantial to the stability, functionality, or testability of this application will generally not be accepted (we share the same [rationales as the Rails project](https://github.com/rails/rails/pull/13771#issuecomment-32746700)).

#### **Do you intend to add a new feature or change an existing one?**

* Please open an [issue](https://github.com/openSUSE/software-o-o/issues/new) to discuss your change before writing any code.
* If the changes are visual, consider attaching screenshots showing the before/after change in the GitHub pull request description.

#### **Do you want to talk to us?**

* We hang out in our [gitter chatroom](https://gitter.im/openSUSE/software-o-o). This is an **informal** chat, please
  keep discussions about bugs and features on GitHub.

Thanks! :green_heart: :green_heart: :green_heart:

software.opensuse.org team
