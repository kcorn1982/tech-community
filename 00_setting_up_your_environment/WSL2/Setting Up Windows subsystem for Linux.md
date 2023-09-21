In this tutorial we will get set up with WSL2 on our Windows system. 
	
1. Install Windows Terminal
	1. To install the Windows Terminal, you can install it through the Microsoft Store, [here](https://aka.ms/terminal).
	2. Set Windows Terminal as you default command line app.
		1. Open you Windows Terminal. 
		2. Click the 'more' chevron. Go to settings
		3. In Startup, select 'Windows Terminal' as your default terminal application. 
		4. In Default Profile, you can change which command line the terminal will start with. You can select Command Prompt here, or just leave it set as Powershell.

1. Install WSL2
	1. wsl --install this will install the Ubuntu kernel on your system
		1. If you have a favour flavor of Linux:
			1. You can check the available distributions be running the command: wsl -l -o
			2. And, from the available options:
				1. wsl --install -d <Distro name> replacing the <Distro name> with your choosen flavor of Linux.
	2. You should now be able to open Linux in your Windows Terminal...
		1. The next step is to create username and  password.
			1. Note: The Linux shell uses blind typing, while entering your password nothing will appear. Don't panic! 
			2. This will be both your default user details and the Linux administrator account.
	3. Finally, ensure your distribution is up to date.
		1. Run the command sudo apt update && sudo apt upgrade
	4. And, you are done installing the Linux sub-system.
2. Map WSL2 to your C drive
	1. [To Be Added]
3. Install WSL2 extension in VSCode
	1. In VSCode, go to Extensions.
	2. Search for 'Remote Development'
	3. You want 'Remote Development(preview) by microsoft.com. Select it.
	4. and click 'Install'

That's it. You are all set up.

For more information:
[Windows Terminal installation | Microsoft Learn](https://learn.microsoft.com/en-us/windows/terminal/install)
[Install WSL | Microsoft Learn](https://learn.microsoft.com/en-us/windows/wsl/install)
[Get started using VS Code with WSL | Microsoft Learn](https://learn.microsoft.com/en-us/windows/wsl/tutorials/wsl-vscode?source=recommendations#install-vs-code-and-the-wsl-extension)
