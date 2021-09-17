![Atlas scheme](https://www.oulu.fi/sites/default/files/styles/full_width/public/content-images/Atlas_image_0.jpg)


# Metagenome-atlas course Finnland 2021


**Schedule (three separate days)**
- Monday September 27
- Friday October 1 
- Monday October 4
Time: 9:15 – 12:30 + 13:30 - 17:00 EEST

**Important links**

- [Progress table](https://docs.google.com/spreadsheets/d/1b8uat67SvAM-4B8sMc1NhaiGlBxT_L24cb3LmdYZm5c/edit)
- [Announcements](https://github.com/metagenome-atlas/Tutorial_Finnland/discussions/2)
- [Issues](https://github.com/metagenome-atlas/Tutorial_Finnland/issues)
- [Course repo](https://github.com/metagenome-atlas/Tutorial_Finnland)


# Pre-work


**Please follow the following steps during the week leading up to the tutorial.**


Please note your progress in this [Progress table](https://docs.google.com/spreadsheets/d/1b8uat67SvAM-4B8sMc1NhaiGlBxT_L24cb3LmdYZm5c/edit), so that we can keep the overview.

If you encounter any problems during the pre-work or the tutorial, fill in an [issue on the Tutorial repo](https://github.com/metagenome-atlas/Tutorial_Finnland/issues) to tell us our problem. If you need help to login we will organize a meeting on Friday moring 24.9. To help you to do the steps. 

## To do list
1. Check again the schedule and put it in your agenda. We send a calender invitation if this helps. Keep in mind that the course is organised in the Finnish timezone (GMT+3). 
1. Create an account in [GitHub](https://github.com/)
    - Subscribe to the [announcements](https://github.com/metagenome-atlas/Tutorial_Finnland/discussions/2) on the tutorial repo.
    - Say hallo to the participants on [the forum](https://github.com/metagenome-atlas/Tutorial_Finnland/discussions).
2. If you are new to bash, we reccomend to follow [this module](https://linuxsurvival.com/)
3. Install a ssh client:
    - Windows users, you will need to download *[mobaxterm](https://mobaxterm.mobatek.net/)*
    - Mac users, use a terminal
4. Connect to the puhti server where we will run the pipeline (see below).


Please note your progress in the *progress table*.



## Setup
### Login to CSC

Look up your username in the Progress Table and the password I send in the first mail.
Open mobaxterm (on windows) or the terminal (on mac). Then Type:
    
    ssh username@puhti.csc.fi


### Setting up SSH keys

This is optional but makes login a lot easier.

This setup is done locally, so you need to logout of the remote machine:
`logout`

In mobaxtrem (windows) or your terminal (mac):
  
    ssh-keygen -t rsa -b 4096

You will be prompted for a file name and location where to save the key. Accept the defaults by pressing **ENTER**.
Next, you will be asked for a passphrase. Do **not** leave the passphrase empty.

Then copy the ssh key to puhti:

    ssh-copy-id yourcscusername@puhti.csc.fi

You will then be prompted for your passpharse.

Now you can login without password simply with:
  
    ssh yourcscusername@puhti.csc.fi






*Please note your progress in the progress table*.
