# Travis CLI Test

This project demonstrates the steps required to install and run Travis CLI commands from within a Travis build.

These techniques are useful for accessing arbitrary github repositories, fetching release files, etc.

Includes install commands for public www.travis-ci.org and enterprise Travis (commented-out).

To prove it works, the script issues commands with Travis CLI to:
 - Display the user's list of github repos, and
 - Set a public environment variable into the current Travis project settings.
