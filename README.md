# vscode-settings

![image](https://user-images.githubusercontent.com/1501327/158923759-b2b8453b-a83e-4120-93b1-56f20475202b.png)

![image](https://user-images.githubusercontent.com/1501327/156951152-c310fe78-87b7-413b-a99a-1dc1fd3f55e3.png)

![image](https://user-images.githubusercontent.com/1501327/156951355-9678fd88-980f-4b69-8e17-229757db1de2.png)

![image](https://user-images.githubusercontent.com/1501327/156951268-0755695a-b502-4d79-b3a4-d200e6940f9e.png)

![image](https://user-images.githubusercontent.com/1501327/156951541-8005c5a6-1092-47a6-858d-29d4d6ca8456.png)

![image](https://user-images.githubusercontent.com/1501327/156951719-32102d19-5e2d-4bf8-87bc-2d6c7743c37d.png)

![image](https://user-images.githubusercontent.com/1501327/156952057-8becd434-f998-4d2e-ba0d-b8d214476e6a.png)
```json
		"commands": [
			{
				"command": "extension.runTerminalCommand",
				"-title": "Run Terminal Command...",
				"title": "🟥 ターミナルコマンド"
			}
		],
```
![image](https://user-images.githubusercontent.com/1501327/156953377-5f236079-ca2c-4364-b876-e5e4d26bb8a2.png)

![image](https://user-images.githubusercontent.com/1501327/156953674-133664da-f61f-4995-ad6d-cf2644b86ad7.png)



### ダウンロード
[vscode 用ワ－ススペーステンプレート](https://github.com/winofsql/subject)

![image](https://user-images.githubusercontent.com/1501327/156952692-e577f2f1-edee-4c72-9803-a467d0609875.png)

![image](https://user-images.githubusercontent.com/1501327/156955258-4a5992f1-2b10-459a-baa8-e522cf2eefa8.png)

![image](https://user-images.githubusercontent.com/1501327/156955190-92e14c26-c7e5-48ba-a5df-cbd5044d8dbb.png)

![image](https://user-images.githubusercontent.com/1501327/156955381-4bed881a-809b-433e-b548-2855804f4b39.png)

![image](https://user-images.githubusercontent.com/1501327/156955452-a837249e-6a87-46aa-b9cd-34b99f17f126.png)

![image](https://user-images.githubusercontent.com/1501327/156955541-30153aa2-c39d-4432-b7d0-1dbdc7c7d2dd.png)

![image](https://user-images.githubusercontent.com/1501327/156957195-29a43539-b5bf-48db-9f8b-99ae7479bd46.png)

![image](https://user-images.githubusercontent.com/1501327/156957355-5fb32419-9b4e-4066-a639-14038a3637ae.png)

### settings.json
```json
{
    "-files.encoding": "shiftjis",
    "files.autoSave": "afterDelay",
    "editor.mouseWheelZoom": true,
    "editor.renderWhitespace": "all",
    "editor.unicodeHighlight.includeComments": true,
    "editor.detectIndentation": false,
    "window.zoomLevel": 1,
    "workbench.startupEditor": "none",
    "security.workspace.trust.untrustedFiles": "open",
    "workbench.iconTheme": "material-icon-theme",
    "material-icon-theme.folders.color": "#bfc553",
    "material-icon-theme.opacity": 0.8,
    "material-icon-theme.showWelcomeMessage": false
}
```

![image](https://user-images.githubusercontent.com/1501327/156961781-999040d9-8edf-46ea-94fd-9027663fdff1.png)

### vscode-icon.reg
```reg
Windows Registry Editor Version 5.00

[HKEY_CLASSES_ROOT\VSCode.code-workspace]
@="Code Workspace ソース ファイル"

[HKEY_CLASSES_ROOT\VSCode.code-workspace\DefaultIcon]
@="C:\\app2\\Microsoft VS Code\\Code.exe"

[HKEY_CLASSES_ROOT\VSCode.code-workspace\shell]

[HKEY_CLASSES_ROOT\VSCode.code-workspace\shell\open]
"Icon"="\"C:\\app\\Microsoft VS Code\\Code.exe\""

[HKEY_CLASSES_ROOT\VSCode.code-workspace\shell\open\command]
@="\"C:\\app2\\Microsoft VS Code\\Code.exe\" \"%1\""


```

![image](https://user-images.githubusercontent.com/1501327/158924632-9de83715-b611-49e5-81c2-33efc437e074.png)

> 他の PC の C:\Users\ユーザ名\.vscode をコピーするのが効率的です
