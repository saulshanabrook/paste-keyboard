# Why
Some mac dialogues (password prompts) do not allow pasting into the password fields. This is cumbersome if you use a password manager and do not want to type out your long password.
# How
Running this applescript will get the clipboard contents and type each character indivually. Obviously all style will be lost. I created a Service in Automator that recieves no input and is runnable anywhere, with a "Run AppleScript" action for this script. ![Automator Screenshot](http://cl.ly/image/2q0p101p0e2sg "Automator Screenshot")
