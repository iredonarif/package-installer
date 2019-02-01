# package-installer

Is a bash script to install packages in bulk on some linux distributions.
I developed this program in my second year of computer science.

This idea came to me because I often installed systems on computers. And for any new installation, I repeated the same actions.
This is the reason why I had to find a way to automate these actions.

## How it works?
After cloning the script,

On your terminal, run the script:

```bash
$ ./ package-installer.sh
```

You will be prompted to choose the way you want to provide the packages to install.
We have 2 options:
* For the first option, you will provide all packages in the prompt and separate them with semicolons.
* For the second option, you will enter a txt file name. This file will contains all the packages to install; one package per line.
The script will read the packages from this file.
