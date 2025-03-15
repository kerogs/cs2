<div align="center">
<!-- <img alt="Profiles Pictures" src="" width="200" height="200"/> -->

<h3> Kerogs' CS2 configuration 🛠️</h3>

</div>

# kerogs.cfg - CS2 Configuration

This is my custom configuration for **CS2**

## How to Use

1. **Download** the `kerogs.cfg` file.
2. **Place it in the CS2 directory** : ``steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg``
3. **Launch 2** and open the console.
4. **Execute the config in console** by typing:
```sh
exec kerogs.cfg
```

## Configuration Breakdown

### 1. **Console Activation**
| Command             | Description                           |
|---------------------|---------------------------------------|
| `con_enable "true"`  | Enables the game console.             |

### 2. **Keyboard Shortcuts**
| Key    | Action                                             |
|--------|----------------------------------------------------|
| `²`    | Toggles the console (`bind "²" "toggleconsole"`)    |
| `Tab`  | Shows the scoreboard (`bind "tab" "+showscores"`)  |
| `N`    | Activates various match settings (unlimited buy time, respawn, etc.)  |

### 3. **Audio Settings**
| Command                           | Description                                             |
|------------------------------------|---------------------------------------------------------|
| `volume "0.53"`                    | Sets the game volume to 53%.                            |
| `bind "F3" "incrementvar volume 0 1 -0.025"` | Decreases volume by 2.5% on each press of F3.           |
| `bind "F4" "incrementvar volume 0 1 0.025"`  | Increases volume by 2.5% on each press of F4.           |
| `snd_mute_losefocus "false"`       | Keeps audio playing when alt-tabbed.                    |

### 4. **Voice Settings**
| Command                                | Description                                              |
|----------------------------------------|----------------------------------------------------------|
| `voice_modenable "true"`               | Enables voice communication.                             |
| `bind "CAPSLOCK" "voice_modenable_toggle"` | Toggles other players' voice volume with `Caps Lock`.    |
| `bind "MOUSE5" "+voicerecord"`        | Activates voice recording when pressing MOUSE5.           |
| `voice_always_sample_mic "true"`      | Ensures mic is always sampled for voice chat.             |

### 5. **Mouse Sensitivity**
| Command             | Description               |
|---------------------|---------------------------|
| `sensitivity "5.06"` | Sets the mouse sensitivity to `5.06`. |

### 6. **Viewmodel Customization**
| Command                              | Description                                          |
|--------------------------------------|------------------------------------------------------|
| `viewmodel_offset_x 2`               | Adjusts the horizontal offset of the weapon model.   |
| `viewmodel_offset_y 2`               | Adjusts the vertical offset of the weapon model.     |
| `bind "MOUSE4" "switchhands"`        | Switches hands when pressing the 4th mouse button.   |

### 7. **HUD Customization**
| Command                                       | Description                                      |
|-----------------------------------------------|--------------------------------------------------|
| `cl_showloadout "true"`                       | Shows the player's loadout on the HUD.           |
| `cl_radar_scale "0.4"`                        | Adjusts the radar scale.                        |
| `bind "[" "incrementvar cl_radar_scale 0.25 1 -0.05"` | Decreases radar scale.                         |
| `bind "]" "incrementvar cl_radar_scale 0.25 1 0.05"`  | Increases radar scale.                         |

### 8. **FPS Settings**
| Command           | Description                     |
|-------------------|---------------------------------|
| `fps_max "401"`   | Sets the max FPS to 401.        |
| `fps_max_ui "61"` | Limits the FPS for UI to 61.   |

### 9. **Crosshair Customization**
| Command                                | Description                                           |
|----------------------------------------|-------------------------------------------------------|
| `cl_crosshairstyle "4"`                | Sets the crosshair style to `4`.                       |
| `cl_crosshaircolor "1"`                | Sets the crosshair color to green.                     |
| `cl_crosshairsize "1"`                 | Sets the crosshair size.                              |
| `cl_crosshairgap "-4"`                 | Sets the gap of the crosshair to `-4`.                |

### 10. **Other Settings**
| Command                      | Description                                     |
|------------------------------|-------------------------------------------------|
| `bind "p" "toggle cl_showfps"` | Toggles the FPS counter.                       |
| `bind "F1" "autobuy"`         | Automatically buys default weapons.             |
| `bind "F2" "rebuy"`           | Rebuys the last set of items.                   |
| `bind "c" "say gg"`           | Sends "gg" in chat (good game).                 |

### 11. **Weapon and Grenade Bindings**
| Command                                | Description                                              |
|----------------------------------------|----------------------------------------------------------|
| `bind "a" "slot3; slot2"`             | Binds the `A` key to switch to primary and secondary weapons. |
| `bind "." "sv_rethrow_last_grenade"`  | Re-throws the last grenade.                              |
| `bind "/" "toggle sv_grenade_trajectory_prac_pipreview"` | Toggles grenade trajectory preview.                     |

### 12. **Final Settings**
| Command              | Description                         |
|----------------------|-------------------------------------|
| `host_writeconfig`    | Saves the current configuration.    |

## Credits

The configuration was inspired by various sources, including:

- **FranzJ**
- **acx0** - [https://github.com/acx0/cs2-cfg](https://github.com/acx0/cs2-cfg).
