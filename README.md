# sd-webui-xyzplot-preset
Added a preset function to the XYZ plot script of SD-Web-UI  
Web-UIのXYZ plot scriptにプリセット機能を追加したものです。

## Install
xyzplot_s.pyをダウンロードして、`web-ui-root/scirpt`に入れて下さい。  
downonad xyzplot_s.py and put into `web-ui-root/scirpt`

## How to use
script一覧に`X/Y/Z plot S`が追加されます。
設定した後、`Preset name`に設定名を入れ、`Set XYZ plot as Preset`ボタンを押すとプリセットが作成されます。
`Set Mode`を`Overwrite`にすると上書きされます。DeleteにするとPresetが削除されます。
`Preset`を選択して`Load from preset`ボタンを押すと設定が読み出されます。

`X/Y/Z plot S` script will be added to the list of scripts. After setting up, enter the preset name in the `Preset name` field and click the `Set XYZ plot as Preset` button to create the preset. If you set `Set Mode` to `Overwrite`, it will overwrite the existing settings. If set to `Delete`, the preset will be deleted. Select `Preset` and click the `Load from preset` button to load the settings.
