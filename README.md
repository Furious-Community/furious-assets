# furious-assets
The assets used on Furious servers.

Upload your custom content:

    Copy the materials, models, and sounds into the respective subfolders.

Add the custom content to your server's game configuration:

    Open the server.cfg file located in the csgo/cfg directory of your server.
    Add the following lines to the end of the file:

    sv_downloadurl "http://yourserver.com/csgo/"
    sv_allowdownload 1
    sv_allowupload 1

    Replace http://yourserver.com/csgo/ with the URL of your custom content folder.

Restart your server:

    Restart your server to apply the changes and make the custom content available to your players.

That's it! The custom materials, models, and sounds used by Furious Gaming are now installed and ready to go. If you run into any issues, make sure your custom content is correctly placed in the right folders. Also, double-check that your server.cfg file is correctly configured to allow downloads and uploads.
