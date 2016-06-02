# Sencha Themer Example Workspace

This is a workspace that you can use to try out the Private EA release of Sencha Themer.

It contains two applications:

 * StarterApp - this is the standard app that gets generated when you run sencha generate app.
 * FeedViewer - a more complex app multi-tab that displays data from various news sites as well as the Sencha forums.

## Requirements

 * Sencha Cmd 6.2 EA

## Setup

After cloning the repo, use the following commands to get up and running:

    cd /path/to/sencha-themer-example-workspace/FeedViewer
    sencha app watch

This will download the latest version of Ext JS into the workspace, compile the app, and start a web server so you can view the FeedViewer app in your browser.

By default the apps should now be available via:

http://localhost:1841/FeedViewer

* Note: If you are running sencha app watch elsewhere, your port may very.  Check the output of sencha app watch for the correct URL.
