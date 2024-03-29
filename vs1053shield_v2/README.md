## yoradio VS1053B Shield rev2.2
<img src="vs1053shield_v2_01.jpg" width="240" height="auto" />

---
- [Gerber files](vs1053shield_v2.2_GBR.zip)
- [Bill of materials](vs1053shield_v2_BOM_aliexpress.pdf)
- [Schematic](vs1053shield_v2.2_SCH.pdf)
- [Preview](vs1053shield_v2_02.jpg)

## myoptions.h
#### Base config, without display and controls
```
#define LED_BUILTIN          2
#define I2S_DOUT             255
#define VS1053_CS            27
#define MUTE_PIN             13
#define MUTE_VAL             LOW
```
---
#### Advanced config
```
#define LED_BUILTIN          2
#define DSP_MODEL            DSP_<your_display>
#define I2S_DOUT             255
#define VS1053_CS            27
#define MUTE_PIN             13
#define MUTE_VAL             LOW
/* Uncomment this if you are using an IR receiver */
//#define IR_PIN               14
/* Uncomment this if you are using an Encoder1 */
//#define ENC_BTNL             34
//#define ENC_BTNB             39
//#define ENC_BTNR             36
//#define ENC_INTERNALPULLUP   false
/* Uncomment this if you are using an Encoder2 */
//#define ENC2_BTNL            33
//#define ENC2_BTNB            32
//#define ENC2_BTNR            35
//#define ENC2_INTERNALPULLUP  false
```
