# Sb3-to-exe
Convert Scratch 3 file to Windows Executable in just 2 mins with Node.js.


## Setting up ur Device

- Download Node.js from [here](https://nodejs.org/en/download/current/) .
- Open Node.js Command Promp from ur Desktop.
- Type the given code when u start:

```
   $ npm install nativefier -g   
  ```
  Let this process end. *This is a one-time process and need not be cariied out everytime u create an app*
  
## Preparing ur Scratch Project
  
  Nativefier permits access to th entire web server once an app is built in stead of just one web-page it has been confined to. So we must package a Scratch project is such a way that the page doesn't have any links with other pages in the given server. Hence, the scratch project should be packaged in Forkphorus in stead of Turbowrap or packaging in HTMLifiers.
  Follow these steps to package in Forkphorus:
  
- Go to [forkphorus.github.io](forkphorus.github.io)
- Enter your scratch project link in the link box.
- Check all needed boxes and click on `Package` button.
- Keep the link of the project u r redirected to, for u will need this.

## Converting to Executable

It is a very easy **command line** that converts ur forkphorus web-page to a native executable file.
