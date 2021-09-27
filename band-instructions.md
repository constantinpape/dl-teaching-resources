# EMBL DL-COURSE 2021 RESOURCES

For this year's deep learning course we will use BAND desktops, cloud based virtual desktops provided by EMBL as part of the EOSC Life project.

## Testing BAND

- Go to [band.embl.de](https://band.embl.de/#/eosc-landingpage) and click `LOGIN`.
- Use your Google account to log in
- This will open the `Launch Desktops` page
    - Select a suitable configuration in `Desktop configuration`, see example in the screenshot below.
    - Click `LAUNCH` and then `yes` in the prompt
    - Click `GO TO DESKTOP` in `Running desktops`
- This will open the virtual desktop in a new tab
- You can now use this desktop to use pre-installed software or install new software in your home directory
- The home directory is persistent, i.e. everything you create in it will still be there when you launch a new desktop
- The environment for the webinar exercises is already preinstalled via jupyterLab, you can access it via `Applications->Programming->DL Course`
- This will open jupyter lab. You can test it e.g. with the notebooks at https://github.com/constantinpape/dl-teaching-resources


## More information

- Users can install software or download data into their home data, which persists in between sessions.
- For more and faster storage `/tmp` can be used. It is temporary, i.e. will be lost after the session. Hence make sure to copy data you want to keep to your home directory.
- The required software and environments can be pre-installed (see example for `DL Course` environment above) so course participants don't need to set up everything on their own.
- Traning data or other large data-sets can be shared via the EMBL S3 data storage, which can be accessed via `Applications->Data Access->Mount EMBL S3 Bucket`
