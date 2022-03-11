	for i,v in pairs(game.Workspace:GetDescendants()) do -- grabs everything from workspace
		if v.Name == 'Map' then -- checks if it has a handle and if its a touchtransmitter
			local BillboardGui = Instance.new('BillboardGui') -- Makes Billboardgui
			local TextLabel = Instance.new('TextLabel') -- makes text label

			BillboardGui.Parent = v.SafeHouse.Light.RustyLightBase -- what the billboardgui goes into
			BillboardGui.AlwaysOnTop = true -- if its on top or not
			BillboardGui.Size = UDim2.new(0, 50, 0, 50) -- size of it
			BillboardGui.StudsOffset = Vector3.new(0,2,0)

			TextLabel.Parent = BillboardGui -- putting textlabel into billboardgui
			TextLabel.BackgroundColor3 = Color3.new(1,1,1) -- color
			TextLabel.BackgroundTransparency = 1 -- transparency
			TextLabel.Size = UDim2.new(1, 0, 1, 0) -- size
			TextLabel.Text = "Safe House" -- what the label says
			TextLabel.TextColor3 = Color3.new(1, 0, 0) -- color
			TextLabel.TextScaled = true -- if the text is scaled or not
			print('Worked')
		end
	end

	for i,v in pairs(game.Workspace:GetDescendants()) do -- grabs everything from workspace
		if v.Name == 'Map' then -- checks if it has a handle and if its a touchtransmitter
			local BillboardGui = Instance.new('BillboardGui') -- Makes Billboardgui
			local TextLabel = Instance.new('TextLabel') -- makes text label

			BillboardGui.Parent = v.ObservationTower.Lights.Core -- what the billboardgui goes into
			BillboardGui.AlwaysOnTop = true -- if its on top or not
			BillboardGui.Size = UDim2.new(0, 50, 0, 50) -- size of it
			BillboardGui.StudsOffset = Vector3.new(0,2,0)

			TextLabel.Parent = BillboardGui -- putting textlabel into billboardgui
			TextLabel.BackgroundColor3 = Color3.new(1,1,1) -- color
			TextLabel.BackgroundTransparency = 1 -- transparency
			TextLabel.Size = UDim2.new(1, 0, 1, 0) -- size
			TextLabel.Text = "Observation Tower" -- what the label says
			TextLabel.TextColor3 = Color3.new(1, 0, 0) -- color
			TextLabel.TextScaled = true -- if the text is scaled or not
			print('Worked2')
		end
	end

	for i,v in pairs(game.Workspace:GetDescendants()) do -- grabs everything from workspace
		if v.Name == 'Map' then -- checks if it has a handle and if its a touchtransmitter
			local BillboardGui = Instance.new('BillboardGui') -- Makes Billboardgui
			local TextLabel = Instance.new('TextLabel') -- makes text label

			BillboardGui.Parent = v.PowerStation.StationFolder.LightButton -- what the billboardgui goes into
			BillboardGui.AlwaysOnTop = true -- if its on top or not
			BillboardGui.Size = UDim2.new(0, 50, 0, 50) -- size of it
			BillboardGui.StudsOffset = Vector3.new(0,2,0)

			TextLabel.Parent = BillboardGui -- putting textlabel into billboardgui
			TextLabel.BackgroundColor3 = Color3.new(1,1,1) -- color
			TextLabel.BackgroundTransparency = 1 -- transparency
			TextLabel.Size = UDim2.new(1, 0, 1, 0) -- size
			TextLabel.Text = "Power Station" -- what the label says
			TextLabel.TextColor3 = Color3.new(1, 0, 0) -- color
			TextLabel.TextScaled = true -- if the text is scaled or not
			print('Worked3')
		end
	end

	for i,v in pairs(game.Workspace:GetDescendants()) do -- grabs everything from workspace
		if v.Name == 'Map' then -- checks if it has a handle and if its a touchtransmitter
			local BillboardGui = Instance.new('BillboardGui') -- Makes Billboardgui
			local TextLabel = Instance.new('TextLabel') -- makes text label
			BillboardGui.Parent = v.Shack.ShopPart-- what the billboardgui goes into
			BillboardGui.AlwaysOnTop = true -- if its on top or not
			BillboardGui.Size = UDim2.new(0, 50, 0, 50) -- size of it
			BillboardGui.StudsOffset = Vector3.new(0,2,0)

			TextLabel.Parent = BillboardGui -- putting textlabel into billboardgui
			TextLabel.BackgroundColor3 = Color3.new(1,1,1) -- color
			TextLabel.BackgroundTransparency = 1 -- transparency
			TextLabel.Size = UDim2.new(1, 0, 1, 0) -- size
			TextLabel.Text = "Shop" -- what the label says
			TextLabel.TextColor3 = Color3.new(1, 0, 0) -- color
			TextLabel.TextScaled = true -- if the text is scaled or not
			print('Worked4')
		end
	end
	for i,v in pairs(game.Workspace:GetDescendants()) do -- grabs everything from workspace
		if v.Name == 'Map' then -- checks if it has a handle and if its a touchtransmitter
			local BillboardGui = Instance.new('BillboardGui') -- Makes Billboardgui
			local TextLabel = Instance.new('TextLabel') -- makes text label

			BillboardGui.Parent = v.BaseCamp.TargetRegionPart -- what the billboardgui goes into
			BillboardGui.AlwaysOnTop = true -- if its on top or not
			BillboardGui.Size = UDim2.new(0, 50, 0, 50) -- size of it
			BillboardGui.StudsOffset = Vector3.new(0,2,0)

			TextLabel.Parent = BillboardGui -- putting textlabel into billboardgui
			TextLabel.BackgroundColor3 = Color3.new(1,1,1) -- color
			TextLabel.BackgroundTransparency = 1 -- transparency
			TextLabel.Size = UDim2.new(1, 0, 1, 0) -- size
			TextLabel.Text = "Base Camp" -- what the label says
			TextLabel.TextColor3 = Color3.new(1, 0, 0) -- color
			TextLabel.TextScaled = true -- if the text is scaled or not
			print('Worked4')
		end
	end
end)
