# CS2 Config

Counter-Strike 2 config setup.

---

## Crosshair Cycler

Located in `custom/crosshair-cycler.cfg`

### Features

| Feature | Description |
|---------|-------------|
| **7 Presets** | Switch between A-G crosshairs |
| **Cycle Key** | Press `P` to cycle through presets |
| **Nade Tool** | Toggle with `F5` for smoke/molotov alignment |

### Crosshair Presets

| Preset | Style | Size | Thickness | Gap | Outline | Special |
|--------|-------|------|-----------|-----|---------|---------|
| **A** | Standard Double | 2.0 | 0.5 | 0 | 1px | - |
| **B** | Tighter Gap | 1.6 | 0.5 | -2 | 0.5px | Subtle outline |
| **C** | Dot | 2.0 | 1.0 | 9999 | 1px | Dot enabled |
| **D** | Thin Standard | 2.3 | 0.1 | 0 | 1px | Minimal width |
| **E** | Thick Center | 1.0 | 8.0 | -7 | None | Recoil tracking ON |
| **F** | Tight Minimal | 2.2 | 0.5 | -4 | None | **Default** |
| **G** | Thin Lines | 1.0 | 0 | -4 | None | No thickness |

### Binds

```console
// Cycle to next crosshair (with sound feedback)
P

// Toggle nade alignment tool ON/OFF
F5
```

### Commands

```console
// Show current crosshair settings (opens console)
ch
```

---

## Crosshair Color Cycler

Located in `custom/crosshair-color-cycler.cfg`

### Features

| Feature | Description |
|---------|-------------|
| **10 Colors** | Cycle through preset crosshair colors |
| **Cycle Key** | Press `O` to cycle through colors |
| **Sound Feedback** | Plays `ui/menu_focus` sound on each cycle |

### Colors

| Order | Color | cl_crosshaircolor | RGB Values |
|-------|-------|-------------------|------------|
| 1 | Green | 1 | Default |
| 2 | Yellow | 2 | Default |
| 3 | Dark Blue | 3 | Default |
| 4 | Cyan | 4 | Default |
| 5 | Red | 5 | 255, 0, 0 |
| 6 | White | 5 | 255, 255, 255 |
| 7 | Black | 5 | 0, 0, 0 |
| 8 | Pink | 5 | 255, 192, 203 |
| 9 | Purple | 5 | 160, 32, 240 |
| 10 | (cycles back to Green) | - | - |

### Binds

```console
// Cycle to next crosshair color (with sound feedback)
O
```

---

## Viewmodel Cycler

Located in `custom/viewmodel-cycler.cfg`

### Features

| Feature | Description |
|---------|-------------|
| **6 Presets** | Switch between viewmodel positions |
| **Cycle Key** | Press `[` to cycle through presets |
| **Sound Feedback** | Plays `player/geiger1` sound on each cycle |

### Presets

| Preset | Description | Offset X | Offset Y | Offset Z |
|--------|-------------|----------|----------|----------|
| **preset1** | Default CS2 position | Default | Default | Default |
| **preset2** | Alternative default | Default | Default | Default |
| **gangsta** | Raised right viewmodel | 2.5 | -1 | 2 |
| **butt** | Far bottom-left viewmodel | -2 | -2 | 2 |
| **doom** | Low left viewmodel | -2 | -2 | -1.5 |
| **preset1_low** | Close low position | 2.5 | 2 | -2 |

### Binds

```console
// Cycle to next viewmodel preset (with sound feedback)
[
```

### Commands

```console
// Show current viewmodel offsets (opens console)
vm
```

---

## Files

| File | Purpose |
|------|---------|
| `autoexec.cfg` | Main config that loads all custom files on startup |
| `custom/crosshair-cycler.cfg` | Crosshair presets and cycling system with nade alignment tool |
| `custom/crosshair-color-cycler.cfg` | Crosshair color presets with 10-color cycling system |
| `custom/viewmodel-cycler.cfg` | Viewmodel position presets with 6 preset cycling system |
