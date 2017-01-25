# Competitve Programming
## Sublime Text 3 (c++)
``input.io`` нэртэй файлыг эх кодны байгаа газарт үүсгэж, бодлогийн ОРОЛТ-г оруулж өгнө. Build + compile үйлдэл хамт хийгдэх учраас гараас Ctrl+B дарахад хангалттай. ГАРАЛТ терминал цонх нээгдэж, гарна.

PS: Файлаас унших, файлруу бичих код нэмж бичих шаардлагагүй standart input/output ашиглахад болно. Мөн хязгааргүй давталтанд орсон тохиолдолт xterm цонхыг ``xkill``-р устгаж болно.

Build system: 
```
{
	//"cmd": ["g++ ${file} && xterm -hold -e \"./a.out < input.io > output.io\""], /*Хэт их гаралттай үед*/
	"cmd": ["g++ ${file} && xterm -hold -e \"./a.out < input.io\""], 
	"file_regex": "^(..[^:]*):([0-9]+):?([0-9]+)?:? (.*)$",
	"working_dir": "${file_path}",
	"selector": "source.c++",
	"shell": true
}
```
User settings:

``auto_complete, auto_match`` нь автоматаар ```{}, [], (), ""``` гэх мэт хаалтууд хаагддаг тохиргоог удирдана. 
```
{
	"auto_complete": false,
	"auto_indent": true,
	"auto_match_enabled": false,
	"color_scheme": "Packages/Color Scheme - Default/Solarized (Dark).tmTheme",
	"font_face": "Roboto Mono Medium",
	"font_size": 10,
	"ui_seperator": true,
	"ui_fix_tab_labels": true,
	"ui_font_size_small": true
}
```

# Competitive Gaming
## StarCraft 2 
1. StarCraft 2-н графикийн бүх тохиргоог LOW (хамгийн бага) болож өөрчлөөд тоглоомыг хаана.
2. ``Documents/StarCraft II/variables.txt`` файлыг доорхи тохиргоогоор дарж хуулна.

```
accountCountry=MNG
antialias=0
bakeTerrainLighting=0
creeptrans=1
globalhdr=1
glossmaps=1
GraphicsOptionEffectsDetail=1
GraphicsOptionModelQuality=1
GraphicsOptionOverallQualityVer7[15]=5
GraphicsOptionPortraits=1
GraphicsOptionShaderDetail=1
GraphicsOptionShadowQuality=0
lighting=0
lightingLevel=2
lightingregionmapterrain=1
localhdr=1
lowqualitymodels=0
normalmap=1
particlelod=1
pixellight=1
portraits3d=0
preBlendedCreep=0
sampleFOW=1
shadows=1
shadowmapsize=1
simplifiedCloaking=0
simplifiedShaders=0
spec=1
splatlod=1
textureBasedFOW=1
use20shaders=0
useLowqualitymodels=0
vsync=0
```


## Dota 2 (Quickplay)
Dota 2 консол ашиглана
```
dota_ability_quick_cast 1
bind "q" "dota_ability_quickcast 0"
bind "w" "dota_ability_quickcast 1"
bind "e" "dota_ability_quickcast 2"
bind "r" "dota_ability_quickcast 5"
bind "d" "dota_ability_quickcast 3"
bind "f" "dota_ability_quickcast 4"
dota_force_right_click_attack 1
bind A "+chatwheel; chat0" 
alias chat0 "chat_wheel_phrase_0 64;
chat_wheel_phrase_1 69;
chat_wheel_phrase_2 15;
chat_wheel_phrase_3 66;
chat_wheel_phrase_4 76;
chat_wheel_phrase_5 60;
chat_wheel_phrase_6 69;
chat_wheel_phrase_7 70;"
dota_always_show_player_names 0
dota_camera_accelerate 50
dota_camera_disable_zoom 0
dota_camera_speed 3000
dota_disable_range_finder 0
dota_hud_healthbar_number 1
dota_player_units_auto_attack 1
dota_screen_shake 0
fps_max 80
mat_triplebuffered 0
mat_vsync 0
rate 80000
volume 1
```
