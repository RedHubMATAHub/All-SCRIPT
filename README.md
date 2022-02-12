local PlaceId = game.PlaceId

if PlaceId == 3101667897 then
    loadstring(game:HttpGet"https://raw.githubusercontent.com/RedHubMATAHub/Legends-Of-Speed-/main/README.md")()
elseif PlaceId == 3102144307 then
	loadstring(game:HttpGet("https://raw.githubusercontent.com/RedHubMATAHub/AnimeClickerSimulator/main/README.md"))()
elseif PlaceId == 286090429 then
	loadstring(game:HttpGet("https://raw.githubusercontent.com/RedHubMATAHub/Arsenalup/main/README.md"))()
else
	game.Players.LocalPlayer:kick("NOT SCRITP GAME")
	wait(1)
	game:Shutdown()
end
