This repo is for the reporting of issues found within and when using Bash on Ubuntu on Windows.

###Labels
This and our User Voice page are your best ways to interact directly with the Bash on Ubuntu on Windows teams. We will be monitoring and responding to issues as best we can. Please attempt to avoid filing duplicates of open or closed items when possible. In the spirit of openness we will be tagging issues with the following:

- **bug** – We consider this issue to be a bug internally. This tag is generally for bugs in implemented features, or something we consider to be a “bug level” change. Things marked with Bug have a corresponding bug in on Microsoft’s internal bug tracking system.
  - Example: No internet connectivity in Bash [(#5)](https://github.com/Microsoft/BashOnWindows/issues/5)

- **feature** – Denotes something that is not yet implemented.  The community should use our User Voice page for voting on which features everyone feels as the most important.  The team will take the User Voice page as input in deciding what to work on next.
  - Example:  Docker is not working [(#85)](https://github.com/Microsoft/BashOnWindows/issues/85)

- **discussion** – Denotes a discussion on the board that does not relate to a specific feature.
  - Example: Windows Subsystem for Linux is not open source [(#178)](https://github.com/Microsoft/BashOnWindows/issues/178)

- **fixinbound** – When possible, we will mark bugs that have been fixed internally.  Unfortunately we cannot say specifically when the bug will hit the insider flights.

- **bydesign** – Denotes that an issue is raised that we consider is working as intended.  We will give some reasoning why this is by design.  After one week we will either close the issue or mark as Discussion depending on what comes up.

Additional tags may be used to denote specific types of issues.  These include items such as network or symlink. 

###Closing
Issues may be closed by the original poster at any time.  We will close issues if:
- One week passes after the change goes out to the Insider Fast ring
- An issue is clearly a dup of another.  The duplicate will be linked
- Any discussion that has clearly run its course

###Important Links
- Documentation:  https://msdn.microsoft.com/en-us/commandline/wsl/about
- Release Notes: https://msdn.microsoft.com/en-us/commandline/wsl/release_notes
- User Voice: https://wpdev.uservoice.com/forums/266908-command-prompt-console-bash-on-ubuntu-on-windo/category/161892-bash
- WSL Blog: https://blogs.msdn.microsoft.com/wsl
- Console Blog: https://blogs.msdn.microsoft.com/commandline/
- Stack Overflow: https://stackoverflow.com/questions/tagged/wsl
- Community powered list of programs that work and don't work: https://github.com/ethanhs/WSL-Programs
- Community powered discussion forum: http://wsl-forum.qztc.io/

###FAQs/Tips and Tricks

Q: Can I run any other distro besides Ubuntu?
A: Its not officially supported but you may be able to run Arch (and likely others) using the steps by @goreliu here: https://github.com/Microsoft/BashOnWindows/issues/8#issuecomment-240026910

Q: Can I upgrade Ubuntu to any other release? 14.04 is old. 
A: People reporting success here: https://github.com/Microsoft/BashOnWindows/issues/482

Q: I love this feature, can I get it? 
A: Please suggest one uservoice link above. Please note that Microsoft (the author of this FAQ section doesn't work for them) is resource constrained and have said that they are focusing on the most use development related scenarios first.
