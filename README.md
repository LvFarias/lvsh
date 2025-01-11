# Installation

## Install deps

1. Download lvsh:

    ```shell
    sudo apt install ccrypt zip
    ```

## Download and Config

1. Download lvsh:

    ```shell
    wget -c https://github.com/LvFarias/lvsh/archive/refs/heads/main.zip main.zip
    unzip main.zip
    ccrypt -d -f lvsh-main/lvsh.tgz.cpt
    tar xvfz lvsh-main/lvsh.tgz -C ~ --strip-components=2
    ```

2. Extract and run Config:

    ```shell
    ccrypt -d -f ~/lvsh/shell.tgz.cpt
    tar xvfz ~/lvsh/shell.tgz -C ~ --strip-components=2
    ~/lvsh/config.sh
    ```

## Create company workspace (Optional)

1. Run workspace command for company

    ```shell
    ~/lvsh/make<COMPANY>.sh
    ```
    1.1 Example: `~/lvsh/makeWhims.sh`.

2. Make Backup with change ssh, zsh or shell:

    ```shell
    ~/lvsh/backup.sh
    ```