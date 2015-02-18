HBC
===

HandBrake Cutter (HBC) is a command-line wrapper for HandBrakeCLI that cut or extract video clips by human-readable time.

## Requirements

Make sure you have installed the [command line version of HandBrake](https://handbrake.fr/downloads2.php) and place the binary into any "PATH" (e.g. /usr/local/bin).

## Usage

Time format are HH:MM:SS or MM:SS, or SS (simply seconds):

    $ hbc FILENAME START-TIME STOP-TIME

## Example

To extract video from 00:34 (0 minute 34 seconds) to (1 minute 57 seconds):

    $ hbc sample.mp4 00:34 01:57

To extract video from 00:01:10 (0 hour, 1 minute and 10 seconds) to 01:23:14 (1 hour, 23 minutes and 14 seconds):

    $ hbc sample.mp4 00:01:10 01:23:14
