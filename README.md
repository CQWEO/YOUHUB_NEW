task.wait(1.5)
--[[]]
local YOUHUB = {};
YOUHUB["1"] = Instance.new("ScreenGui", game:GetService("Players").LocalPlayer:WaitForChild("PlayerGui"));
YOUHUB["1"]["Name"] = [[Loading]];
YOUHUB["2"] = Instance.new("Frame", YOUHUB["1"]);
YOUHUB["2"]["BorderSizePixel"] = 0;
YOUHUB["2"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
YOUHUB["2"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
YOUHUB["2"]["Size"] = UDim2.new(0, 400, 0, 300);
YOUHUB["2"]["ClipsDescendants"] = true;
YOUHUB["2"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
YOUHUB["2"]["Position"] = UDim2.new(0.5, 0, 0.5, 0);
YOUHUB["2"]["Name"] = [[MainFrame]];
YOUHUB["3"] = Instance.new("UICorner", YOUHUB["2"]);
YOUHUB["3"]["Name"] = [[Corner]];
YOUHUB["3"]["CornerRadius"] = UDim.new(0, 6);
YOUHUB["4"] = Instance.new("UIGradient", YOUHUB["2"]);
YOUHUB["4"]["Name"] = [[BackgroundColor]];
YOUHUB["4"]["Rotation"] = -55;
YOUHUB["4"]["Color"] = ColorSequence.new{ColorSequenceKeypoint.new(0.000, Color3.fromRGB(36, 36, 36)),ColorSequenceKeypoint.new(0.345, Color3.fromRGB(66, 66, 66)),ColorSequenceKeypoint.new(0.466, Color3.fromRGB(66, 66, 66)),ColorSequenceKeypoint.new(1.000, Color3.fromRGB(101, 101, 101))};
YOUHUB["4"]["Offset"] = Vector2.new(0, -0.25);
YOUHUB["5"] = Instance.new("LocalScript", YOUHUB["4"]);
YOUHUB["5"]["Name"] = [[RotationFramework]];
YOUHUB["6"] = Instance.new("TextLabel", YOUHUB["2"]);
YOUHUB["6"]["TextWrapped"] = true;
YOUHUB["6"]["BorderSizePixel"] = 0;
YOUHUB["6"]["TextScaled"] = true;
YOUHUB["6"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
YOUHUB["6"]["FontFace"] = Font.new([[rbxasset://fonts/families/Ubuntu.json]], Enum.FontWeight.Bold, Enum.FontStyle.Normal);
YOUHUB["6"]["TextSize"] = 14;
YOUHUB["6"]["TextColor3"] = Color3.fromRGB(255, 255, 255);
YOUHUB["6"]["Size"] = UDim2.new(0, 216, 0, 63);
YOUHUB["6"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
YOUHUB["6"]["Text"] = [[YOU HUB LOADING...]];
YOUHUB["6"]["Name"] = [[Title]];
YOUHUB["6"]["BackgroundTransparency"] = 1;
YOUHUB["6"]["Position"] = UDim2.new(1, -235, 1, -185);
YOUHUB["7"] = Instance.new("ImageLabel", YOUHUB["2"]);
YOUHUB["7"]["BorderSizePixel"] = 0;
YOUHUB["7"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
YOUHUB["7"]["Image"] = [[http://www.roblox.com/asset/?id=14044876843]];
YOUHUB["7"]["Size"] = UDim2.new(0, 125, 0, 105);
YOUHUB["7"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
YOUHUB["7"]["Name"] = [[Logo]];
YOUHUB["7"]["BackgroundTransparency"] = 1;
YOUHUB["7"]["Position"] = UDim2.new(0.05000000074505806, 0, 1, -205);
YOUHUB["8"] = Instance.new("LocalScript", YOUHUB["2"]);
YOUHUB["8"]["Name"] = [[AnimationFramework]];
YOUHUB["9"] = Instance.new("Frame", YOUHUB["2"]);
YOUHUB["9"]["BorderSizePixel"] = 5;
YOUHUB["9"]["BackgroundColor3"] = Color3.fromRGB(0, 0, 0);
YOUHUB["9"]["Size"] = UDim2.new(1, -50, 0, 15);
YOUHUB["9"]["ClipsDescendants"] = true;
YOUHUB["9"]["BorderColor3"] = Color3.fromRGB(54, 55, 54);
YOUHUB["9"]["Position"] = UDim2.new(0, 25, 0, 250);
YOUHUB["9"]["Name"] = [[LoadingFrame]];
YOUHUB["a"] = Instance.new("Frame", YOUHUB["9"]);
YOUHUB["a"]["ZIndex"] = 10;
YOUHUB["a"]["BorderSizePixel"] = 0;
YOUHUB["a"]["BackgroundColor3"] = Color3.fromRGB(119, 180, 158);
YOUHUB["a"]["Size"] = UDim2.new(1, 0, 1, 0);
YOUHUB["a"]["ClipsDescendants"] = true;
YOUHUB["a"]["BorderColor3"] = Color3.fromRGB(54, 55, 54);
YOUHUB["a"]["Position"] = UDim2.new(0, 0, 0, 1);
YOUHUB["a"]["Name"] = [[LoadingBar]];
YOUHUB["b"] = Instance.new("UICorner", YOUHUB["a"]);
YOUHUB["b"]["Name"] = [[Corner]];
YOUHUB["b"]["CornerRadius"] = UDim.new(0, 4);
YOUHUB["c"] = Instance.new("IntValue", YOUHUB["a"]);
YOUHUB["c"]["Name"] = [[Percentage]];
YOUHUB["d"] = Instance.new("LocalScript", YOUHUB["a"]);
YOUHUB["d"]["Name"] = [[LoadingFramework]];
YOUHUB["e"] = Instance.new("LocalScript", YOUHUB["a"]);
YOUHUB["e"]["Name"] = [[Entities]];
YOUHUB["f"] = Instance.new("UICorner", YOUHUB["9"]);
YOUHUB["Name"] = [[Corner]];
YOUHUB["f"]["CornerRadius"] = UDim.new(0, 4);
YOUHUB["10"] = Instance.new("UIStroke", YOUHUB["9"]);
YOUHUB["10"]["Color"] = Color3.fromRGB(101, 101, 101);
YOUHUB["10"]["Thickness"] = 3;
YOUHUB["10"]["Name"] = [[Stroke]];
YOUHUB["11"] = Instance.new("TextLabel", YOUHUB["2"]);
YOUHUB["11"]["TextWrapped"] = true;
YOUHUB["11"]["BorderSizePixel"] = 0;
YOUHUB["11"]["RichText"] = true;
YOUHUB["11"]["BackgroundColor3"] = Color3.fromRGB(255, 255, 255);
YOUHUB["11"]["FontFace"] = Font.new([[rbxasset://fonts/families/SourceSansPro.json]], Enum.FontWeight.Regular, Enum.FontStyle.Normal);
YOUHUB["11"]["TextSize"] = 30;
YOUHUB["11"]["TextColor3"] = Color3.fromRGB(114, 114, 114);
YOUHUB["11"]["AnchorPoint"] = Vector2.new(0.5, 0.5);
YOUHUB["11"]["Size"] = UDim2.new(0, 2100, 0, 50);
YOUHUB["11"]["BorderColor3"] = Color3.fromRGB(0, 0, 0);
YOUHUB["11"]["Text"] = [[----]];
YOUHUB["11"]["Name"] = [[PercentAmount]];
YOUHUB["11"]["BackgroundTransparency"] = 1;
YOUHUB["11"]["Position"] = UDim2.new(0.5, 0, 0.75, 10);
YOUHUB["12"] = Instance.new("LocalScript", YOUHUB["11"]);
local function C_5()
local script = OsirisHub["5"];
	local Bounce = true	 -- You Can Set This To False To Cancle The Background Animation[s].
	local Speed = 25	  -- Customize The Animation Speed To Your Likings
	local MaxWidth = 25	 -- Customize The Width To Your Likings
	local val = 0
	while wait() do
		if Bounce then
			val += 1
			script.Parent.Rotation = (math.sin(((val * MaxWidth) / (Speed))) - 55)
		end
	end
end;
task.spawn(C_5);
local function C_8()
local script = YOUHUB["9"];
	local BeginingSize = UDim2.new(9, 5, 9, 5)
	local MainSize = UDim2.new(0, 1200, 0, 630)
	local SpreadSize = UDim2.new(0, 1400, 0, 5)
	script.Parent.BackgroundTransparency = 0
	script.Parent.Size = BeginingSize
	for i = 0, 10 do
		script.Parent.BackgroundTransparency -= 0.1
	end
	script.Parent:TweenSize(
		SpreadSize,
		Enum.EasingDirection.InOut,
		Enum.EasingStyle.Linear,
		1,
		true
	)
	wait(1.25)
	script.Parent:TweenSize(
		MainSize, 
		Enum.EasingDirection.InOut,
		Enum.EasingStyle.Linear, 
		1, 
		true
	)
end;
task.spawn(C_8);
local function C_d()
local script = YOUHUB["d"];
	script.Parent.Percentage.Value = 0
	while wait() do
		script.Parent:TweenSize(
			UDim2.new((script.Parent.Percentage.Value / 100),0,1,0),
			Enum.EasingDirection.Out,
			Enum.EasingStyle.Linear,
			0.1,
			true
		)
	end
end;
task.spawn(C_d);
local function C_e()
local script = YOUHUB["e"];
	local Status = script.Parent.Percentage
	local num = nil
	while not (Status.Value >= 100) do
		num = math.random(0.1, 3)
		wait(num)
		num = math.random(1, 10)
		for i = 1, num do
			wait()
			Status.Value = Status.Value + 1
		end
		if Status.Value > 100 then
			Status.Value = 100
		end
	end
	if Status.Value > 100 then
		Status.Value = 100
	end
	wait(2)
	script.Parent.Parent.Parent:TweenSize(
		UDim2.new(0,0,0,0),
		Enum.EasingDirection.Out,
		Enum.EasingStyle.Back, 
		1, 
		true
	)
end;
task.spawn(C_e);
local function C_12()
local script = YOUHUB["12"];
	while wait() do
		script.Parent.Text = (script.Parent.Parent.LoadingFrame.LoadingBar.Percentage.Value .. "%")
	end
end;
task.spawn(C_12);
return YOUHUB["1"], wait(60)> 
