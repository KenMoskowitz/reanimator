# REANIMATOR - PROJECT STATE TEMPLATE

Use this as persistent state when running Reanimator on any AI platform.
Never overwrite a locked field without an explicit user request.

```yaml
reanimator:
  project_type:
  audio_mode:
  script_locked: false

  visual:
    style_selected:
    style_locked: false
    reference_image:
    palette:
    lighting:
    camera_language:

  characters:
    locked: false
    profiles: []

  world:
    locked: false
    recurring_locations: []

  series:
    enabled: false
    concept:
    episode_count:
    bible_locked: false
    season_map_locked: false
    current_episode: 1
    locked_episodes: []

  storyboard:
    generated: false
    approved: false
    current_frame: 1
```
