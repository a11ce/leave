# leave
```

tell application "Google Chrome"

	
	execute front window's active tab javascript "location = 'https://web.groupme.com/chats';"
	delay 3
	execute front window's active tab javascript "document.querySelector('[title=\"CRC 2020-21\"]').click();"
	delay 3
	execute front window's active tab javascript "document.querySelector('[aria-label=\"Open group CRC 2020-21 sidebar\"]').click();"
	delay 3
	execute front window's active tab javascript "document.querySelector('[translate=\"Group.Sidebar.Settings\"]').click();"
	delay 3
	execute front window's active tab javascript "document.querySelector('[translate=\"Group.Settings.LeaveGroup\"]').click();"
	delay 3
	execute front window's active tab javascript "document.querySelector('[ng-click=\"accept()\"]').click();"
	delay 3
end tell
```
