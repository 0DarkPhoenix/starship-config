# 🚀 Starship

Starship installation: https://starship.rs/guide/

# Initialize on other devices
## 1. Clone the repository
### Windows
```
git clone https://github.com/0DarkPhoenix/starship-config.git %USERPROFILE%\.config\starship
```

### MacOS & Linux
```
git clone https://github.com/0DarkPhoenix/starship-config.git ~/.config/starship
```

## 2. Add STARSHIP_CONFIG variable to point to `starship.toml` folder inside `~/.config/starship`
### Windows
```
setx STARSHIP_CONFIG %USERPROFILE%\.config\starship\starship.toml
```

### MacOS & Linux
```
export STARSHIP_CONFIG="~/.config/starship/starship.toml"
```

> [!NOTE]
> Refresh the terminal config or restart the terminal instance for the environment variables to take effect

# Update lazyvim config from remote
```
git pull --ff-only
```
