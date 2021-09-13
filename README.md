# WhiteSystemInfo
 
 ### Basic Information 기본 정보
 Rainmeter Skin for Clear Desktop</br>
 깔끔한 바탕화면을 위한 레인미터 스킨</br>
 There are information skin for system, disk, time, network.</br>
 시스템, 디스크, 시간, 네트워크 정보 스킨이 있습니다.</br>
 Each Skin have two choice, 0 and 1.</br>
 각각의 스킨은 0과 1 두 가지 중 선택합니다.</br>
 
 [Example 예시](#example-예시)   
 [Customize Tip 맞춤설정 정보](customize-tip-맞춤설정-정보)   
 
 
 ### Example 예시
 - <b>*Skin0: Time0.ini, System0.ini, Disk0.ini, Network0.ini*</b> </br>
 It have transparent background and solid white text.</br>
 투명한 배경과 흰색 글씨로 되어있습니다.</br>
 🔽🔽<b>Like This 아래처럼요!</b>🔽🔽</br>
 ![image](https://user-images.githubusercontent.com/86394389/132462370-a65b4cab-4a79-4a97-8224-76bbf9c6810d.png) </br></br>
 - <b>*Skin1: Time1.ini, System1.ini, Disk1.ini, Network1.ini*</b></br>
 It have Background Color but, it isn't solid.</br>
 배경 색이 있지만, 불투명하지 않습니다.</br>
 If it's fontColor is same with Desktop background, it looks like transparent text.</br>
 만약 fontColor가 바탕화면 배경색과 같다면, 그건 투명한 텍스트인 것처럼 보일 겁니다.</br>
 🔽🔽<b>Like This 이렇게요!</b>🔽🔽</br>
 ![image](https://user-images.githubusercontent.com/86394389/132463001-f13505ee-f442-4a53-a2b8-63ade12dd52f.png) </br>
 I used Font '[나눔손글씨 할아버지의나눔](https://clova.ai/handwriting/list.html#102)'.

### Customize Tip 맞춤설정 정보
 
 Skins have below customize options. You can change in each skin file.</br>
 다음의 사항을 설정하여 자신에게 맞게 사용하세요. 각 스킨파일에서 바꿀 수 있습니다.</br>
 This skins are almost same with <b>illustro</b> skin.</br>
 이 스킨은 <b>illustro</b> 스킨과 거의 같습니다.</br>
 *OptionName = Default Option (0 or 1 or both: possible skin name to edit)*</br>
 *설정 항목 이름 = 디폴트 설정 (0 또는 1에 해당하는지 또는 둘 다: 가능한 스킨 이름)*</br>
 
 - <b>[Variables]</b></br>
 This is variables for customizing style, part of [Variables] in File.</br>
 파일 내에서 [Variables] 항목의 일부로 스타일을 설정하는 변수들입니다.
	- fontName = 나눔손글씨 할아버지의나눔 (0,1: Disk, Network, System, Time)
	- textSize = 14 (0,1: Disk, Network, System, Time)
	- colorText = 255,255,255,255 (0,1: Disk, Network, System, Time)
	- colorBar = 255,255,255,255 (0,1: Disk, Network, System)
 - <b>[Rainmeter]</b></br>
 It exists for solid color background, so below option can change backgroundColor.</br>
 불투명한 색상의 배경을 위해 존재하며 아래 설정은 배경 색을 바꿀 수 있습니다.
 	- SolidColor = 255,255,255,80 (1: Disk, Network, System, Time)
 - <b>[EachStyle]\(String\)</b></br>
 This can change String Meter Style.</br>
 String 미터의 스타일을 변경할 수 있습니다.
 	- StringAlign=Center (0,1: Disk, Network, System, Time)
 	- StringCase=Upper (0,1: Disk, Network, System, Time)
 	- ;StringStyle=Bold (0,1: Disk, Network, System, Time) //Commented
 	- ;StringEffect=Shadow (0,1: Disk, Network, System, Time) //Commented
 	- ;FontEffectColor=0,0,0,100 (0,1: Disk, Network, System, Time) //Commented
 - <b>[EachStyle]\(Bar\)</b></br>
 This is for skins have Bar Meter. You can see the difference in remained space color of Bar. </br>
 Bar 미터를 위한 것입니다. 바의 남은 부분에 해당하는 색의 변화를 볼 수 있습니다.
 	- SolidColor=255,255,255,15 (0,1: Disk, Network, System, Time)
 <!--
 ### Skins in Example Image 예시 이미지의 다른 스킨들
 
	1) Clear Text | redsaph

Option: Clear Text.ini</br>
Setting: Different from basic setting</br>
	Alignment: center</br>
	Features: ON) Adaptive Hide, Scrolling, Stow controls</br>
	Size: 1080*0.6</br>
	Fonts: 나눔손글씨 할아버지의나눔</br>
		(https://clova.ai/handwriting/list.html#102)</br>
	Code Editing: Font Size

	2) Interactive Dock 1.0 | FinchNelson

Setting file edit:</br>
	Expend: 1.5</br>
	Direction: -1 </br>
A Dcok.ini file edit: low padding, icon size</br>

	3) Waveline | Eldog-02
Setting:</br>
	(Variables file)</br>
	Fill=255,255,255,75</br>
	Outline=255,255,255,255</br>
	Width=6</br>
	Height=50</br>
	RestingHeight=10</br>
	OutlineWidth=1</br>
	BarSpacing=20</br>
	AttackSpeed=50</br>
	DecaySpeed=250</br>
	Sensitivity=75</br>
-->
