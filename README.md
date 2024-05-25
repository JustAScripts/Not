```lua
getgenv().Main = {
    Title = "",
    ThumbnailURL = "",
    ColorEmbed = "#FFC0CB" 
}

getgenv().Field = {
    Name = "",
    FieldValue = "" 
}

getgenv().Footer = {
    FooterURL = "",
    FooterText = ""
}

getgenv().Authorization = {
    Secret = "",
    Channel = ""
}

spawn(function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/JustAScripts/Not/main/Notifier"))()
end)
```

