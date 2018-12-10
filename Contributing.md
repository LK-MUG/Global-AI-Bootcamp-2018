## Guidelines for Contributing to Repository

Before contributing:

- ensure that the **dev** branch on your fork is in sync with the original **Global-O365-Dev-BootCamp-2018** repository
    ```sh
    # assuming you are in the folder of your locally cloned fork....
    git checkout dev

    # assuming you have a remote named `upstream` pointing to the official **Global-O365-Dev-BootCamp-2018** repo
    git fetch upstream

    # update your local dev to be a mirror of what's in the main repo
    git pull --rebase upstream dev
    ```

- create a feature branch for your change. If you'll get stuck on an issue or merging your PR will take a while, this will allow you to have a clean dev branch that you can use for contributing other changes
    ```sh
    git checkout -b my-contribution
    ```
