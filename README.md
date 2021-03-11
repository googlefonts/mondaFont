# Monda Font Project
by Vernon Adams

The Monda font family is a free font family. The Monda Fonts are designed to be used freely across the internet by web browsers on desktop computers, laptops and mobile devices.

This project is a fork from the old Vernon Adams font repository hosted at [GitHub](https://github.com/vernnobile/mondaFont)

# Changelog:
- 25 November 2012 - v.1 - First release of Regular and Bold weights.
- 12 February 2021 - v.2 - Release of V2 with updated character set to support African Latin.
- 09 March 2021 - v.2 - Fixed some issues related to diacritics position.


## Building the Fonts

The font is built using fontmake and gftools post processing script. Tools are all python based, so it must be previously installed.

To install all the Python tools into a virtualenv, do the following:

From terminal:

```

cd your/local/project/directory

#once in the project folder create a virtual environment. 
This step has to be done just once, the first time:

python3 -m venv venv

#activate the virtual environment

source venv/bin/activate

#install the required dependencies

pip install -r requirements.txt

```

Then run the this command:

```
cd sources
gftools builder config.yml
```
