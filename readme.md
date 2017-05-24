# Update List


### Version Semantics: 

    Major. Minor. isNotShaderCacheContained (1 if not Contained)

<hr>

## 1.0 
> Add Basic Folder Structures

## 1.1

> Add Basic Wall Collider

> Add One Hinge Joint Door 

> Clear All Props from unityPackage Q512

> Sceen -> non-static

## 1.2 

> trying new space


<details>
<summary>Bugs require Fix:</summary>

* collider fix, 
* hinge joint fix, 
* wall fix

</details>

## 1.3

> fix collider 

> Hinge Joint not fixed yet

> Fill up new space

> Still non-static

<details>
<summary>Bugs require Fix:</summary>
	
* Hinge joint fix
* exit sign for upper cube of door(Maybe Ricgh Text UI will fix it)
* upper cube: Anchor override for two reflection probes with weights
* other area space bug

</details>

## 1.4

> fix room-Boiserie and Room-shelf bug(Shelf separate into two parts)

> Add windows.max for needs of boolean expression when adding windows

<details>
<summary>Bugs require Fix:</summary>
	
* Hinge joint fix
* exit sign for upper cube of door(Maybe Ricgh Text UI will fix it)
* upper cube: Anchor override for two reflection probes with weights
* other area space bug

</details>

## 1.5

> Complete partial office structure

> Still non-static

<details>
<summary>Bugs require Fix:</summary>

* Hinge joint fix
* exit sign for upper cube of door(Maybe Ricgh Text UI will fix it)
* upper cube: Anchor override for two reflection probes with weights
* other area space bug

</details>
	

## 1.6

> Fixed upper cube of the door

> Office Strcture minor Adjust

> Still non-static

<details>
<summary>Bugs require Fix:</summary>

* Hinge joint fix

</details>
	
## 1.7

> Add Props: Tray, Mug, KirbyMug, CupCake, Record Player

> Finish Section: Book Shelef of Office

> Still non-static

<details>
<summary>Bugs require Fix:</summary>

* Hinge joint fix

</details>

## 1.8

> Add Props: Spinning Top, Golden Laugh

> Try Add Reflection Probe Under top for top's reflection, however result is not good. Depreciated for now.

> Still non-static

<details>
<summary>Bugs require Fix:</summary>

* Hinge joint fix

</details>

## 1.9

> Add Props: Creeper Doll, Kirby Doll, Flowers, Mac Keyboard&Mouse

> Adjust Desktop structure

> Almost ready to start bake light

<details>
<summary>Bugs require Fix:</summary>

* Hinge joint fix

</details>

## 2.0

> Adjust Ceiling light

> trying add Fur Shader to Dools, but due to resouce-consuming depreciated.

> trying adjust material of spinning top, however it stay for original mat for now.

> Almost ready to start bake light

<details>
<summary>Bugs require Fix:</summary>

* Hinge joint fix // May Not Needed? <- if restrict access to other room?

</details>

## 2.1

> Adjust Wall Frames

> Almost ready to start bake light

<details>
<summary>Bugs require Fix:</summary>

* Hinge joint fix // May Not Needed? <- if restrict access to other room?

* Lack of Office Props on Haku's Desktop

</details>

## 3.0

> Lighting Baked

> Lots of workaround for beautify Scenes

<details>
<summary>Preview</summary>

<img src="img/3.0preview.png">

</details>

<details>
<summary>Bugs require Fix:</summary>

* Lack of Office Props on Haku's Desktop

</details>

## 3.1

> Fix Position of Caffe Table, Console

> Adjust Exposure and Rotation of Skybox

<details>
<summary>Bugs require Fix:</summary>

* Lack of Office Props on Haku's Desktop

</details>

## 4.0 Merged

> Merge Project With M,P Version

<details>
<summary>Bugs require Fix:</summary>

* Lack of Office Props on Haku's Desktop

</details>

## 4.1 

> Note: Compressed With lightmap, ShaderCache, etc.

> Backup of new Lightmap

<details>
<summary>Bugs require Fix:</summary>

* Lack of Office Props on Haku's Desktop

* MKII Glow Shader Bug on d3d9x

</details>

## 4.2

> Import some of haku animation

> Build up simple demo of HeadLookController, BreathController

> HeadLookHelper is depreciated due to it may cause "The Exorcist"

> Adding Enviornment Compensation Light, Haku Compensation Light (Now Both are Directional Light with different Culling Mask)

<details>
<summary>Bugs require Fix:</summary>

* Lack of Office Props on Haku's Desktop

* MKII Glow Shader Bug on d3d9x

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

</details>

## 4.3

> Update Idle State Animation: Blending(Actually additvely blend) Animation of sitting.fbx from mixamo.com, trying syncing with BreathController

> Params:

	*	AvatarMask: Torse & two arms (NO HAND & IK)

	*	BreathController: Duration: 0.78

	*	AnimtaionController: BreathLayer: Additively, weight = 0.15

	*	AnimtaionController: BreathLayer.Delay -> BreathLayer.Breathing: Transition Duration = 0.25, Offset = 0

	*	AnimtaionController: BreathLayer.Breathing: Speed = 1

	*	Animtaion: sitting.fbx: frame 177 - frame 363 + AvatarMask

<details>
<summary>Bugs require Fix:</summary>

* Lack of Office Props on Haku's Desktop

* MKII Glow Shader Bug on d3d9x

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

</details>

## 4.4

> Adding Tracking target for HMD (Now Param: z = -1.93)

> Trying Blend Legs part with previous parts, However Foot Ik reacts wierd

	* 	Use 3ds max reconstruct Animation (So many works)

	*	However OL Haku's Heels won't move

	*	Temporaily change to Uniform Haku Instead

<details>
<summary>Bugs require Fix:</summary>

* Lack of Office Props on Haku's Desktop

* MKII Glow Shader Bug on d3d9x

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* Considering use Uniform Haku Instead of OL Haku

</details>

## 4.5

> Finish Haku Office Animator: Leg Layer

<details>
<summary>Bugs require Fix:</summary>

* Lack of Office Props on Haku's Desktop

* MKII Glow Shader Bug on d3d9x

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* Considering use Uniform Haku Instead of OL Haku

</details>

## 4.6

> Setup Haku Office Animator: UpperBody Layer

> Setup Randomly Leg Motion Script

<details>
<summary>Bugs require Fix:</summary>

* Lack of Office Props on Haku's Desktop

* MKII Glow Shader Bug on d3d9x

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* Considering use Uniform Haku Instead of OL Haku

</details>

## 4.7

> Setup Simple grab object controll

<details>
<summary>Bugs require Fix:</summary>

* Lack of Office Props on Haku's Desktop

* MKII Glow Shader Bug on d3d9x

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* Considering use Uniform Haku Instead of OL Haku

* UpperBody Randome motion script not finished

* Wall Collider needs to be fit exact space more

* Floor Collider needs to be fit exact space more

* Gravity: Due to the scene is two big, acts like moon

	* Shrink the scene

	* Override single scene gravity settings

* The place of rose should be adjusted

* The Scale of Camera Rig Should be adjusted

</details>

## 4.8

> Fix Gravity Bug

	* Gravity is propotion to scale 

	* Wierd AddForce after realeasing grab object is because I rotated [CameraRig]

> Update Simple give gift interaction

<details>
<summary>Bugs require Fix:</summary>

* Lack of Office Props on Haku's Desktop

* MKII Glow Shader Bug on d3d9x

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* Considering use Uniform Haku Instead of OL Haku

* UpperBody Randome motion script not finished

* The scale of room props should be adjusted

</details>

## 4.9

> Update Basic Lunch Scene

<details>
<summary>Bugs require Fix:</summary>

* Lack of Office Props on Haku's Desktop

* MKII Glow Shader Bug on d3d9x

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* Considering use Uniform Haku Instead of OL Haku

* UpperBody Randome motion script not finished

* The scale of room props should be adjusted

</details>

## 5.0

> Update Hurt Effect in Minecraft, Time countdown, etc.

> Update Game Control of Minecraft Scene

> Update Simple Whole Game Control

> Confirmed use Uniform Haku Instead of OL Haku

<details>
<summary>Bugs require Fix:</summary>

* Lack of Office Props on Haku's Desktop

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* UpperBody Randome motion script not finished

* The scale of room props should be adjusted

</details>

## 5.1

> Update Controller details

> I forgot what I've done :(

<details>
<summary>Bugs require Fix:</summary>

* Lack of Office Props on Haku's Desktop

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* UpperBody Randome motion script not finished

* The scale of room props should be adjusted

</details>

## 5.2

> Update Tutorial change image solution(hit.point to uv)

<details>
<summary>Bugs require Fix:</summary>

* Lack of Office Props on Haku's Desktop

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* UpperBody Randome motion script not finished

* The scale of room props should be adjusted

</details>

## 5.3

> ScreenFadeOut when changing scene (now only attached on Minecraft)

<details>
<summary>Bugs require Fix:</summary>

* Lack of Office Props on Haku's Desktop

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* UpperBody Randome motion script not finished

* The scale of room props should be adjusted

</details>

## 5.5

> Merged from ProjectHaku_P_Version5.4

> Construct Full Dropping gift script in Office Scene(All Gifts & after drop & detect drop with headLookController)

> Construct simple upper body animator (However random play script are not finished yet)

> Construct Planes that able to teleport

<details>
<summary>Bugs require Fix:</summary>

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* UpperBody Randome motion script not finished // almost done

* The scale of room props should be adjusted

</details>

## 5.6

> Finished Construct upper body animator

> Add Special Areas For haku to peek

<details>
<summary>Bugs require Fix:</summary>

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* Camera needs to higher?

* The scale of room props should be adjusted

</details>


## 5.8

> Merged from ProjectHaku_Y_Version5.8

> Finished Basic Crab Scene (including Morph Controll & revised anim, however not baked physics)

<details>
<summary>Bugs require Fix:</summary>

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* More less-important details are in todo.md

</details>

## 6.0

> Finished Crape and crab Lunch Scene

> Not quite sure waht updated in this version


<details>
<summary>Bugs require Fix:</summary>

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* More less-important details are in todo.md

</details>

## 6.2 ~ 6.2.8

> experiment with revised animations

<details>
<summary>Bugs require Fix:</summary>

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* More less-important details are in todo.md

</details>

## 6.4

> Revised Animations and fixing wierd bug when fast entering giving gift's collider, causing haku look at you while her hands still typing (Update: Ver 6.5 Not Fixed?)

<details>
<summary>Bugs require Fix:</summary>

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* More less-important details are in todo.md

</details>

## 6.5

> Add Basic Wedding Scene

> Spawn Camera on specific point by substract the placement between CameraRig & Camera(eye), However it works strange on office scene

> add experimental scene: Office Before Lunch

<details>
<summary>Bugs require Fix:</summary>

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* More less-important details are in todo.md

</details>

## 6.6.5

> Adjust BeforeLunchScene without physics effects on animation, a.k.a. broke meshes

> .5 is for haven't clean up experimental animations

<details>
<summary>Bugs require Fix:</summary>

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* More less-important details are in todo.md

</details>

## 6.7

> clean up experimental animations

> Adjust BeforeLunchScene

	裙子用bake，彎腰時破圖

	頭髮用MMD4Mecanim 的 Bullet Physics + MMDRigidbody 的 Cube

<details>
<summary>Bugs require Fix:</summary>

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* More less-important details are in todo.md


</details>

## 6.8

> Add Scene: Opening 

> Minecraft 全部串接 (計時倒數、GameStart/Over Canvas、creeper dying effects)，只缺ipad控制

<details>
<summary>Bugs require Fix:</summary>

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* More less-important details are in todo.md

</details>

## 6.9

> Add Tutorial Control in Scene:Minecraft

> Setting up Scene:Before Lunch

> Finish concat Scene:BeforeLunch and Scene:Lunch

> Trying setup Ending Scene for more details (Now Add: Canvas anim, camera change position)

> Force Rendering support to dx11 in windows, however MKGlow not fixed?

> Ignore dxd9d in some shaders(Axi) of ArchVizPRO

<details>
<summary>Bugs require Fix:</summary>

* Wierd physics are because of specialArea Collider in cameraRig?

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* More less-important details are in todo.md

</details>

## 7.0

> Finished Scene:BadEnding

> Construct Basic scene controll of Scene:GoodEnding, need testing and finish it with HMD on

<details>
<summary>Bugs require Fix:</summary>

* Wierd physics are because of specialArea Collider in cameraRig?

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* More less-important details are in todo.md

</details>

## 7.1

> Merge with Project_M_ver6.5, Adjust Scene:Office prop's scale

<details>
<summary>Bugs require Fix:</summary>

* Wierd physics are because of specialArea Collider in cameraRig?

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* More less-important details are in todo.md

</details>

## 7.2

> Finished Scene:GoodEnding (Not checked in VR)

<details>
<summary>Bugs require Fix:</summary>

* Wierd physics are because of specialArea Collider in cameraRig?

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* More less-important details are in todo.md

</details>


## 7.3

> Finished Scene:GoodEnding & Scene:BadEnding & Scene:Opening, Not including art details

> Add Scripting Control to bgm fadeIn/Out

<details>
<summary>Bugs require Fix:</summary>

* Wierd physics are because of specialArea Collider in cameraRig?

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* More less-important details are in todo.md

</details>

## 7.4

> Finished Bgm Controlling

<details>
<summary>Bugs require Fix:</summary>

* Wierd physics are because of specialArea Collider in cameraRig?

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* More less-important details are in todo.md

</details>

## 7.5

> FadeOut Bgm:EndingGoodWait

> 調整Minecraft Count Canvas

> 修正Office物理bug(果然是因為SpecialAreacapusle，調整physical detection layer 修正)

> 全部的bgm、音量再調整、Office Recorder

> 加入Lunch Ipad

> 修正SpawnAtPoint Bug: 因為CameraEye 和 CameraRig本身的Scale的引響(將CameraRig Scele 調成1解決，不過因此 Scene:Office 東西位置需要再微調)

> 修正 修正SpawnAtPoint Bug 之後地板會閃爍：拿掉 PlaneRefection就可以了(可能是之前改DXD9的關係)

> 修正 Minecraft CleanUp 沒有兩隻手把都啟用的bug

<details>
<summary>Bugs require Fix:</summary>

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* More less-important details are in todo.md

</details>

## 7.6

> Adjust Skirt

<details>
<summary>Bugs require Fix:</summary>

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* More less-important details are in todo.md

</details>

## 7.7

> LunchScene, EndingScene * 2 材質、光照完成！

	註記：無法看見蠟燭是因為跟背後玻璃的transparent相衝?

> Fix goodEnding CleanUp Bug

> Fix goodEnding SpawnAtPoint Bug

<details>
<summary>Bugs require Fix:</summary>

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* More less-important details are in todo.md

</details>

## 7.8

> Update Hint in Scene:Office

> Update Dialog Sprite in Scene:BeforeLunch & adjust time for changing scene

> Update Eaten effects on crape & crab(Add Donut)


<details>
<summary>Bugs require Fix:</summary>

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* Should add: Haku eating morph and SFXs

* Scene:Lunch LaserPointer Bug

* More less-important details are in todo.md

</details>

## 7.9

> Adjust Haku's scale in whole game

<details>
<summary>Bugs require Fix:</summary>

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* Should add: Haku eating morph and SFXs

* Scene:Lunch LaserPointer Bug

* More less-important details are in todo.md

</details>

## 8.0

> 修正 Vive Tutorial ReleaseObj 時給予velocity, augularVelocity 的問題(應該要用local座標系的速度、角速度)

	所以在此之後Camera可以Rotate了

> 建立API: 固定出生點視角 (根據 Start 時頭盔位置計算CameraRig轉動量，並根據旋轉之後位置重新指定位置)

> 尚未套用到Office以外的場景(最需要的應該是BeforeLunch)

<details>
<summary>Bugs require Fix:</summary>

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* Should add: Haku eating morph and SFXs

* Scene:Lunch LaserPointer Bug

* More less-important details are in todo.md

</details>

## 8.1 ~ 8.4

> 因為未詳細紀錄更新紀錄，所以直接整合在一起

> 紀錄上次更新API細節: 固定出生點視角 修正
	
	兩種做法：

	一為根據Camera轉動場景，在生成位置 但是這樣就無法static (舊的作法) // 不好

	二為根據位置計算CameraRig的轉動位移跟位置位移

> 修正新API之後 Ending 場景切換 Camera 位置

	因為轉動之後位移量不再是直接用加的，不過GoodEnding並未做視角控制，沿用舊版

> 初步 Bake 中，效果還好，但是

	光線在天花板處有明顯分界 // 應該是因為point light + 半圓燈罩? 正常嗎?

	沒有陰影的感覺 也沒有樹葉陰影的感覺

> 建立完整第0場景，修正移動到MenuBg的Bug

	因為下面的Plane 在手把的 TeleportMask中

	強迫完成教學的設計模式 (但是無法處理喜歡亂搞的玩家)

> 加入 GoodEnding 觀眾

> 加入Office Judge 禮物時轉頭

> 修正 Office 給東西動畫的bug (因為 Update UpperBodyMotion使用 IEnumerator，所以控制城拿東西後馬上被 Assign 回 Keyboard了)

> 修正複數Bug

	* 修正 Lunch LaserPointer Bug

	* 調整 Minecraft Canvas位置

	* Office 撿不到東西 // 沒問題啊?

	* Lunch 要離Haku進一點

	* Minecraft場景拿不到Ipad // 修改擺放位置

	* 調整 BeforeLunch Bgm 音量到 0.3 // 原本的兩倍

	* 修正BadEnding Haku表情 
	
	* Office表情慢一點點 // 因為加入轉頭

	* Haku頭髮Shader透明? // 因為貼圖本身那邊有alpha = 255的狀況，change MainTex to HairNT

	*  Office Keyboard 音效 // 不過沒有fadeIn, Out, 沒有很fit手指動作

> 註記：

	加頭髮 > 小穿越

	裙子物理沒有考慮到左右腳切換

	Idle -> take東西會小小穿越裙子 // 先不處理!

<details>
<summary>Bugs require Fix:</summary>

* MKII Glow Shader Bug on d3d9x // One Workaround is to exclude direct9 on build setting

* Shadow of Realtime Direction Light Behavior really wierd (Just Like Silent Hills, WTF)

* More less-important details are in todo.md

</details>
