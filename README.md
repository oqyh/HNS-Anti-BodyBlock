# [CSGO-CSS] HNS Anti BodyBlock (1.0.0)
https://hlmod.net/threads/csgo-css-hns-anti-bodyblock.66104/

### Fall Damage Print + Health Regeneration Fall Damage + God Mode Timer

https://www.youtube.com/watch?v=ck5GlHgqC-E

## .:[ ConVars ]:.
 ```
//=========================[ Enable/Disable Plugin ]======================================================

// Enable [CSGO-CSS] HNS Anti BodyBlock Plugin?
// 1= Yes
// 0= No
hns_b_enable_plugin "1"

//===============================[ Settings ]=============================================================

// Make 0 Fall Damage For
// 3= CT on T's Head Only
// 2= T on CT's Head Only
// 1= Both [CT on T's Head] and [T on CT's Head]
// 0= No one
hns_b_disable_fall "0"

//===============================[ Misc ]=================================================================

// Enable Cooldown Timer Client Between Jumps On Enemy's Head?
// 1= Yes
// 0= No (Means Client Can Jump On Next Head After Land On Ground)
hns_b_enable_cooldown "0"

// if [hns_b_enable_cooldown 1] (in Secs) Cooldown Client Between Jumps On Enemy's Head
hns_b_cooldown "5.0"



// Enable Jumped Boost?
// 1= Yes
// 0= No
hns_b_enable_jb "0"

// if [hns_b_enable_jb 1] For How Much Jump Boost Height
// 400 or higher= high jump
// 200 or lower= low jump
hns_b_jb_height "400.0"



// Make Damage Who Got Step On His Head
// 3= CT on T's Head Only
// 2= T on CT's Head Only
// 1= Both [CT on T's Head] and [T on CT's Head]
// 0= No (Disable)
hns_b_enable_damage "0"

// if [hns_b_enable_damage 1 or 2 or 3] Damage Who Got Step On His Head @Air
hns_b_damage_a "20"

// if [hns_b_enable_damage 1 or 2 or 3] Damage Who Got Step On His Head @Ground
hns_b_damage_g "4"

// if [hns_b_enable_damage 1 or 2 or 3] Damage Who Got Step On His Head @Ladder
hns_b_damage_l "8"

// if [hns_b_enable_damage 1 or 2 or 3] Damage Who Got Step On His Head @Surf
hns_b_damage_s "10"

// if [hns_b_enable_damage 1 or 2 or 3] Damage Who Got Step On His Head @Water
hns_b_damage_w "4"

//===============================[ Sounds ]===============================================================


// Enable Sound CT on T's Head?
// 1= Yes
// 0= No
hns_b_sound_ct "1"

// if [hns_b_sound_ct 1] Where Sound Located ((((Without Sound/)))
hns_b_ct_path "discord-oqyh/mario.mp3"


// Enable Sound T on CT's Head?
// 1= Yes
// 0= No
hns_b_sound_t "1"

// if [hns_b_sound_t 1] Where Sound Located ((((Without Sound/)))
hns_b_t_path "discord-oqyh/haha.mp3"


//=======================[ Messages / Chat ]==============================================================

// Send Announced Message To All Who Got Jump On Enemy's Head
// 2= Yes Without Hp Left
// 1= Yes With Hp Left
// 0= No
hns_b_announcer "1"

// if [hns_b_announcer 1 or 2] Do You Like To Add Locations (@surf,@water,etc...)
// 1= Yes
// 0= No
hns_b_announcer_loc "0"

//========================================================================================================
```


## .:[ Change Log ]:.
```
(1.0.0)
-Initial Release
```

## .:[ Donation ]:.

If this project help you reduce time to develop, you can give me a cup of coffee :)

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://paypal.me/oQYh)
