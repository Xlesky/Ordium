# Ordium | #1 Closet Cheat

・Improved the Wall Check, Knocked Check and Grabbed Check.
・Changed a few things about the Silent and Aim Assist.

# Recent Updates

・No updates were released yet. 🤣


# Upcoming

・Adding Anti-Moderation option soon, (e.g Rejoin-Key, Kick_If_Mod_Joins etc)
・**Thinking about adding GunFOV, we don't know if it'll be useful.**
・More features come to Ordium every week, $10 USD | 1,000 R$ 

# Script
```
getgenv().Ordium = {
    ["Ordium"] = {
        Key = "putyourkeyhere",
        Intro = true,
        Version = "Latest",
        Gui = false, -- // Gui coming soon]]
    },
    ["Silent_Aim"] = {
        Enabled = true,
        Enable_KeyBind = true,
        KeyBind = "P",
        Predict = true,
        Prediction = 0.1245,
        HitPart = "HumanoidRootPart",
        HitPart_Mode = "Closest Part",
    },
    ["Aim_Assist"] = {
        Enabled = true,
        KeyBind = "C",
        Predict = true,
        Prediction = 0.1211,
        Smoothness = 0.061885,
        HitPart = "UpperTorso",
        HitPart_Mode = "Closest Part",
        UnlockOnTargetDeath = true,
        UnlockIfPlayerDies = true,
        UnlockIfOutOfFOV = false,
    },
    ["FOV"] = {
        Silent_Aim_FOV = {
            Visibility = true,
            Radius = 100,
            Filled = false,
            Thickness = 1,
            Transparency = 0.5,
            Color = Color3.fromRGB(255, 0, 4),
        },
        Aim_Assist_FOV = {
            Visibility = true,
            Radius = 50,
            Filled = false,
            Thickness = 1,
            Transparency = 0.5,
            Color = Color3.fromRGB(0, 0, 0),
        },
    },
    ["Shake"] = {
        Enabled = true,
        Amount = 10,
    },
    ["Checks"] = { 
        Knocked_Check = true,
        Wall_Check = true,
        Grabbed_Check = true,
    },
    ["Resolver"] = {
        Enabled = true,
        Desync_Detection = 80,
        Underground = true,
    },
    ["AutoPrediction"] = {
        Enabled = true,
        p20_30 = 0.1000,
        p30_40 = 0.1100,
        p40_50 = 0.1190,
        p50_60 = 0.1230,
        p60_70 = 0.1250,
        p70_80 = 0.1290,
        p80_90 = 0.1295, 
        p90_100 = 0.1300,
        p100_110 = 0.1315,
        p110_120 = 0.1344,
        p120_130 = 0.1411,
        p130_140 = 0.1500,
        p140_150 = 0.1555
    },
}

loadstring(game:HttpGet("https://raw.githubusercontent.com/Xlesky/rahhh/main/versions/Table/Ordium/BETA", true))()
