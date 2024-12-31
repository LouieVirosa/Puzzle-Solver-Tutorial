## Installation

You will need an internet connection to load the following python packages
used in this lesson.

in linux, installation is straightforward:

```bash
pip install -r requirements.txt
```

In Windows, you will need Visual Studio as well as Visual Studio Build Tools, but the pip installation command is identical.


## Run

```bash
cd (this_directory)
jupyter notebook

open a browser to http://localhost:8888
```

NOTE: If there is any problem locating the jupyter executable, try:

```bash
python3 -m site --user-base
```

to find where pip install jupyter... call it from there. (might be $HOME/.local/bin)
