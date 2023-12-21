#  EditActionUnique

> [!CAUTION]
> Not released, just a specification

- The purpose is to make any  task for an action with the preset `edit` to be unique :
  - If offline, an edit could be in pending task
  - If launch a new edit, intead of creating a new task, the one in pending task will be opened

# Setting to activate the feature

##  MobileProject

> 🚧 how to inject inside mobile app for new projet?

##  Android

Inside `app/src/main/assets/appInfo.json`

```json
	"action.editAreUnique": true
```

##  iOS

Inside `Settings/Settings.plist`

```xml
	<key>action.editAreUnique</key>
	<true/>
```
