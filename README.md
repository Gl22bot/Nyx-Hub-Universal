-- Game Detect
local gameId = game.PlaceId

-- IDs dos jogos
local GAME_1_ID = 2753915549  -- Blox Fruits
local GAME_2_ID = 142823291   -- Murder Mystery 2

-- Função para executar o script correto
local function executeScript(gameId)
    if gameId == GAME_1_ID then
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Gl22bot/NyxBF/refs/heads/main/BfNYXHUB.md"))()
    elseif gameId == GAME_2_ID then
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Gl22bot/Mm2/refs/heads/main/README.md"))()
    end
end

-- Executa a detecção
executeScript(gameId)
