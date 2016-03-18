## Description

This plugin pulls all files in each specified directory, and checks their created time against the current time.  If the maximum age of any file is exceeded, a warning/critical message is returned as appropriate.

This is useful for examining backup directories for freshness.

The only requirement is the bash shell interpreter, which most systems have installed by default.

Tested to work on Linux/FreeBSD/OS X.

## Usage ##

Run the plugin with the --help argument for a full description of all arguments, example usage, and caveats.

The included utils.sh script is required for this plugin to run properly, and must be placed in the same directory as the plugin. On RHEL/CentOS systems, it is provided by the ```nagios-plugins``` package, and is provided here for other use cases.

## Support

The issue tracker for this project is provided to file bug reports, feature requests, and project tasks -- support requests are not accepted via the issue tracker. For all support-related issues, including configuration, usage, and training, consider hiring a competent consultant.
