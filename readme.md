# Server Connection Script

*A better name will come in the future*

## What is it?

Server connection Script, or scs, is a lazy mans ssh connection tool to help eleviate some of the tedious connections settings. Instead of using code like `ssh -P xxx -i /location/of/key user@example.com` and having to remember every line for each server, or having to manually add new Hosts to the `.ssh/config` file for each server, this script will help.

Everytime you launch scs, it will prompt you will a few choices of what you'd like to do. Things like;

- Add a new server
- Connect to server
- Edit existing server

etc.

## How to use it

scs will automatically edit all the neseccary files when you add, edit, or remove servers. All that the user is required to do is to input simple commands like `scs` or `scs connect ` or `scs remove ` etc. Using `scs` will open an interactive cli.

## How do I install this?

SCS is written in sh. Any computer that can process sh will be able to use this. You will need ssh installed on your computer first.

## What makes this different from other ssh tools?

This is a tool for the cli only. Any one who wants to use a GUI should look elsewhere. I preffer the cli when connecting to my servers.

## Can I help with the project?

Of course. Extra hands is always welcome.

## Can I fork this?

Of course. Power to FOSS.


