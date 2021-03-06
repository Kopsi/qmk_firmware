## Layout

### Keymap 0: Basic layer
```
,--------------------------------------------------.           ,--------------------------------------------------.
|   `    |   1  |   2  |   3  |   4  |   5  |  =   |           |  L1  |   6  |   7  |   8  |   9  |   0  |   -    |
|--------+------+------+------+------+-------------|           |------+------+------+------+------+------+--------|
| TAB    |   Q  |   W  |   E  |   R  |   T  |  L1  |           |  L2  |   Y  |   U  |   I  |   O  |   P  |   \    |
|--------+------+------+------+------+------|      |           |      |------+------+------+------+------+--------|
| Esc    |   A  |   S  |   D  |   F  |   G  |------|           |------|   H  |   J  |   K  |   L  |   ;  |   '    |
|--------+------+------+------+------+------|  L2  |           |TT(3) |------+------+------+------+------+--------|
| LShift |Z/Ctrl|   X  |   C  |   V  |   B  |      |           |      |   N  |   M  |   ,  |   .  |//Ctrl| RShift |
`--------+------+------+------+------+-------------'           `-------------+------+------+------+------+--------'
  |LCTRL |  F4  |  F5  | LGUI | LALT |                                       | Left | Down |  Up  | Right| RGUI |
  `----------------------------------'                                       `----------------------------------'
                                       ,-------------.       ,-------------.
                                       | Copy | Paste|       | Copy | Paste  |
                                ,------|------|------|       |------+--------+------.
                                |      |      | PgUp |       | PgDn |        |      |
                                | Bcksp|OSL(2)|------|       |------|  Ent   |Space |
                                |      | VIM  | Del  |       |OSL(2)|        |      |
                                `--------------------'       `----------------------'
```
* For a single tap or single hold, OSL behaves like OSL(SYMB). For a tap + hold, it behaves like MO(VIM).

### Keymap 1: Code Layer
```
,--------------------------------------------------.           ,--------------------------------------------------.
|        |      |      |      |      |      |      |           |      |      |      |      |      |      |        |
|--------+------+------+------+------+-------------|           |------+------+------+------+------+------+--------|
|        |      |      |      |      |      |  F10 |           |  F11 |      |      |      |      |      |        |
|--------+------+------+------+------+------|      |           |      |------+------+------+------+------+--------|
|        |      |      |      |      |      |------|           |------|      |      |      |      |      |        |
|--------+------+------+------+------+------|  L2  |           |      |------+------+------+------+------+--------|
|        |      |      |      |      |      |      |           |      |      |      |      |      |      |        |
`--------+------+------+------+------+-------------'           `-------------+------+------+------+------+--------'
  |      |      |      |      |      |                                       | F12  |GoToIm| FAR  |      |      |
  `----------------------------------'                                       `----------------------------------'
                                       ,-------------.       ,---------------.
                                       |Format|Build |       | Copy | Paste  |
                                ,------|------|------|       |------+--------+------.
                                |      |      |Refact|       |  Up  |        |      |
                                |      |      |------|       |------|        |      |
                                |      |      |      |       | Down |        |      |
                                `--------------------'       `----------------------'
```
* Build  - Visualt Studio Build Solution. Sends `CTRL + SHFT + B`
* FAR    - Visual Studio Find All References. Sends `CTRL + K, R`
* Format - Visual Studio Format. Sends `CTRL + K, CTRL + D`
* GoToIm - Visual Studio Go To Implementation. Sends `CTRL + F12`
* Refact - Visual Studio Refactor. Sends `CTRL + R, R`
* Sort U - Visual Studio Sort Usings. Sends `CTRL + R, CTRL + G`


### Keymap 2: Symbol Layer
```
,---------------------------------------------------.           ,--------------------------------------------------.
|Version  |  F1  |  F2  |  F3  |  F4  |  F5  |      |           |      |  F6  |  F7  |  F8  |  F9  |  F10 |   F11  |
|---------+------+------+------+------+------+------|           |------+------+------+------+------+------+--------|
|         |   !  |   @  |   (  |   )  |   |  |      |           |      |   Up |   7  |   8  |   9  |   *  |   F12  |
|---------+------+------+------+------+------|      |           |      |------+------+------+------+------+--------|
|         |   #  |   $  |   {  |   }  |   `  |------|           |------| Down |   4  |   5  |   6  |   +  |        |
|---------+------+------+------+------+------|      |           |      |------+------+------+------+------+--------|
|         |   %  |   ^  |   [  |   ]  |   ~  |      |           |      |   &  |   1  |   2  |   3  |   \  |        |
`---------+------+------+------+------+-------------'           `-------------+------+------+------+------+--------'
  | EPRM  |      |      |      |      |                                       |   0  |   0  |   .  |   =  |      |
  `-----------------------------------'                                       `----------------------------------'
                                       ,-------------.       ,-------------.
                                       |      | Caps |       |      |      |
                                ,------|------|------|       |------+------+------.
                                |      |      |APscr |       |      |      |      |
                                |      |      |------|       |------|      |      |
                                |      |      | PScr |       |      |      |      |
                                `--------------------'       `--------------------'
```
* APscr - Take a printscreen of the current app. Sends `Alt + Print Screen`

### Keymap 3: Media and Mouse Keys
```
,--------------------------------------------------.           ,--------------------------------------------------.
|        |      |      |      |      |      |      |           |      |      |      |      |      |      |        |
|--------+------+------+------+------+-------------|           |------+------+------+------+------+------+--------|
|        |      |      | MsUp |      |      |      |           |      |      |      |      |      |      |        |
|--------+------+------+------+------+------|      |           |      |------+------+------+------+------+--------|
|        |      |MsLeft|MsDown|MsRght|      |------|           |------|      |      |      |      |      |        |
|--------+------+------+------+------+------|      |           |      |------+------+------+------+------+--------|
|        |      |      |      |      |      |      |           |      |      |      |      |      |      |        |
`--------+------+------+------+------+-------------'           `-------------+------+------+------+------+--------'
  |      |      |      | Lclk | Rclk |                                       |      |      |      |      |      |
  `----------------------------------'                                       `----------------------------------'
                                       ,-------------.       ,-------------.
                                       | Back+| Back-|       | Vol+ |      |
                                ,------|------|------|       |------+------+------.
                                |      |      |BL_TOG|       | Vol- |      |      |
                                |      |      |------|       |------| PL/PS| Next |
                                |      |      |      |       | Back |      |      |
                                `--------------------'       `--------------------'
```

### Keymap 4: Movement
```
,--------------------------------------------------.           ,--------------------------------------------------.
|        |      |      |      |      |      |      |           |      |      |      |      |      |      |        |
|--------+------+------+------+------+-------------|           |------+------+------+------+------+------+--------|
|        |KOpen |KType | LSFT |      |      |      |           |      | Copy |      |      |      | Paste|        |
|--------+------+------+------+------+------|      |           |      |------+------+------+------+------+--------|
|        |DLeft |DRight| LCTL | LGUI |      |------|           |------| Left | Down |  Up  | Right|      |        |
|--------+------+------+------+------+------|      |           |      |------+------+------+------+------+--------|
|        |SFT_TB| Tab  |      |      |      |      |           |      |      |      |      |      |      |        |
`--------+------+------+------+------+-------------'           `-------------+------+------+------+------+--------'
  |      |      |      |      |      |                                       |      |      |      |      |      |
  `----------------------------------'                                       `----------------------------------'
                                       ,-------------.       ,-------------.
                                       |      |      |       | Home | End  |
                                ,------|------|------|       |------+------+------.
                                |      |      |      |       |      |      |      |
                                |      |      |------|       |------|      |      |
                                |      |      |      |       |      |      |      |
                                `--------------------'       `--------------------'
```
* DLeft  - Move to the left Desktop. Sends `Ctrl + Win + Left Arrow`
* DRight - Move to the right Desktop. Sends `Ctrl + Win + Right Arrow`
* KOpen  - Opens KeePass. Sends `Ctrl + Alt + k`
* KType  - Autotypes KeePass password. Sends `Ctrl + Alt + a`
* SFT_TB - Sends `CTRL + TAB`.
