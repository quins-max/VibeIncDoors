local BaseUrl = "https://raw.githubusercontent.com/quins-max/VibeIncDoors/refs/heads/main/"
if game.PlaceId ~= 6516141723 then
    loadstring(game:HttpGet(BaseUrl .. "Game/Main.luau"))()
else
    loadstring(game:HttpGet(BaseUrl .. "Game/Lobby.luau"))()
end
