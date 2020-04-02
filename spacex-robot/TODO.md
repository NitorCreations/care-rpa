# TODO file for new activity package

- read all INTRODUCTION.md files and follow their guidance (those files
  should help you get understanging what belong where in this new
  activity package)
- add your own content to toplevel README.md file
- add your own license text to LICENSE file
- try out your new activity using following "Quick workflow with CLI"
- make your own changes to this project and make it yours

# Quick workflow with CLI

On shell (or command prompt) do following:

    robo credentials <paste your API Key here>
    mkdir new_activity
    chdir new_activity
    robo init .
    robo wrap
    robo run entrypoint.sh
    # on Windows, replace above with one below
    # robo run entrypoint.cmd
    robo upload --workspace 1234 --activity 5678
    # in above, replace workspace and activity with your own values
