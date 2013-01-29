# Why
Some mac dialogues (password prompts) do not allow pasting into the password fields. This is cumbersome if you use a password manager and do not want to type out your long password.
# How
Running this applescript will get the clipboard contents and type each character indivually. Obviously all style will be lost. I created a Service in Automator that recieves no input and is runnable anywhere, with a "Run AppleScript" action for this script. ![Automator Screenshot](http://f.cl.ly/items/3U2s3l2k2T0Q1x1t3Y2J/Screen%20Shot%202013-01-29%20at%203.35.22%20PM.png "Automator Screenshot")
