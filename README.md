# Code Snippets Plugin
All code snippets can be easily imported as .json files into the Code Snippets plugin.

## Where to install the Code Snippets Plugin from

https://wordpress.org/plugins/code-snippets/

## How to Import the Code Snippets .json files

You will need to install and active Code Snippets Plugin on the website you want to import the .json files you want.

Please, take a look for the Snippets admin menu, when viewing from wp-admin.

So from Snippets > Import, select the .json file you want to import, then click on the Upload file and import button. Then from Snippets > All Snippets, active and deactivate code snippets as needed.

## Troubleshort

In case a code snippet breaks your website, please manually edit your wp-config.php file, and add the following:

```
define('CODE_SNIPPETS_SAFE_MODE', true);
```

Right before:

```
/* That's all, stop editing! Happy blogging. */
```

This will enable you to load the wp-admin again, and disable any code snippet that may be causing the issue.
