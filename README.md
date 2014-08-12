## SublimeText Redmine Client

SublimeText Plugin to interact with Redmine right in your editor.

### Quick Start
- Clone/download plugin to your SublimeText User folder under SubRed

### Configure

##### Basic
Set the `redmine_url` and `api_key` in `Preferences: Package Settings > SubRed > Settings – User`:

```
{
  "redmine_url" : "URL to your Redmine",
  "api_key": "Set your Redmine API Key"
}
```

##### Hotkeys
`Preferences: Package Settings > SubRed > Key Bindings – User`:

Available commands:

`sub_red` - Open Issue

`sub_red_set_status` - Set Issue Status

`sub_red_get_query` - List Queries

Hotkeys configuration:

```
  {
    "keys": ["shift+command+k"],
    "command": "sub_red"
  },
  {
    "keys": ["shift+command+h"],
    "command": "sub_red_set_status"
  },
  {
    "keys": ["shift+command+l"],
    "command": "sub_red_get_query"
  }
```

### Functions

	- View issue in SublimeText
	- Change issue state
	- View Queries list and issues from particular query

### Showtime!
![Query](screenshots/subred_show.gif?raw=true)

### Why?

I really hate to open browser, navigate to Redmine.

