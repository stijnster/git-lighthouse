Copy the git-lh script to a bin directory on your system and change the execution rights;

    cp git-lh <YOUR BIN PATH HERE>/bin
    chmod 755 <YOUR BIN PATH HERE>/bin/git-lh

Go to your repository directory and add these config values

    git config --add lighthouse.token <YOUR TOKEN HERE>
    git config --add lighthouse.account <YOUR ACCOUNT HERE>
    git config --add lighthouse.project <YOUR LIGHTHOUSE PROJECT ID HERE>

Run the script from within the directory to load all your changes;

    git-lh

Or, pass in a commit or tag to start keeping lighthouse up-to-date from that version;

    git-lh <YOUR COMMIT OR TAG HERE>