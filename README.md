-- Gui to Lua
-- Version: 3.2

-- Instances:

local uibloxjurassico = Instance.new("ScreenGui")
local gatunohub = Instance.new("Frame")
local TabFrame = Instance.new("Frame")
local SideLine = Instance.new("Frame")
local TabList = Instance.new("ScrollingFrame")
local SideLine_2 = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local TopbarFrame = Instance.new("Frame")
local ImageLabel = Instance.new("ImageLabel")
local UICorner_2 = Instance.new("UICorner")
local BottomFrame = Instance.new("Frame")
local Line = Instance.new("Frame")
local Title = Instance.new("TextButton")
local UICorner_3 = Instance.new("UICorner")
local FixCorner = Instance.new("Frame")
local TextButton = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")
local TextButton_2 = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local Frame = Instance.new("Frame")
local UICorner_6 = Instance.new("UICorner")
local TextButton_3 = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")
local TextButton_4 = Instance.new("TextButton")
local UICorner_8 = Instance.new("UICorner")
local ImageButton = Instance.new("ImageButton")
local UICorner_9 = Instance.new("UICorner")

--Properties:

uibloxjurassico.Name = "ui-bloxjurassico"
uibloxjurassico.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
uibloxjurassico.DisplayOrder = 100
uibloxjurassico.ResetOnSpawn = false

gatunohub.Name = "gatunohub"
gatunohub.Parent = uibloxjurassico
gatunohub.AnchorPoint = Vector2.new(0.5, 0.5)
gatunohub.BackgroundColor3 = Color3.fromRGB(17, 17, 17)
gatunohub.BorderColor3 = Color3.fromRGB(0, 0, 0)
gatunohub.BorderSizePixel = 0
gatunohub.Position = UDim2.new(0.443479747, 0, 0.440890133, 0)
gatunohub.Size = UDim2.new(0, 609, 0, 406)

TabFrame.Name = "TabFrame"
TabFrame.Parent = gatunohub
TabFrame.BackgroundColor3 = Color3.fromRGB(15, 15, 15)
TabFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
TabFrame.BorderSizePixel = 0
TabFrame.Position = UDim2.new(-0.00199993886, 0, 0.0126316436, 0)
TabFrame.Size = UDim2.new(0.300000012, 0, 0.949999988, 0)

SideLine.Name = "SideLine"
SideLine.Parent = TabFrame
SideLine.AnchorPoint = Vector2.new(1, 0)
SideLine.BackgroundColor3 = Color3.fromRGB(49, 49, 49)
SideLine.BorderColor3 = Color3.fromRGB(0, 0, 0)
SideLine.BorderSizePixel = 0
SideLine.LayoutOrder = 1
SideLine.Position = UDim2.new(0.999999881, 0, 0, 0)
SideLine.Size = UDim2.new(0, 1, 1, 0)
SideLine.ZIndex = 10

TabList.Name = "TabList"
TabList.Parent = TabFrame
TabList.Active = true
TabList.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TabList.BackgroundTransparency = 1.000
TabList.BorderColor3 = Color3.fromRGB(0, 0, 0)
TabList.BorderSizePixel = 0
TabList.Position = UDim2.new(0, 0, 0.0999999717, 0)
TabList.Size = UDim2.new(0.993807137, 0, 0.900000036, 0)
TabList.CanvasSize = UDim2.new(0, 0, 0, 0)
TabList.ScrollBarThickness = 0

SideLine_2.Name = "SideLine"
SideLine_2.Parent = TabFrame
SideLine_2.AnchorPoint = Vector2.new(1, 0)
SideLine_2.BackgroundColor3 = Color3.fromRGB(49, 49, 49)
SideLine_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
SideLine_2.BorderSizePixel = 0
SideLine_2.Position = UDim2.new(1, 0, 0.100000001, 0)
SideLine_2.Size = UDim2.new(1, 0, 0, 1)

UICorner.Parent = TabFrame

TopbarFrame.Name = "TopbarFrame"
TopbarFrame.Parent = TabFrame
TopbarFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TopbarFrame.BackgroundTransparency = 1.000
TopbarFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
TopbarFrame.BorderSizePixel = 0
TopbarFrame.Size = UDim2.new(1, 0, 0.100000001, 0)

ImageLabel.Parent = TopbarFrame
ImageLabel.AnchorPoint = Vector2.new(0.5, 0.5)
ImageLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel.BackgroundTransparency = 1.000
ImageLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageLabel.BorderSizePixel = 0
ImageLabel.Position = UDim2.new(0.453475654, 0, 0.342773557, 0)
ImageLabel.Size = UDim2.new(0.29392454, 0, 1.47001445, 0)
ImageLabel.Image = "rbxassetid://106702991471250"
ImageLabel.ScaleType = Enum.ScaleType.Fit

UICorner_2.Parent = gatunohub

BottomFrame.Name = "BottomFrame"
BottomFrame.Parent = gatunohub
BottomFrame.AnchorPoint = Vector2.new(0, 1)
BottomFrame.BackgroundColor3 = Color3.fromRGB(23, 23, 23)
BottomFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
BottomFrame.BorderSizePixel = 0
BottomFrame.Position = UDim2.new(0, 0, 1, 0)
BottomFrame.Size = UDim2.new(1, 0, 0.0500000007, 0)

Line.Name = "Line"
Line.Parent = BottomFrame
Line.BackgroundColor3 = Color3.fromRGB(49, 49, 49)
Line.BorderColor3 = Color3.fromRGB(0, 0, 0)
Line.BorderSizePixel = 0
Line.Size = UDim2.new(1, 0, 0, 1)
Line.ZIndex = 10

Title.Name = "Title"
Title.Parent = BottomFrame
Title.Active = false
Title.AnchorPoint = Vector2.new(0.5, 0.5)
Title.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Title.BackgroundTransparency = 1.000
Title.BorderColor3 = Color3.fromRGB(0, 0, 0)
Title.BorderSizePixel = 0
Title.Position = UDim2.new(0.511249959, 0, 0.499999136, 0)
Title.Selectable = false
Title.Size = UDim2.new(0.977500021, 0, 0.600000024, 0)
Title.Font = Enum.Font.Unknown
Title.Text = "gatuno-hub: https://discord.gg/Tb9BUFkF"
Title.TextColor3 = Color3.fromRGB(116, 116, 116)
Title.TextScaled = true
Title.TextSize = 14.000
Title.TextWrapped = true

UICorner_3.Parent = BottomFrame

FixCorner.Name = "FixCorner"
FixCorner.Parent = BottomFrame
FixCorner.BackgroundColor3 = Color3.fromRGB(23, 23, 23)
FixCorner.BorderColor3 = Color3.fromRGB(0, 0, 0)
FixCorner.BorderSizePixel = 0
FixCorner.Size = UDim2.new(1, 0, 0.200000003, 0)

TextButton.Parent = gatunohub
TextButton.BackgroundColor3 = Color3.fromRGB(217, 0, 4)
TextButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton.BorderSizePixel = 0
TextButton.Position = UDim2.new(0.0344827585, 0, 0.167487681, 0)
TextButton.Size = UDim2.new(0, 138, 0, 51)
TextButton.Font = Enum.Font.Creepster
TextButton.Text = "esp-jogador"
TextButton.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton.TextScaled = true
TextButton.TextSize = 14.000
TextButton.TextWrapped = true

UICorner_4.Parent = TextButton

TextButton_2.Parent = gatunohub
TextButton_2.BackgroundColor3 = Color3.fromRGB(217, 0, 4)
TextButton_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_2.BorderSizePixel = 0
TextButton_2.Position = UDim2.new(0.0344827585, 0, 0.307881773, 0)
TextButton_2.Size = UDim2.new(0, 138, 0, 69)
TextButton_2.Font = Enum.Font.Creepster
TextButton_2.Text = "no-clip"
TextButton_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_2.TextScaled = true
TextButton_2.TextSize = 14.000
TextButton_2.TextWrapped = true

UICorner_5.Parent = TextButton_2

Frame.Parent = gatunohub
Frame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.318177879, 0, 0.0434528962, 0)
Frame.Size = UDim2.new(0, 407, 0, 359)

UICorner_6.Parent = Frame

TextButton_3.Parent = gatunohub
TextButton_3.BackgroundColor3 = Color3.fromRGB(217, 0, 4)
TextButton_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_3.BorderSizePixel = 0
TextButton_3.Position = UDim2.new(0.0344827585, 0, 0.5, 0)
TextButton_3.Size = UDim2.new(0, 138, 0, 62)
TextButton_3.Font = Enum.Font.Creepster
TextButton_3.Text = "auto-farme"
TextButton_3.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_3.TextScaled = true
TextButton_3.TextSize = 14.000
TextButton_3.TextWrapped = true

UICorner_7.Parent = TextButton_3

TextButton_4.Parent = gatunohub
TextButton_4.BackgroundColor3 = Color3.fromRGB(217, 0, 4)
TextButton_4.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_4.BorderSizePixel = 0
TextButton_4.Position = UDim2.new(0.0344827585, 0, 0.689655185, 0)
TextButton_4.Size = UDim2.new(0, 138, 0, 62)
TextButton_4.Font = Enum.Font.Creepster
TextButton_4.Text = "fly"
TextButton_4.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_4.TextScaled = true
TextButton_4.TextSize = 14.000
TextButton_4.TextWrapped = true

UICorner_8.Parent = TextButton_4

ImageButton.Parent = uibloxjurassico
ImageButton.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
ImageButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageButton.BorderSizePixel = 0
ImageButton.Position = UDim2.new(0.023221869, 0, 0.305980533, 0)
ImageButton.Size = UDim2.new(0, 84, 0, 78)
ImageButton.Image = "rbxassetid://106702991471250"

UICorner_9.Parent = ImageButton

-- Scripts:

local function AOVRCO_fake_script() -- TextButton.LocalScript 
	local script = Instance.new('LocalScript', TextButton)

	-- Script para botão que alterna cor ao clicar
	-- Coloque este script como LocalScript dentro do botão (TextButton ou ImageButton)
	
	local button = script.Parent -- O botão onde o script está
	local originalColor = button.BackgroundColor3 -- Salva a cor original
	local isGreen = false -- Controla se está verde ou não
	
	-- Função que executa quando o botão é clicado
	local function toggleColor()
		if isGreen then
			-- Se está verde, volta para a cor original
			button.BackgroundColor3 = originalColor
			isGreen = false
			print("Botão voltou para cor original")
		else
			-- Se não está verde, fica verde
			button.BackgroundColor3 = Color3.new(0, 1, 0) -- Verde puro
			isGreen = true
			print("Botão ficou verde")
		end
	end
	
	-- Conecta a função ao evento de clique
	button.MouseButton1Click:Connect(toggleColor)
end
coroutine.wrap(AOVRCO_fake_script)()
local function QCRXVRB_fake_script() -- TextButton.esp 
	local script = Instance.new('LocalScript', TextButton)

	local Players = game:GetService("Players")
	local LocalPlayer = Players.LocalPlayer
	local RunService = game:GetService("RunService")
	
	local button = script.Parent  -- se o script estiver DENTRO do botão
	-- Se estiver fora, use: local button = script.Parent:WaitForChild("ToggleButton")
	
	local espEnabled = false
	local espConnections = {}
	local billboardGuis = {}
	
	-- Função para criar o ESP de um jogador
	local function createESP(player)
		if player == LocalPlayer then return end
		if not player.Character or not player.Character:FindFirstChild("HumanoidRootPart") then return end
	
		local root = player.Character:WaitForChild("HumanoidRootPart")
	
		local billboard = Instance.new("BillboardGui")
		billboard.Name = "ESP"
		billboard.AlwaysOnTop = true
		billboard.Size = UDim2.new(0, 200, 0, 50)
		billboard.StudsOffset = Vector3.new(0, 3, 0)
		billboard.Adornee = root
		billboard.Parent = root
	
		local textLabel = Instance.new("TextLabel")
		textLabel.Size = UDim2.new(1, 0, 1, 0)
		textLabel.BackgroundTransparency = 1
		textLabel.TextColor3 = Color3.new(1, 0, 0) -- vermelho
		textLabel.TextStrokeTransparency = 0.5
		textLabel.TextScaled = true
		textLabel.Font = Enum.Font.SourceSansBold
		textLabel.Text = ""
		textLabel.Parent = billboard
	
		billboardGuis[player] = {
			gui = billboard,
			label = textLabel
		}
	end
	
	-- Função para remover o ESP de um jogador
	local function removeESP(player)
		if billboardGuis[player] then
			billboardGuis[player].gui:Destroy()
			billboardGuis[player] = nil
		end
	end
	
	-- Atualiza as distâncias e nomes
	local function updateESP()
		for player, data in pairs(billboardGuis) do
			if player and player.Character and player.Character:FindFirstChild("HumanoidRootPart") then
				local distance = (player.Character.HumanoidRootPart.Position - LocalPlayer.Character.HumanoidRootPart.Position).Magnitude
				data.label.Text = string.format("%s\n[%.1f studs]", player.Name, distance)
			end
		end
	end
	
	-- Ativa o ESP
	local function enableESP()
		for _, player in ipairs(Players:GetPlayers()) do
			if player ~= LocalPlayer then
				createESP(player)
			end
		end
	
		espConnections["characterAdded"] = Players.PlayerAdded:Connect(function(player)
			player.CharacterAdded:Connect(function()
				task.wait(1)
				if espEnabled then
					createESP(player)
				end
			end)
		end)
	
		espConnections["playerRemoving"] = Players.PlayerRemoving:Connect(function(player)
			removeESP(player)
		end)
	
		espConnections["updateLoop"] = RunService.RenderStepped:Connect(updateESP)
	end
	
	-- Desativa o ESP
	local function disableESP()
		for player, data in pairs(billboardGuis) do
			removeESP(player)
		end
	
		for _, conn in pairs(espConnections) do
			if conn and conn.Disconnect then
				conn:Disconnect()
			end
		end
	
		espConnections = {}
	end
	
	-- Clique do botão para ativar/desativar
	button.MouseButton1Click:Connect(function()
		espEnabled = not espEnabled
		button.Text = espEnabled and "Desativar ESP" or "Ativar ESP"
	
		if espEnabled then
			enableESP()
		else
			disableESP()
		end
	end)
	
end
coroutine.wrap(QCRXVRB_fake_script)()
local function NJBNMA_fake_script() -- TextButton_2.LocalScript 
	local script = Instance.new('LocalScript', TextButton_2)

	-- Script para botão que alterna cor ao clicar
	-- Coloque este script como LocalScript dentro do botão (TextButton ou ImageButton)
	
	local button = script.Parent -- O botão onde o script está
	local originalColor = button.BackgroundColor3 -- Salva a cor original
	local isGreen = false -- Controla se está verde ou não
	
	-- Função que executa quando o botão é clicado
	local function toggleColor()
		if isGreen then
			-- Se está verde, volta para a cor original
			button.BackgroundColor3 = originalColor
			isGreen = false
			print("Botão voltou para cor original")
		else
			-- Se não está verde, fica verde
			button.BackgroundColor3 = Color3.new(0, 1, 0) -- Verde puro
			isGreen = true
			print("Botão ficou verde")
		end
	end
	
	-- Conecta a função ao evento de clique
	button.MouseButton1Click:Connect(toggleColor)
end
coroutine.wrap(NJBNMA_fake_script)()
local function QWQB_fake_script() -- TextButton_2.noclip 
	local script = Instance.new('LocalScript', TextButton_2)

	-- Serviços
	local Players = game:GetService("Players")
	local RunService = game:GetService("RunService")
	
	-- Variáveis
	local player = Players.LocalPlayer
	local character = player.Character or player.CharacterAdded:Wait()
	local noclipAtivo = false
	
	-- Função para ativar/desativar noclip
	local function toggleNoclip()
		noclipAtivo = not noclipAtivo
	
		if noclipAtivo then
			RunService:BindToRenderStep("Noclip", Enum.RenderPriority.Character.Value, function()
				local char = player.Character
				if char then
					for _, part in pairs(char:GetDescendants()) do
						if part:IsA("BasePart") and part.CanCollide == true then
							part.CanCollide = false
						end
					end
				end
			end)
		else
			RunService:UnbindFromRenderStep("Noclip")
			local char = player.Character
			if char then
				for _, part in pairs(char:GetDescendants()) do
					if part:IsA("BasePart") then
						part.CanCollide = true
					end
				end
			end
		end
	end
	
	-- Conectando ao botão (o script deve estar DENTRO do botão)
	script.Parent.MouseButton1Click:Connect(toggleNoclip)
	
end
coroutine.wrap(QWQB_fake_script)()
local function UKATMN_fake_script() -- Frame.LocalScript 
	local script = Instance.new('LocalScript', Frame)

	-- Script de Monitoramento para seu Frame existente
	-- Coloque este script como LocalScript dentro do seu Frame
	
	local Players = game:GetService("Players")
	local RunService = game:GetService("RunService")
	local Stats = game:GetService("Stats")
	
	local frame = script.Parent -- Seu frame existente
	local player = Players.LocalPlayer
	
	-- Label do Ping (centralizado)
	local pingLabel = Instance.new("TextLabel")
	pingLabel.Name = "PingLabel"
	pingLabel.Parent = frame
	pingLabel.Size = UDim2.new(1, -10, 0, 30)
	pingLabel.Position = UDim2.new(0, 5, 0, 10)
	pingLabel.BackgroundTransparency = 1
	pingLabel.Text = "🌐 Ping: Carregando..."
	pingLabel.TextColor3 = Color3.new(0, 1, 0)
	pingLabel.TextScaled = true
	pingLabel.TextXAlignment = Enum.TextXAlignment.Center
	pingLabel.Font = Enum.Font.SourceSansBold
	
	-- Label do FPS (centralizado)
	local fpsLabel = Instance.new("TextLabel")
	fpsLabel.Name = "FpsLabel"
	fpsLabel.Parent = frame
	fpsLabel.Size = UDim2.new(1, -10, 0, 30)
	fpsLabel.Position = UDim2.new(0, 5, 0, 50)
	fpsLabel.BackgroundTransparency = 1
	fpsLabel.Text = "⚡ FPS: Carregando..."
	fpsLabel.TextColor3 = Color3.new(0, 1, 0)
	fpsLabel.TextScaled = true
	fpsLabel.TextXAlignment = Enum.TextXAlignment.Center
	fpsLabel.Font = Enum.Font.SourceSansBold
	
	-- Label da Quantidade de Players (centralizado)
	local playersCountLabel = Instance.new("TextLabel")
	playersCountLabel.Name = "PlayersCountLabel"
	playersCountLabel.Parent = frame
	playersCountLabel.Size = UDim2.new(1, -10, 0, 30)
	playersCountLabel.Position = UDim2.new(0, 5, 0, 90)
	playersCountLabel.BackgroundTransparency = 1
	playersCountLabel.Text = "👥 Players: Carregando..."
	playersCountLabel.TextColor3 = Color3.new(0, 1, 0)
	playersCountLabel.TextScaled = true
	playersCountLabel.TextXAlignment = Enum.TextXAlignment.Center
	playersCountLabel.Font = Enum.Font.SourceSansBold
	
	-- Título da Lista de Players (centralizado)
	local playersTitle = Instance.new("TextLabel")
	playersTitle.Name = "PlayersTitle"
	playersTitle.Parent = frame
	playersTitle.Size = UDim2.new(1, -10, 0, 25)
	playersTitle.Position = UDim2.new(0, 5, 0, 130)
	playersTitle.BackgroundTransparency = 1
	playersTitle.Text = "📋 Lista de Jogadores"
	playersTitle.TextColor3 = Color3.new(0, 1, 0)
	playersTitle.TextScaled = true
	playersTitle.TextXAlignment = Enum.TextXAlignment.Center
	playersTitle.Font = Enum.Font.SourceSansBold
	
	-- ScrollingFrame para Lista de Players (se adapta ao frame)
	local playersFrame = Instance.new("ScrollingFrame")
	playersFrame.Name = "PlayersFrame"
	playersFrame.Parent = frame
	playersFrame.Size = UDim2.new(1, -20, 1, -170) -- Se adapta ao tamanho restante do frame
	playersFrame.Position = UDim2.new(0, 10, 0, 160)
	playersFrame.BackgroundTransparency = 1
	playersFrame.BorderSizePixel = 0
	playersFrame.ScrollBarThickness = 8
	playersFrame.ScrollBarImageColor3 = Color3.new(1, 1, 1)
	
	-- Variáveis para FPS
	local frameCount = 0
	local lastTime = tick()
	local currentFPS = 0
	
	-- Função para determinar qualidade do ping
	local function getPingQuality(ping)
		if ping < 150 then
			return "🟢 Boa", Color3.new(0, 1, 0)
		elseif ping < 190 then
			return "🟡 Jogavel", Color3.new(1, 1, 0)
		elseif ping < 250 then
			return "🟠 Ruim", Color3.new(1, 0.5, 0)
		elseif ping < 300 then
			return "🔴 horrivel", Color3.new(1, 0, 0)
		else
			return "⚫ Extrema", Color3.new(0.5, 0, 0.5)
		end
	end
	
	-- Função para atualizar lista de players
	local function updatePlayersList()
		-- Limpa lista atual
		for _, child in pairs(playersFrame:GetChildren()) do
			if child:IsA("TextLabel") then
				child:Destroy()
			end
		end
	
		-- Adiciona players atuais
		local playersList = Players:GetPlayers()
		for i, plr in pairs(playersList) do
			local playerLabel = Instance.new("TextLabel")
			playerLabel.Name = "Player_" .. i
			playerLabel.Parent = playersFrame
			playerLabel.Size = UDim2.new(1, -10, 0, 25)
			playerLabel.Position = UDim2.new(0, 5, 0, (i-1) * 30)
			playerLabel.BackgroundTransparency = 1
			playerLabel.Text = "• " .. plr.Name .. (plr == player and " (Você)" or "")
			playerLabel.TextColor3 = Color3.new(0, 1, 0) -- Verde para todos
			playerLabel.TextScaled = true
			playerLabel.TextXAlignment = Enum.TextXAlignment.Center -- Centralizado
			playerLabel.Font = Enum.Font.SourceSans
		end
	
		-- Atualiza tamanho do canvas
		playersFrame.CanvasSize = UDim2.new(0, 0, 0, #playersList * 30)
	end
	
	-- Função principal de atualização
	local function updateStats()
		-- Atualizar FPS
		frameCount = frameCount + 1
		local currentTime = tick()
		if currentTime - lastTime >= 1 then
			currentFPS = math.floor(frameCount / (currentTime - lastTime))
			frameCount = 0
			lastTime = currentTime
		end
	
		-- Atualizar Ping
		local ping = math.floor(player:GetNetworkPing() * 1000)
		local pingQuality, pingColor = getPingQuality(ping)
	
		-- Atualizar Labels (centralizados)
		pingLabel.Text = "🌐 Ping: " .. ping .. "ms (" .. pingQuality .. ")"
		pingLabel.TextColor3 = Color3.new(0, 1, 0) -- Verde sempre
	
		fpsLabel.Text = "⚡ FPS: " .. currentFPS
		fpsLabel.TextColor3 = Color3.new(0, 1, 0) -- Verde sempre
	
		playersCountLabel.Text = "👥 Players: " .. #Players:GetPlayers() .. "/" .. Players.MaxPlayers
	end
	
	-- Eventos
	Players.PlayerAdded:Connect(function(plr)
		updatePlayersList()
		print("🔵 " .. plr.Name .. " entrou no jogo!")
	end)
	
	Players.PlayerRemoving:Connect(function(plr)
		print("🔴 " .. plr.Name .. " saiu do jogo!")
		wait(0.1) -- Pequeno delay para garantir que o player foi removido
		updatePlayersList()
	end)
	
	-- Conexões de atualização
	RunService.Heartbeat:Connect(updateStats)
	
	-- Atualizar lista inicial
	wait(1) -- Espera um pouco para carregar tudo
	updatePlayersList()
	
	print("✅ Monitor do servidor iniciado no seu frame!")
end
coroutine.wrap(UKATMN_fake_script)()
local function VPTHP_fake_script() -- gatunohub.LocalScript 
	local script = Instance.new('LocalScript', gatunohub)

	local UIS = game:GetService("UserInputService")
	local RunService = game:GetService("RunService")
	
	local frame = script.Parent
	local dragging
	local dragInput
	local dragStart
	local startPos
	
	local function update(input)
		local delta = input.Position - dragStart
		frame.Position = UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X, startPos.Y.Scale, startPos.Y.Offset + delta.Y)
	end
	
	frame.InputBegan:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
			dragging = true
			dragStart = input.Position
			startPos = frame.Position
	
			input.Changed:Connect(function()
				if input.UserInputState == Enum.UserInputState.End then
					dragging = false
				end
			end)
		end
	end)
	
	frame.InputChanged:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
			dragInput = input
		end
	end)
	
	RunService.RenderStepped:Connect(function()
		if dragging and dragInput then
			update(dragInput)
		end
	end)
	
end
coroutine.wrap(VPTHP_fake_script)()
local function XZAB_fake_script() -- TextButton_3.LocalScript 
	local script = Instance.new('LocalScript', TextButton_3)

	-- Script para botão que alterna cor ao clicar
	-- Coloque este script como LocalScript dentro do botão (TextButton ou ImageButton)
	
	local button = script.Parent -- O botão onde o script está
	local originalColor = button.BackgroundColor3 -- Salva a cor original
	local isGreen = false -- Controla se está verde ou não
	
	-- Função que executa quando o botão é clicado
	local function toggleColor()
		if isGreen then
			-- Se está verde, volta para a cor original
			button.BackgroundColor3 = originalColor
			isGreen = false
			print("Botão voltou para cor original")
		else
			-- Se não está verde, fica verde
			button.BackgroundColor3 = Color3.new(0, 1, 0) -- Verde puro
			isGreen = true
			print("Botão ficou verde")
		end
	end
	
	-- Conecta a função ao evento de clique
	button.MouseButton1Click:Connect(toggleColor)
end
coroutine.wrap(XZAB_fake_script)()
local function ACEGN_fake_script() -- TextButton_3.auto farme 
	local script = Instance.new('LocalScript', TextButton_3)

	local Players = game:GetService("Players")
	local LocalPlayer = Players.LocalPlayer
	local running = false
	local autofarmThread = nil
	
	-- Referência ao botão (este script deve estar dentro do mesmo ScreenGui ou no botão)
	local button = script.Parent  -- se o script estiver dentro do botão
	-- Se estiver em outro lugar, use algo como: local button = script.Parent:WaitForChild("ToggleButton")
	
	button.MouseButton1Click:Connect(function()
		running = not running
		button.Text = running and "Desativar AutoFarm" or "Ativar AutoFarm"
	
		if running and not autofarmThread then
			autofarmThread = task.spawn(function()
				while running do
					local character = LocalPlayer.Character or LocalPlayer.CharacterAdded:Wait()
					local hrp = character:WaitForChild("HumanoidRootPart")
					local targets = {}
	
					local amberFolder = workspace:FindFirstChild("ItemSpawn") and workspace.ItemSpawn:FindFirstChild("Amber")
					if amberFolder then
						for _, part in pairs(amberFolder:GetChildren()) do
							if part:IsA("Part") and part.Name == "AmberSpawn" then
								for _, child in ipairs(part:GetChildren()) do
									if child:IsA("Model") then
										local prompt = child:FindFirstChildWhichIsA("ProximityPrompt", true)
										if prompt then
											table.insert(targets, {part = part, prompt = prompt})
										end
									end
								end
							end
						end
					end
	
					for _, data in ipairs(targets) do
						if not running then break end
						hrp.CFrame = data.part.CFrame + Vector3.new(0, 3, 0)
						task.wait(0.5)
						fireproximityprompt(data.prompt, 3)
						task.wait(0.5)
					end
	
					task.wait(1)
				end
				autofarmThread = nil -- limpa a thread quando parar
			end)
		end
	end)
	
end
coroutine.wrap(ACEGN_fake_script)()
local function WKQYXEP_fake_script() -- TextButton_4.LocalScript 
	local script = Instance.new('LocalScript', TextButton_4)

	-- Script para botão que alterna cor ao clicar
	-- Coloque este script como LocalScript dentro do botão (TextButton ou ImageButton)
	
	local button = script.Parent -- O botão onde o script está
	local originalColor = button.BackgroundColor3 -- Salva a cor original
	local isGreen = false -- Controla se está verde ou não
	
	-- Função que executa quando o botão é clicado
	local function toggleColor()
		if isGreen then
			-- Se está verde, volta para a cor original
			button.BackgroundColor3 = originalColor
			isGreen = false
			print("Botão voltou para cor original")
		else
			-- Se não está verde, fica verde
			button.BackgroundColor3 = Color3.new(0, 1, 0) -- Verde puro
			isGreen = true
			print("Botão ficou verde")
		end
	end
	
	-- Conecta a função ao evento de clique
	button.MouseButton1Click:Connect(toggleColor)
end
coroutine.wrap(WKQYXEP_fake_script)()
local function LZVB_fake_script() -- TextButton_4.fly 
	local script = Instance.new('LocalScript', TextButton_4)

	local Players = game:GetService("Players")
	local UserInputService = game:GetService("UserInputService")
	local RunService = game:GetService("RunService")
	
	local player = Players.LocalPlayer
	local button = script.Parent -- botão que ativa/desativa o fly
	
	local flying = false
	local flySpeed = 100
	local flyConnection
	
	local character = player.Character or player.CharacterAdded:Wait()
	local hrp = character:WaitForChild("HumanoidRootPart")
	
	local bodyGyro
	local bodyVelocity
	
	-- Atualiza referência do personagem e HumanoidRootPart ao renascer
	local function updateCharacter()
		character = player.Character or player.CharacterAdded:Wait()
		hrp = character:WaitForChild("HumanoidRootPart")
	end
	
	local function getDirection()
		local moveDir = Vector3.zero
		local vertical = 0
	
		-- Corrigido: W para frente (-Z), S para trás (+Z)
		if UserInputService:IsKeyDown(Enum.KeyCode.S) then
			moveDir += Vector3.new(0, 0, -1)
		end
		if UserInputService:IsKeyDown(Enum.KeyCode.W) then
			moveDir += Vector3.new(0, 0, 1)
		end
		if UserInputService:IsKeyDown(Enum.KeyCode.A) then
			moveDir += Vector3.new(-1, 0, 0)
		end
		if UserInputService:IsKeyDown(Enum.KeyCode.D) then
			moveDir += Vector3.new(1, 0, 0)
		end
		if UserInputService:IsKeyDown(Enum.KeyCode.Space) then
			vertical += 1
		end
		if UserInputService:IsKeyDown(Enum.KeyCode.LeftControl) then
			vertical -= 1
		end
	
		return moveDir, vertical
	end
	
	local function startFly()
		if not hrp then return end
	
		bodyGyro = Instance.new("BodyGyro")
		bodyGyro.P = 9e4
		bodyGyro.MaxTorque = Vector3.new(9e9, 9e9, 9e9)
		bodyGyro.CFrame = hrp.CFrame
		bodyGyro.Parent = hrp
	
		bodyVelocity = Instance.new("BodyVelocity")
		bodyVelocity.Velocity = Vector3.zero
		bodyVelocity.MaxForce = Vector3.new(9e9, 9e9, 9e9)
		bodyVelocity.Parent = hrp
	
		flyConnection = RunService.RenderStepped:Connect(function()
			local moveDir, vertical = getDirection()
			local camCF = workspace.CurrentCamera.CFrame
			local dir = (camCF.RightVector * moveDir.X + camCF.LookVector * moveDir.Z).Unit
			if dir ~= dir then dir = Vector3.zero end
			local finalVelocity = dir * flySpeed + Vector3.new(0, vertical * flySpeed, 0)
	
			bodyVelocity.Velocity = finalVelocity
			bodyGyro.CFrame = CFrame.new(Vector3.zero, camCF.LookVector)
		end)
	end
	
	local function stopFly()
		if flyConnection then
			flyConnection:Disconnect()
			flyConnection = nil
		end
		if bodyGyro then
			bodyGyro:Destroy()
			bodyGyro = nil
		end
		if bodyVelocity then
			bodyVelocity:Destroy()
			bodyVelocity = nil
		end
	end
	
	button.MouseButton1Click:Connect(function()
		flying = not flying
		button.Text = flying and "Desativar Fly" or "Ativar Fly"
	
		if flying then
			startFly()
		else
			stopFly()
		end
	end)
	
	-- Quando o personagem renascer, atualiza referências e religa fly se estiver ativo
	player.CharacterAdded:Connect(function()
		updateCharacter()
	
		if flying then
			task.wait(0.5) -- espera o personagem carregar direito
			startFly()
		end
	end)
	
end
coroutine.wrap(LZVB_fake_script)()
local function YCYZ_fake_script() -- ImageButton.LocalScript 
	local script = Instance.new('LocalScript', ImageButton)

	-- Script para ImageButton controlar um Frame existente
	-- Coloque este script como LocalScript dentro do ImageButton
	
	local imageButton = script.Parent -- ImageButton onde o script está
	
	-- CONFIGURE AQUI: Caminho para seu frame existente
	-- Exemplo: se seu frame está em StarterGui > ScreenGui > MeuFrame
	-- Coloque: local targetFrame = script.Parent.Parent.MeuFrame
	-- Ou se está em PlayerGui: local targetFrame = Players.LocalPlayer.PlayerGui.ScreenGui.MeuFrame
	
	local Players = game:GetService("Players")
	local player = Players.LocalPlayer
	
	-- MUDE ESTA LINHA para o caminho do seu frame:
	local targetFrame = script.Parent.Parent.gatunohub -- <-- COLOQUE O NOME DO SEU FRAME AQUI
	
	-- Variável para controlar se está aberto ou fechado
	local isOpen = true -- Começa como true se seu frame já está visível, ou false se está escondido
	
	-- Função para alternar visibilidade do frame
	local function toggleFrame()
		if targetFrame then
			if isOpen then
				-- Esconder o frame
				targetFrame.Visible = false
				isOpen = false
				print("🔴 Frame escondido!")
			else
				-- Mostrar o frame
				targetFrame.Visible = true
				isOpen = true
				print("🟢 Frame mostrado!")
			end
		else
			warn("❌ Frame não encontrado! Verifique o caminho em 'targetFrame'")
		end
	end
	
	-- Conectar o clique do ImageButton
	imageButton.MouseButton1Click:Connect(function()
		toggleFrame()
	end)
	
	print("✅ ImageButton configurado para controlar frame existente!")
end
coroutine.wrap(YCYZ_fake_script)()
local function JUBBSBM_fake_script() -- ImageButton.LocalScript 
	local script = Instance.new('LocalScript', ImageButton)

	local UIS = game:GetService("UserInputService")
	local RunService = game:GetService("RunService")
	
	local button = script.Parent
	local dragging
	local dragInput
	local dragStart
	local startPos
	
	local function update(input)
		local delta = input.Position - dragStart
		button.Position = UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X, startPos.Y.Scale, startPos.Y.Offset + delta.Y)
	end
	
	button.InputBegan:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
			dragging = true
			dragStart = input.Position
			startPos = button.Position
	
			input.Changed:Connect(function()
				if input.UserInputState == Enum.UserInputState.End then
					dragging = false
				end
			end)
		end
	end)
	
	button.InputChanged:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
			dragInput = input
		end
	end)
	
	RunService.RenderStepped:Connect(function()
		if dragging and dragInput then
			update(dragInput)
		end
	end)
	
end
coroutine.wrap(JUBBSBM_fake_script)()
