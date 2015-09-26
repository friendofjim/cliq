# sfdc cli

When it comes to Salesforce.com data loads, the command line is your friend. It's a native function of your computer; the CLI interface uses native Salesforce.com data loader APIs; and it's fun.

This repo is a bare-bones example of a CLI setup, and calls a simple extraction from the Account object in Salesforce.com. In later commits, I plan to show examples of SFDC data manipulation via scripting (viz. how to store files locally and reference them later in your script; how to zip files together into an uberfile and post it to Chatter; sending data to Hive/Hadoop; etc).

Please note that this setup is optimized to run on Linux and Unix systems. If you're not on a Mac or a Linux box, then you won't be able to use this configuration out of the box.

Have some awesomeness to contribute? Create a branch!

One more thing: As you're getting started, I recommend heading over to https://code.google.com/p/dataloadercliq/ - Vijay Swamidass has provided the basic framework for setting up your CLI to work with data loads. His CLIq (Command Line Interface Quickstart) scripts automatically generate the basic files for you. He also provides a forum for bugs and user feedback.
