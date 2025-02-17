# How to Update SillyTavern

This is not an installation guide. If you need installation instructions, look here:
<https://docs.alpindale.dev/pygmalion-extras/sillytavern/#installation>

(This guide assumes you have already installed SillyTavern once and know how to run it on your OS.)

(A plain text copy of this file is also present inside SillyTavern's base install folder.)

----

## Linux/Termux

You definitely installed via git, so just 'git pull' inside the SillyTavern directory.

----

## Windows/MacOS

### Method 1 - GIT

We always recommend users install using 'git'. Here's why:

When you have installed via 'git clone', all you have to do to update is type 'git pull' in a command line in the ST folder.
The updates are applied automatically and safely.

### Method 2 - ZIP

If you insist on installing via a zip, here is the tedious process for doing the update:

1. Download the new release zip.
2. Unzip it into a folder OUTSIDE of your current ST installation.
3. Do the usual setup procedure for your OS to install NodeJS requirements.

4. Copy the following files/folders as necessary(*) from your old ST installation:

  (*) 'As necessary' = "If you made any custom content related to those folders".
  None of the folders are mandatory, so only copy what you need.

#### NB: DO NOT COPY THE ENTIRE /PUBLIC/ FOLDER

  Doing so could break the new install and prevent new features from being present.

```plaintext
Backgrounds
Characters
Chats
Groups
Group chats
KoboldAI Settings
NovelAI Settings
OpenAI Settings
TextGen Settings (textgen = ooba)
Themes
User Avatars
Worlds
settings.json
```
  
5. Once those folders/files are copied, Paste them into the /Public/ folder of the new install.

6. Start SillyTavern once again with the method appropriate to your OS, and pray you got it right.

7. If everything shows up, you can safely delete the old ST folder.
