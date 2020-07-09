# minimalJupyterNotebook
Minimal personal Jupyter notebook launcher

This repo file contains a simple manifest file that defines a configuration capable of launching a minimal Jupyter notebook server on [Reclaim Cloud](https://reclaim.cloud/).

[![](http://img.shields.io/static/v1?label=Reclaim&message=launch&color=blue)](https://app.my.reclaim.cloud/?jps=https://github.com/ousefulReclaimed/minimalJupyterNotebook/blob/master/manifest.jps)

Clicking the button will automatically load the manifest file from this repo in your [Reclaim Cloud console](https://app.my.reclaim.cloud) if you are already logged in.

![](.images/Reclaim_Cloud_Dashboard_install.png)

If you want to load the file manually, copy the raw file URL from the Github repo:


![](.images/minimalJupyterNotebook_manifest_jps.png)

And then add paste it into the new environment *Import* from *URL* dialogue:

![](.images/Reclaim_Cloud_Dashboard_jps.png)

When you hit the *Import* button, the environment will be created:


![](.images/Reclaim_Cloud_Dashboard_waiting.png)

*This may take some time...*

When it's ready:

![](.images/Reclaim_Cloud_Dashboard_ready.png)

you can click on the automatically generate URL to go to your enviroment:

![](.images/Jupyter_Notebook_served.png)

If you forget to take note of the environment, launch the environment console, and echo the token value (`echo $JUPYTER_TOKEN`):

![](.images/Reclaim_Cloud_Dashboard_recover.png)


If you want to review all the environment variables, run the command: `printenv`


