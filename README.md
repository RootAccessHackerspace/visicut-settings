# Visicut Settings

Settings for [VisiCut](https://github.com/t-oster/VisiCut) used by Root Access Hackerspace

VisiCut is used to prepare, save, and send jobs to the K40 laser cutter.

Control for the laser cutter are provided by [k40-laser-scripts](https://github.com/RootAccessHackerspace/k40-laser-scripts)

Directions (and most of this README) have been adapted from [FAU FabLab](https://github.com/fau-fablab)

## Instructions

### Initialize
 * Delete your settings before you clone this repo, if they exist:
    
    ```bash
    rm -rf ~/.visicut/
    ```

 * Clone the repo to `.visicut`:
    
    ```bash
    git clone git@github.com:RootAccessHackerspace/visicut-settings.git .visicut
    ```
    If that doesn't work, you may need to use HTTPS instead of SSH:
    ```bash
    git clone https://github.com/RootAccessHackerspace/visicut-settings.git .visicut
    ```
    However, you will not have push access to the main repo, and any changes you wish to submit will have to bit in the form of a pull request.

### Update
To update your settings, run:
```bash
cd ~/.visicut
git pull
```

### Updating/pushing settings
You either need SSH+write access to this repo, or (ideally) fork this repo and after commiting/pushing your changes, submit a pull request.
Make sure to include plenty of information as to what you changed in the settings so that the pull request can be expedited.

## Hackerspace info
You might not need to do this, as a current (2017/12/6) goal is to have the settings initialized when your account is created.
Ask the current laser administrator, Dylan ([@dylarm](https://github.com/dylarm)).

Until a method of dealing with merge conflicts semi-automatically is devised, settings with not automatically update.
If you don't want to monitor for updates on here, you can always monitor our [#github Slack channel](https://root-access.slack.com/messages/C86SU5VK2/).
