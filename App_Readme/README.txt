How to install plugins:

- Go to C:\Program Files (x86)\JetBrains\ReSharper\v8.1\Bin
- if you don't find a Plugin folder there then you'll have to create it
- Create a folder with this Name ResharperExt (the name of the plugin's project)
- Put inside the dll of the plugin
- Regenerate the date in the registry if the plugin does not appear in your macro list:
	- open regedit and look for this key: One-Time Initialization Generation
	- change the value to the current date.