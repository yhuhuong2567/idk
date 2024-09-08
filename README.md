local Nova = {}

function Nova:CreateGui()
    local function CreateInstance(cls,props)
        local inst = Instance.new(cls)
        for i,v in pairs(props) do
            inst[i] = v
        end
        return inst
        end
        local StandsFarm = CreateInstance('ScreenGui',{DisplayOrder=0,Enabled=true,ResetOnSpawn=true,Name='StandsFarm', Parent=game.CoreGui})
        local StandsGUI = CreateInstance('Frame',{Style=Enum.FrameStyle.RobloxRound,Active=false,AnchorPoint=Vector2.new(0.5, 0.5),BackgroundColor3=Color3.new(0.156863, 0.156863, 0.156863),BackgroundTransparency=0,BorderColor3=Color3.new(0.105882, 0.164706, 0.207843),BorderSizePixel=0,ClipsDescendants=false,Draggable=false,Position=UDim2.new(2, 0, 0.545793176, 0),Rotation=0,Selectable=false,Size=UDim2.new(0, 612, 0, 335),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name = 'StandsGUI',Parent = StandsFarm})
        local bar = CreateInstance('Frame',{Style=Enum.FrameStyle.RobloxRound,Active=false,AnchorPoint=Vector2.new(0.5, 0.5),BackgroundColor3=Color3.new(0.117647, 0.117647, 0.117647),BackgroundTransparency=0,BorderColor3=Color3.new(0.105882, 0.164706, 0.207843),BorderSizePixel=1,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.499533683, 0, 0.0106219817, 0),Rotation=0,Selectable=false,Size=UDim2.new(0, 612, 0, 24),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name = 'bar',Parent = StandsGUI})
        local closegui = CreateInstance('ImageButton',{Image='rbxassetid://3494886164',ImageColor3=Color3.new(1, 1, 1),ImageRectOffset=Vector2.new(0, 0),ImageRectSize=Vector2.new(0, 0),ImageTransparency=0,ScaleType=Enum.ScaleType.Stretch,SliceCenter=Rect.new(0, 0, 0, 0),AutoButtonColor=true,Modal=false,Selected=false,Style=Enum.ButtonStyle.Custom,Active=true,AnchorPoint=Vector2.new(0.5, 0.5),BackgroundColor3=Color3.new(0.117647, 0.117647, 0.117647),BackgroundTransparency=1,BorderColor3=Color3.new(0.105882, 0.164706, 0.207843),BorderSizePixel=0,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.97882539, 0, 0.458333343, 0),Rotation=0,Selectable=true,Size=UDim2.new(0, 25, 0, 22),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='closegui',Parent = bar})
        local btnNext = CreateInstance('ImageButton',{Image='rbxassetid://932030878',ImageColor3=Color3.new(1, 1, 1),ImageRectOffset=Vector2.new(0, 0),ImageRectSize=Vector2.new(0, 0),ImageTransparency=0,ScaleType=Enum.ScaleType.Stretch,SliceCenter=Rect.new(0, 0, 0, 0),AutoButtonColor=true,Modal=false,Selected=false,Style=Enum.ButtonStyle.Custom,Active=true,AnchorPoint=Vector2.new(0.5, 0.5),BackgroundColor3=Color3.new(0.117647, 0.117647, 0.117647),BackgroundTransparency=1,BorderColor3=Color3.new(0.105882, 0.164706, 0.207843),BorderSizePixel=0,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.0189999994, 0, 0.430999994, 0),Rotation=0,Selectable=true,Size=UDim2.new(0, 25, 0, 21),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='btnNext',Parent = bar})
        local btnBack = CreateInstance('ImageButton',{Image='rbxassetid://932436179',ImageColor3=Color3.new(1, 1, 1),ImageRectOffset=Vector2.new(0, 0),ImageRectSize=Vector2.new(0, 0),ImageTransparency=0,ScaleType=Enum.ScaleType.Stretch,SliceCenter=Rect.new(0, 0, 0, 0),AutoButtonColor=true,Modal=false,Selected=false,Style=Enum.ButtonStyle.Custom,Active=true,AnchorPoint=Vector2.new(0.5, 0.5),BackgroundColor3=Color3.new(0.117647, 0.117647, 0.117647),BackgroundTransparency=1,BorderColor3=Color3.new(0.105882, 0.164706, 0.207843),BorderSizePixel=0,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.0189999994, 0, 0.430999994, 0),Rotation=0,Selectable=true,Size=UDim2.new(0, 25, 0, 21),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=false,ZIndex=1,Name='btnBack',Parent = bar})
        local c1 = CreateInstance('Frame',{Style=Enum.FrameStyle.Custom,Active=false,AnchorPoint=Vector2.new(0.5, 0.5),BackgroundColor3=Color3.new(1, 1, 1),BackgroundTransparency=1,BorderColor3=Color3.new(0.105882, 0.164706, 0.207843),BorderSizePixel=1,ClipsDescendants=true,Draggable=false,Position=UDim2.new(0.498890102, 0, 0.519739747, 0),Rotation=0,Selectable=false,Size=UDim2.new(0, 596, 0, 295),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name = 'c1',Parent = StandsGUI})
        local UIGridLayout = CreateInstance('UIGridLayout', {CellPadding = UDim2.new(0, 10, 0, 2), CellSize = UDim2.new(0, 140, 0, 25), FillDirectionMaxCells = 0, StartCorner=Enum.StartCorner.TopLeft, FillDirection=Enum.FillDirection.Vertical, HorizontalAlignment = Enum.HorizontalAlignment.Left, SortOrder = Enum.SortOrder.LayoutOrder, VerticalAlignment = Enum.VerticalAlignment.Top, Name = 'UIGridLayout', Parent = c1 })
        local c2 = CreateInstance('Frame',{Style=Enum.FrameStyle.Custom,Active=false,AnchorPoint=Vector2.new(0.5, 0.5),BackgroundColor3=Color3.new(1, 1, 1),BackgroundTransparency=1,BorderColor3=Color3.new(0.105882, 0.164706, 0.207843),BorderSizePixel=1,ClipsDescendants=true,Draggable=false,Position=UDim2.new(0.498890102, 0, 0.519739747, 0),Rotation=0,Selectable=false,Size=UDim2.new(0, 596, 0, 295),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=false,ZIndex=1,Name = 'c2',Parent = StandsGUI})
        local UIGridLayout = CreateInstance('UIGridLayout', {CellPadding = UDim2.new(0, 10, 0, 2), CellSize = UDim2.new(0, 140, 0, 25), FillDirectionMaxCells = 0, StartCorner=Enum.StartCorner.TopLeft, FillDirection=Enum.FillDirection.Vertical, HorizontalAlignment = Enum.HorizontalAlignment.Left, SortOrder = Enum.SortOrder.LayoutOrder, VerticalAlignment = Enum.VerticalAlignment.Top, Name = 'UIGridLayout', Parent = c2 })
        --trait
        local TraitsFarm = CreateInstance('ScreenGui',{DisplayOrder=0,Enabled=true,ResetOnSpawn=true,Name='TraitsFarm', Parent=game.CoreGui})
        local Menu = CreateInstance('Frame',{Style=Enum.FrameStyle.RobloxRound,Active=true,AnchorPoint=Vector2.new(0.5, 0.5),BackgroundColor3=Color3.new(0.156863, 0.156863, 0.156863),BackgroundTransparency=0,BorderColor3=Color3.new(0.105882, 0.164706, 0.207843),BorderSizePixel=0,ClipsDescendants=false,Draggable=true,Position=UDim2.new(0.576, -79,0.552, -5),Rotation=0,Selectable=false,Size=UDim2.new(0, 290, 0, 335),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=false,ZIndex=1,Name = 'Menu',Parent = TraitsFarm})
        local bartrait = CreateInstance('Frame',{Style=Enum.FrameStyle.RobloxRound,Active=false,AnchorPoint=Vector2.new(0.5, 0.5),BackgroundColor3=Color3.new(0.117647, 0.117647, 0.117647),BackgroundTransparency=0,BorderColor3=Color3.new(0.105882, 0.164706, 0.207843),BorderSizePixel=1,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.494731188, 0, 0.0150513388, 0),Rotation=0,Selectable=false,Size=UDim2.new(0, 291, 0, 24),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name = 'bartrait',Parent = Menu})
        local closetrait = CreateInstance('ImageButton',{Image='rbxassetid://3494886164',ImageColor3=Color3.new(1, 1, 1),ImageRectOffset=Vector2.new(0, 0),ImageRectSize=Vector2.new(0, 0),ImageTransparency=0,ScaleType=Enum.ScaleType.Stretch,SliceCenter=Rect.new(0, 0, 0, 0),AutoButtonColor=true,Modal=false,Selected=false,Style=Enum.ButtonStyle.Custom,Active=true,AnchorPoint=Vector2.new(0.5, 0.5),BackgroundColor3=Color3.new(0.117647, 0.117647, 0.117647),BackgroundTransparency=1,BorderColor3=Color3.new(0.105882, 0.164706, 0.207843),BorderSizePixel=0,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.97882539, 0, 0.458333343, 0),Rotation=0,Selectable=true,Size=UDim2.new(0, 25, 0, 22),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='closetrait',Parent = bartrait})
        local Slugger = CreateInstance('TextButton',{Font=Enum.Font.SourceSans,FontSize=Enum.FontSize.Size18,Text='Slugger',TextColor3=Color3.new(1, 1, 1),TextScaled=false,TextSize=18,TextStrokeColor3=Color3.new(0, 0, 0),TextStrokeTransparency=1,TextTransparency=0,TextWrapped=true,TextXAlignment=Enum.TextXAlignment.Center,TextYAlignment=Enum.TextYAlignment.Center,AutoButtonColor=true,Modal=false,Selected=false,Style=Enum.ButtonStyle.Custom,Active=true,AnchorPoint=Vector2.new(0, 0),BackgroundColor3=Color3.new(0.117647, 0.117647, 0.117647),BackgroundTransparency=0,BorderColor3=Color3.new(0.105882, 0.164706, 0.207843),BorderSizePixel=0,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.538200021, 0, 0.468377143, 0),Rotation=0,Selectable=true,Size=UDim2.new(0, 120, 0, 23),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='Slugger',Parent = Menu})
        local Brute = CreateInstance('TextButton',{Font=Enum.Font.SourceSans,FontSize=Enum.FontSize.Size18,Text='Brute',TextColor3=Color3.new(1, 1, 1),TextScaled=false,TextSize=18,TextStrokeColor3=Color3.new(0, 0, 0),TextStrokeTransparency=1,TextTransparency=0,TextWrapped=true,TextXAlignment=Enum.TextXAlignment.Center,TextYAlignment=Enum.TextYAlignment.Center,AutoButtonColor=true,Modal=false,Selected=false,Style=Enum.ButtonStyle.Custom,Active=true,AnchorPoint=Vector2.new(0, 0),BackgroundColor3=Color3.new(0.117647, 0.117647, 0.117647),BackgroundTransparency=0,BorderColor3=Color3.new(0.105882, 0.164706, 0.207843),BorderSizePixel=0,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.0468386933, 0, 0.285120964, 0),Rotation=0,Selectable=true,Size=UDim2.new(0, 120, 0, 23),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='Brute',Parent = Menu})
        local Tank = CreateInstance('TextButton',{Font=Enum.Font.SourceSans,FontSize=Enum.FontSize.Size18,Text='Tank',TextColor3=Color3.new(1, 1, 1),TextScaled=false,TextSize=18,TextStrokeColor3=Color3.new(0, 0, 0),TextStrokeTransparency=1,TextTransparency=0,TextWrapped=true,TextXAlignment=Enum.TextXAlignment.Center,TextYAlignment=Enum.TextYAlignment.Center,AutoButtonColor=true,Modal=false,Selected=false,Style=Enum.ButtonStyle.Custom,Active=true,AnchorPoint=Vector2.new(0, 0),BackgroundColor3=Color3.new(0.117647, 0.117647, 0.117647),BackgroundTransparency=0,BorderColor3=Color3.new(0.105882, 0.164706, 0.207843),BorderSizePixel=0,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.538200021, 0, 0.74508065, 0),Rotation=0,Selectable=true,Size=UDim2.new(0, 120, 0, 23),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='Tank',Parent = Menu})
        local Quick = CreateInstance('TextButton',{Font=Enum.Font.SourceSans,FontSize=Enum.FontSize.Size18,Text='Quick',TextColor3=Color3.new(1, 1, 1),TextScaled=false,TextSize=18,TextStrokeColor3=Color3.new(0, 0, 0),TextStrokeTransparency=1,TextTransparency=0,TextWrapped=true,TextXAlignment=Enum.TextXAlignment.Center,TextYAlignment=Enum.TextYAlignment.Center,AutoButtonColor=true,Modal=false,Selected=false,Style=Enum.ButtonStyle.Custom,Active=true,AnchorPoint=Vector2.new(0, 0),BackgroundColor3=Color3.new(0.117647, 0.117647, 0.117647),BackgroundTransparency=0,BorderColor3=Color3.new(0.105882, 0.164706, 0.207843),BorderSizePixel=0,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.538200021, 0, 0.281937331, 0),Rotation=0,Selectable=true,Size=UDim2.new(0, 120, 0, 23),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='Quick',Parent = Menu})
        local Timid = CreateInstance('TextButton',{Font=Enum.Font.SourceSans,FontSize=Enum.FontSize.Size18,Text='Timid',TextColor3=Color3.new(1, 1, 1),TextScaled=false,TextSize=18,TextStrokeColor3=Color3.new(0, 0, 0),TextStrokeTransparency=1,TextTransparency=0,TextWrapped=true,TextXAlignment=Enum.TextXAlignment.Center,TextYAlignment=Enum.TextYAlignment.Center,AutoButtonColor=true,Modal=false,Selected=false,Style=Enum.ButtonStyle.Custom,Active=true,AnchorPoint=Vector2.new(0, 0),BackgroundColor3=Color3.new(0.117647, 0.117647, 0.117647),BackgroundTransparency=0,BorderColor3=Color3.new(0.105882, 0.164706, 0.207843),BorderSizePixel=0,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.538200021, 0, 0.842166483, 0),Rotation=0,Selectable=true,Size=UDim2.new(0, 120, 0, 23),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='Timid',Parent = Menu})
        local Resilient = CreateInstance('TextButton',{Font=Enum.Font.SourceSans,FontSize=Enum.FontSize.Size18,Text='Resilient',TextColor3=Color3.new(1, 1, 1),TextScaled=false,TextSize=18,TextStrokeColor3=Color3.new(0, 0, 0),TextStrokeTransparency=1,TextTransparency=0,TextWrapped=true,TextXAlignment=Enum.TextXAlignment.Center,TextYAlignment=Enum.TextYAlignment.Center,AutoButtonColor=true,Modal=false,Selected=false,Style=Enum.ButtonStyle.Custom,Active=true,AnchorPoint=Vector2.new(0, 0),BackgroundColor3=Color3.new(0.117647, 0.117647, 0.117647),BackgroundTransparency=0,BorderColor3=Color3.new(0.105882, 0.164706, 0.207843),BorderSizePixel=0,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.538102746, 0, 0.369543284, 0),Rotation=0,Selectable=true,Size=UDim2.new(0, 120, 0, 23),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='Resilient',Parent = Menu})
        local Agile = CreateInstance('TextButton',{Font=Enum.Font.SourceSans,FontSize=Enum.FontSize.Size18,Text='Agile',TextColor3=Color3.new(1, 1, 1),TextScaled=false,TextSize=18,TextStrokeColor3=Color3.new(0, 0, 0),TextStrokeTransparency=1,TextTransparency=0,TextWrapped=true,TextXAlignment=Enum.TextXAlignment.Center,TextYAlignment=Enum.TextYAlignment.Center,AutoButtonColor=true,Modal=false,Selected=false,Style=Enum.ButtonStyle.Custom,Active=true,AnchorPoint=Vector2.new(0, 0),BackgroundColor3=Color3.new(0.117647, 0.117647, 0.117647),BackgroundTransparency=0,BorderColor3=Color3.new(0.105882, 0.164706, 0.207843),BorderSizePixel=0,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.0468386933, 0, 0.087794289, 0),Rotation=0,Selectable=true,Size=UDim2.new(0, 120, 0, 23),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='Agile',Parent = Menu})
        local Humble = CreateInstance('TextButton',{Font=Enum.Font.SourceSans,FontSize=Enum.FontSize.Size18,Text='Humble',TextColor3=Color3.new(1, 1, 1),TextScaled=false,TextSize=18,TextStrokeColor3=Color3.new(0, 0, 0),TextStrokeTransparency=1,TextTransparency=0,TextWrapped=true,TextXAlignment=Enum.TextXAlignment.Center,TextYAlignment=Enum.TextYAlignment.Center,AutoButtonColor=true,Modal=false,Selected=false,Style=Enum.ButtonStyle.Custom,Active=true,AnchorPoint=Vector2.new(0, 0),BackgroundColor3=Color3.new(0.117647, 0.117647, 0.117647),BackgroundTransparency=0,BorderColor3=Color3.new(0.105882, 0.164706, 0.207843),BorderSizePixel=0,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.0468386933, 0, 0.560388982, 0),Rotation=0,Selectable=true,Size=UDim2.new(0, 120, 0, 23),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='Humble',Parent = Menu})
        local Mighty = CreateInstance('TextButton',{Font=Enum.Font.SourceSans,FontSize=Enum.FontSize.Size18,Text='Mighty',TextColor3=Color3.new(1, 1, 1),TextScaled=false,TextSize=18,TextStrokeColor3=Color3.new(0, 0, 0),TextStrokeTransparency=1,TextTransparency=0,TextWrapped=true,TextXAlignment=Enum.TextXAlignment.Center,TextYAlignment=Enum.TextYAlignment.Center,AutoButtonColor=true,Modal=false,Selected=false,Style=Enum.ButtonStyle.Custom,Active=true,AnchorPoint=Vector2.new(0, 0),BackgroundColor3=Color3.new(0.117647, 0.117647, 0.117647),BackgroundTransparency=0,BorderColor3=Color3.new(0.105882, 0.164706, 0.207843),BorderSizePixel=0,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.538348615, 0, 0.086256519, 0),Rotation=0,Selectable=true,Size=UDim2.new(0, 120, 0, 23),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='Mighty',Parent = Menu})
        local Strong = CreateInstance('TextButton',{Font=Enum.Font.SourceSans,FontSize=Enum.FontSize.Size18,Text='Strong',TextColor3=Color3.new(1, 1, 1),TextScaled=false,TextSize=18,TextStrokeColor3=Color3.new(0, 0, 0),TextStrokeTransparency=1,TextTransparency=0,TextWrapped=true,TextXAlignment=Enum.TextXAlignment.Center,TextYAlignment=Enum.TextYAlignment.Center,AutoButtonColor=true,Modal=false,Selected=false,Style=Enum.ButtonStyle.Custom,Active=true,AnchorPoint=Vector2.new(0, 0),BackgroundColor3=Color3.new(0.117647, 0.117647, 0.117647),BackgroundTransparency=0,BorderColor3=Color3.new(0.105882, 0.164706, 0.207843),BorderSizePixel=0,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.538200021, 0, 0.654248476, 0),Rotation=0,Selectable=true,Size=UDim2.new(0, 120, 0, 23),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='Strong',Parent = Menu})
        local Indestructible = CreateInstance('TextButton',{Font=Enum.Font.SourceSans,FontSize=Enum.FontSize.Size18,Text='Indestructible',TextColor3=Color3.new(1, 1, 1),TextScaled=false,TextSize=18,TextStrokeColor3=Color3.new(0, 0, 0),TextStrokeTransparency=1,TextTransparency=0,TextWrapped=true,TextXAlignment=Enum.TextXAlignment.Center,TextYAlignment=Enum.TextYAlignment.Center,AutoButtonColor=true,Modal=false,Selected=false,Style=Enum.ButtonStyle.Custom,Active=true,AnchorPoint=Vector2.new(0, 0),BackgroundColor3=Color3.new(0.117647, 0.117647, 0.117647),BackgroundTransparency=0,BorderColor3=Color3.new(0.105882, 0.164706, 0.207843),BorderSizePixel=0,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.0468386933, 0, 0.746160984, 0),Rotation=0,Selectable=true,Size=UDim2.new(0, 120, 0, 23),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='Indestructible',Parent = Menu})
        local Speedy = CreateInstance('TextButton',{Font=Enum.Font.SourceSans,FontSize=Enum.FontSize.Size18,Text='Speedy',TextColor3=Color3.new(1, 1, 1),TextScaled=false,TextSize=18,TextStrokeColor3=Color3.new(0, 0, 0),TextStrokeTransparency=1,TextTransparency=0,TextWrapped=true,TextXAlignment=Enum.TextXAlignment.Center,TextYAlignment=Enum.TextYAlignment.Center,AutoButtonColor=true,Modal=false,Selected=false,Style=Enum.ButtonStyle.Custom,Active=true,AnchorPoint=Vector2.new(0, 0),BackgroundColor3=Color3.new(0.117647, 0.117647, 0.117647),BackgroundTransparency=0,BorderColor3=Color3.new(0.105882, 0.164706, 0.207843),BorderSizePixel=0,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.538200021, 0, 0.557447016, 0),Rotation=0,Selectable=true,Size=UDim2.new(0, 120, 0, 23),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='Speedy',Parent = Menu})
        local Powerhouse = CreateInstance('TextButton',{Font=Enum.Font.SourceSans,FontSize=Enum.FontSize.Size18,Text='Powerhouse',TextColor3=Color3.new(1, 1, 1),TextScaled=false,TextSize=18,TextStrokeColor3=Color3.new(0, 0, 0),TextStrokeTransparency=1,TextTransparency=0,TextWrapped=true,TextXAlignment=Enum.TextXAlignment.Center,TextYAlignment=Enum.TextYAlignment.Center,AutoButtonColor=true,Modal=false,Selected=false,Style=Enum.ButtonStyle.Custom,Active=true,AnchorPoint=Vector2.new(0, 0),BackgroundColor3=Color3.new(0.117647, 0.117647, 0.117647),BackgroundTransparency=0,BorderColor3=Color3.new(0.105882, 0.164706, 0.207843),BorderSizePixel=0,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.538200021, 0, 0.183984607, 0),Rotation=0,Selectable=true,Size=UDim2.new(0, 120, 0, 23),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='Powerhouse',Parent = Menu})
        local Godly = CreateInstance('TextButton',{Font=Enum.Font.SourceSans,FontSize=Enum.FontSize.Size18,Text='Godly',TextColor3=Color3.new(1, 1, 1),TextScaled=false,TextSize=18,TextStrokeColor3=Color3.new(0, 0, 0),TextStrokeTransparency=1,TextTransparency=0,TextWrapped=true,TextXAlignment=Enum.TextXAlignment.Center,TextYAlignment=Enum.TextYAlignment.Center,AutoButtonColor=true,Modal=false,Selected=false,Style=Enum.ButtonStyle.Custom,Active=true,AnchorPoint=Vector2.new(0, 0),BackgroundColor3=Color3.new(0.117647, 0.117647, 0.117647),BackgroundTransparency=0,BorderColor3=Color3.new(0.105882, 0.164706, 0.207843),BorderSizePixel=0,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.0468386933, 0, 0.471802384, 0),Rotation=0,Selectable=true,Size=UDim2.new(0, 120, 0, 23),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='Godly',Parent = Menu})
        local TextLabel = CreateInstance('TextLabel',{Font=Enum.Font.GothamSemibold,FontSize=Enum.FontSize.Size14,Text='Choose The Trait',TextColor3=Color3.new(1, 1, 1),TextScaled=false,TextSize=14,TextStrokeColor3=Color3.new(0, 0, 0),TextStrokeTransparency=1,TextTransparency=0,TextWrapped=false,TextXAlignment=Enum.TextXAlignment.Center,TextYAlignment=Enum.TextYAlignment.Center,Active=false,AnchorPoint=Vector2.new(0.5, 0.5),BackgroundColor3=Color3.new(1, 1, 1),BackgroundTransparency=1,BorderColor3=Color3.new(0.105882, 0.164706, 0.207843),BorderSizePixel=0,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.529033363, 0, 0.0141676292, 0),Rotation=0,Selectable=false,Size=UDim2.new(0, 66, 0, 15),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='TextLabel',Parent = Menu})
        local Legendary = CreateInstance('TextButton',{Font=Enum.Font.SourceSans,FontSize=Enum.FontSize.Size18,Text='Legendary',TextColor3=Color3.new(1, 1, 1),TextScaled=false,TextSize=18,TextStrokeColor3=Color3.new(0, 0, 0),TextStrokeTransparency=1,TextTransparency=0,TextWrapped=true,TextXAlignment=Enum.TextXAlignment.Center,TextYAlignment=Enum.TextYAlignment.Center,AutoButtonColor=true,Modal=false,Selected=false,Style=Enum.ButtonStyle.Custom,Active=true,AnchorPoint=Vector2.new(0, 0),BackgroundColor3=Color3.new(0.117647, 0.117647, 0.117647),BackgroundTransparency=0,BorderColor3=Color3.new(0.105882, 0.164706, 0.207843),BorderSizePixel=0,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.0436052009, 0, 0.84034723, 0),Rotation=0,Selectable=true,Size=UDim2.new(0, 120, 0, 23),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='Legendary',Parent = Menu})
        local Balanced = CreateInstance('TextButton',{Font=Enum.Font.SourceSans,FontSize=Enum.FontSize.Size18,Text='Balanced',TextColor3=Color3.new(1, 1, 1),TextScaled=false,TextSize=18,TextStrokeColor3=Color3.new(0, 0, 0),TextStrokeTransparency=1,TextTransparency=0,TextWrapped=true,TextXAlignment=Enum.TextXAlignment.Center,TextYAlignment=Enum.TextYAlignment.Center,AutoButtonColor=true,Modal=false,Selected=false,Style=Enum.ButtonStyle.Custom,Active=true,AnchorPoint=Vector2.new(0, 0),BackgroundColor3=Color3.new(0.117647, 0.117647, 0.117647),BackgroundTransparency=0,BorderColor3=Color3.new(0.105882, 0.164706, 0.207843),BorderSizePixel=0,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.0440356024, 0, 0.185744151, 0),Rotation=0,Selectable=true,Size=UDim2.new(0, 120, 0, 23),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='Balanced',Parent = Menu})
        local Hypersonic = CreateInstance('TextButton',{Font=Enum.Font.SourceSans,FontSize=Enum.FontSize.Size18,Text='Hypersonic',TextColor3=Color3.new(1, 1, 1),TextScaled=false,TextSize=18,TextStrokeColor3=Color3.new(0, 0, 0),TextStrokeTransparency=1,TextTransparency=0,TextWrapped=true,TextXAlignment=Enum.TextXAlignment.Center,TextYAlignment=Enum.TextYAlignment.Center,AutoButtonColor=true,Modal=false,Selected=false,Style=Enum.ButtonStyle.Custom,Active=true,AnchorPoint=Vector2.new(0, 0),BackgroundColor3=Color3.new(0.117647, 0.117647, 0.117647),BackgroundTransparency=0,BorderColor3=Color3.new(0.105882, 0.164706, 0.207843),BorderSizePixel=0,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.0468386933, 0, 0.655726671, 0),Rotation=0,Selectable=true,Size=UDim2.new(0, 120, 0, 23),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='Hypersonic',Parent = Menu})
        local Elegant = CreateInstance('TextButton',{Font=Enum.Font.SourceSans,FontSize=Enum.FontSize.Size18,Text='Elegant',TextColor3=Color3.new(1, 1, 1),TextScaled=false,TextSize=18,TextStrokeColor3=Color3.new(0, 0, 0),TextStrokeTransparency=1,TextTransparency=0,TextWrapped=true,TextXAlignment=Enum.TextXAlignment.Center,TextYAlignment=Enum.TextYAlignment.Center,AutoButtonColor=true,Modal=false,Selected=false,Style=Enum.ButtonStyle.Custom,Active=true,AnchorPoint=Vector2.new(0, 0),BackgroundColor3=Color3.new(0.117647, 0.117647, 0.117647),BackgroundTransparency=0,BorderColor3=Color3.new(0.105882, 0.164706, 0.207843),BorderSizePixel=0,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.0468386933, 0, 0.372769535, 0),Rotation=0,Selectable=true,Size=UDim2.new(0, 120, 0, 23),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='Elegant',Parent = Menu})
        local anyone = CreateInstance('TextButton',{Font=Enum.Font.SourceSans,FontSize=Enum.FontSize.Size18,Text='Get Anyone',TextColor3=Color3.new(1, 1, 1),TextScaled=false,TextSize=18,TextStrokeColor3=Color3.new(0, 0, 0),TextStrokeTransparency=1,TextTransparency=0,TextWrapped=true,TextXAlignment=Enum.TextXAlignment.Center,TextYAlignment=Enum.TextYAlignment.Center,AutoButtonColor=true,Modal=false,Selected=false,Style=Enum.ButtonStyle.Custom,Active=true,AnchorPoint=Vector2.new(0, 0),BackgroundColor3=Color3.new(0.117647, 0.117647, 0.117647),BackgroundTransparency=0,BorderColor3=Color3.new(0.105882, 0.164706, 0.207843),BorderSizePixel=0,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.278482795, 0, 0.951865673, 0),Rotation=0,Selectable=true,Size=UDim2.new(0, 121, 0, 23),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='anyone',Parent = Menu})
        local btnExecute = CreateInstance('TextButton',{Font=Enum.Font.SourceSansBold,FontSize=Enum.FontSize.Size14,Text='Execute',TextColor3=Color3.new(1, 1, 1),TextScaled=true,TextSize=14,TextStrokeColor3=Color3.new(0, 0, 0),TextStrokeTransparency=1,TextTransparency=0,TextWrapped=true,TextXAlignment=Enum.TextXAlignment.Center,TextYAlignment=Enum.TextYAlignment.Center,AutoButtonColor=true,Modal=false,Selected=false,Style=Enum.ButtonStyle.Custom,Active=true,AnchorPoint=Vector2.new(0.5, 0.5),BackgroundColor3=Color3.new(0.117647, 0.117647, 0.117647),BackgroundTransparency=0,BorderColor3=Color3.new(0.105882, 0.164706, 0.207843),BorderSizePixel=0,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.712359965, 0, 0.889843464, 0),Rotation=0,Selectable=true,Size=UDim2.new(0, 333, 0, 33),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='btnExecute',Parent = c9})
        --storage
        local StorageGui = CreateInstance('ScreenGui',{DisplayOrder=0,Enabled=true,ResetOnSpawn=true,Name='StorageGui', Parent=game.CoreGui})
        local backstor = CreateInstance('Frame',{Style=Enum.FrameStyle.RobloxRound,Active=true,AnchorPoint=Vector2.new(0.5, 0.5),BackgroundColor3=Color3.new(0.156863, 0.156863, 0.156863),BackgroundTransparency=0,BorderColor3=Color3.new(0.105882, 0.164706, 0.207843),BorderSizePixel=0,ClipsDescendants=true,Draggable=true,Position=UDim2.new(0.576, -79,0.552, -5),Rotation=0,Selectable=false,Size=UDim2.new(0, 290, 0, 335),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=false,ZIndex=1,Name = 'backstor',Parent = StorageGui})
        local barstor = CreateInstance('Frame',{Style=Enum.FrameStyle.RobloxRound,Active=true,AnchorPoint=Vector2.new(0.5, 0.5),BackgroundColor3=Color3.new(0.117647, 0.117647, 0.117647),BackgroundTransparency=0,BorderColor3=Color3.new(0.105882, 0.164706, 0.207843),BorderSizePixel=1,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.494731188, 0, 0.0150513388, 0),Rotation=0,Selectable=false,Size=UDim2.new(0, 291, 0, 24),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name = 'barstor',Parent = backstor})
        local namestore = CreateInstance('TextLabel',{Font=Enum.Font.GothamSemibold,FontSize=Enum.FontSize.Size14,Text='Choose Storage',TextColor3=Color3.new(1, 1, 1),TextScaled=false,TextSize=14,TextStrokeColor3=Color3.new(0, 0, 0),TextStrokeTransparency=1,TextTransparency=0,TextWrapped=false,TextXAlignment=Enum.TextXAlignment.Center,TextYAlignment=Enum.TextYAlignment.Center,Active=false,AnchorPoint=Vector2.new(0.5, 0.5),BackgroundColor3=Color3.new(1, 1, 1),BackgroundTransparency=1,BorderColor3=Color3.new(0.105882, 0.164706, 0.207843),BorderSizePixel=0,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.497999996, 0, 0.5, 0),Rotation=0,Selectable=false,Size=UDim2.new(0, 112, 0, 15),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='namestore',Parent = barstor})
        local closestor = CreateInstance('ImageButton',{Image='rbxassetid://3494886164',ImageColor3=Color3.new(1, 1, 1),ImageRectOffset=Vector2.new(0, 0),ImageRectSize=Vector2.new(0, 0),ImageTransparency=0,ScaleType=Enum.ScaleType.Stretch,SliceCenter=Rect.new(0, 0, 0, 0),AutoButtonColor=true,Modal=false,Selected=false,Style=Enum.ButtonStyle.Custom,Active=true,AnchorPoint=Vector2.new(0.5, 0.5),BackgroundColor3=Color3.new(0.117647, 0.117647, 0.117647),BackgroundTransparency=1,BorderColor3=Color3.new(0.105882, 0.164706, 0.207843),BorderSizePixel=0,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.97882539, 0, 0.458333343, 0),Rotation=0,Selectable=true,Size=UDim2.new(0, 25, 0, 22),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='closestor',Parent = barstor})
        local nextstor = CreateInstance('ImageButton',{Image='rbxassetid://932030878',ImageColor3=Color3.new(1, 1, 1),ImageRectOffset=Vector2.new(0, 0),ImageRectSize=Vector2.new(0, 0),ImageTransparency=0,ScaleType=Enum.ScaleType.Stretch,SliceCenter=Rect.new(0, 0, 0, 0),AutoButtonColor=true,Modal=false,Selected=false,Style=Enum.ButtonStyle.Custom,Active=true,AnchorPoint=Vector2.new(0.5, 0.5),BackgroundColor3=Color3.new(0.117647, 0.117647, 0.117647),BackgroundTransparency=1,BorderColor3=Color3.new(0.105882, 0.164706, 0.207843),BorderSizePixel=0,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.0189999994, 0, 0.430999994, 0),Rotation=0,Selectable=true,Size=UDim2.new(0, 25, 0, 21),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='nextstor',Parent = barstor})
        local backstore = CreateInstance('ImageButton',{Image='rbxassetid://932436179',ImageColor3=Color3.new(1, 1, 1),ImageRectOffset=Vector2.new(0, 0),ImageRectSize=Vector2.new(0, 0),ImageTransparency=0,ScaleType=Enum.ScaleType.Stretch,SliceCenter=Rect.new(0, 0, 0, 0),AutoButtonColor=true,Modal=false,Selected=false,Style=Enum.ButtonStyle.Custom,Active=true,AnchorPoint=Vector2.new(0.5, 0.5),BackgroundColor3=Color3.new(0.117647, 0.117647, 0.117647),BackgroundTransparency=1,BorderColor3=Color3.new(0.105882, 0.164706, 0.207843),BorderSizePixel=0,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.018991556, 0, 0.430555999, 0),Rotation=0,Selectable=true,Size=UDim2.new(0, 25, 0, 21),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=false,ZIndex=1,Name='backstore',Parent = barstor})
        local btngetstorage = CreateInstance('TextButton',{Font=Enum.Font.GothamSemibold,FontSize=Enum.FontSize.Size18,Text='Execute',TextColor3=Color3.new(1, 1, 1),TextScaled=false,TextSize=16,TextStrokeColor3=Color3.new(0, 0, 0),TextStrokeTransparency=1,TextTransparency=0,TextWrapped=true,TextXAlignment=Enum.TextXAlignment.Center,TextYAlignment=Enum.TextYAlignment.Center,AutoButtonColor=true,Modal=false,Selected=false,Style=Enum.ButtonStyle.Custom,Active=true,AnchorPoint=Vector2.new(0, 0),BackgroundColor3=Color3.new(0.376471, 0.792157, 0.313726),BackgroundTransparency=0,BorderColor3=Color3.new(0.105882, 0.164706, 0.207843),BorderSizePixel=0,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.377000004, 0, 0.939999998, 0),Rotation=0,Selectable=true,Size=UDim2.new(0, 71, 0, 23),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='btngetstorage',Parent = backstor})
        local p1 = CreateInstance('Frame',{Style=Enum.FrameStyle.Custom,Active=false,AnchorPoint=Vector2.new(0, 0),BackgroundColor3=Color3.new(1, 1, 1),BackgroundTransparency=1,BorderColor3=Color3.new(0.105882, 0.164706, 0.207843),BorderSizePixel=1,ClipsDescendants=false,Draggable=false,Position=UDim2.new(-0.0611096621, 0, 0.0608196221, 0),Rotation=0,Selectable=false,Size=UDim2.new(0, 302, 0, 276),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name = 'p1',Parent = backstor})
        local slot1 = CreateInstance('TextButton',{Font=Enum.Font.Fantasy,FontSize=Enum.FontSize.Size24,Text='None',TextColor3=Color3.new(1, 1, 1),TextScaled=false,TextSize=21,TextStrokeColor3=Color3.new(0, 0, 0),TextStrokeTransparency=1,TextTransparency=0,TextWrapped=true,TextXAlignment=Enum.TextXAlignment.Left,TextYAlignment=Enum.TextYAlignment.Center,AutoButtonColor=true,Modal=false,Selected=false,Style=Enum.ButtonStyle.Custom,Active=true,AnchorPoint=Vector2.new(0, 0),BackgroundColor3=Color3.new(0, 0, 0),BackgroundTransparency=0.5,BorderColor3=Color3.new(0.239216, 0.670588, 1),BorderSizePixel=2,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.366817623, 0, 0.059760984, 0),Rotation=0,Selectable=true,Size=UDim2.new(0, 80, 0, 80),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='slot1',Parent = p1})
        local slot2 = CreateInstance('TextButton',{Font=Enum.Font.Fantasy,FontSize=Enum.FontSize.Size24,Text='None',TextColor3=Color3.new(1, 1, 1),TextScaled=false,TextSize=21,TextStrokeColor3=Color3.new(0, 0, 0),TextStrokeTransparency=1,TextTransparency=0,TextWrapped=true,TextXAlignment=Enum.TextXAlignment.Left,TextYAlignment=Enum.TextYAlignment.Center,AutoButtonColor=true,Modal=false,Selected=false,Style=Enum.ButtonStyle.Custom,Active=true,AnchorPoint=Vector2.new(0, 0),BackgroundColor3=Color3.new(0, 0, 0),BackgroundTransparency=0.5,BorderColor3=Color3.new(0.239216, 0.670588, 1),BorderSizePixel=2,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.681799471, 0, 0.059760984, 0),Rotation=0,Selectable=true,Size=UDim2.new(0, 80, 0, 80),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='slot2',Parent = p1})
        local slot3 = CreateInstance('TextButton',{Font=Enum.Font.Fantasy,FontSize=Enum.FontSize.Size24,Text='None',TextColor3=Color3.new(1, 1, 1),TextScaled=false,TextSize=21,TextStrokeColor3=Color3.new(0, 0, 0),TextStrokeTransparency=1,TextTransparency=0,TextWrapped=true,TextXAlignment=Enum.TextXAlignment.Left,TextYAlignment=Enum.TextYAlignment.Center,AutoButtonColor=true,Modal=false,Selected=false,Style=Enum.ButtonStyle.Custom,Active=true,AnchorPoint=Vector2.new(0, 0),BackgroundColor3=Color3.new(0, 0, 0),BackgroundTransparency=0.5,BorderColor3=Color3.new(0.239216, 0.670588, 1),BorderSizePixel=2,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.0567995012, 0, 0.059760984, 0),Rotation=0,Selectable=true,Size=UDim2.new(0, 80, 0, 80),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='slot3',Parent = p1})
        local slot4 = CreateInstance('TextButton',{Font=Enum.Font.Fantasy,FontSize=Enum.FontSize.Size24,Text='None',TextColor3=Color3.new(1, 1, 1),TextScaled=false,TextSize=21,TextStrokeColor3=Color3.new(0, 0, 0),TextStrokeTransparency=1,TextTransparency=0,TextWrapped=true,TextXAlignment=Enum.TextXAlignment.Left,TextYAlignment=Enum.TextYAlignment.Center,AutoButtonColor=true,Modal=false,Selected=false,Style=Enum.ButtonStyle.Custom,Active=true,AnchorPoint=Vector2.new(0, 0),BackgroundColor3=Color3.new(0, 0, 0),BackgroundTransparency=0.5,BorderColor3=Color3.new(0.239216, 0.670588, 1),BorderSizePixel=2,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.366817623, 0, 0.359761, 0),Rotation=0,Selectable=true,Size=UDim2.new(0, 80, 0, 80),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='slot4',Parent = p1})
        local slot5 = CreateInstance('TextButton',{Font=Enum.Font.Fantasy,FontSize=Enum.FontSize.Size24,Text='None',TextColor3=Color3.new(1, 1, 1),TextScaled=false,TextSize=21,TextStrokeColor3=Color3.new(0, 0, 0),TextStrokeTransparency=1,TextTransparency=0,TextWrapped=true,TextXAlignment=Enum.TextXAlignment.Left,TextYAlignment=Enum.TextYAlignment.Center,AutoButtonColor=true,Modal=false,Selected=false,Style=Enum.ButtonStyle.Custom,Active=true,AnchorPoint=Vector2.new(0, 0),BackgroundColor3=Color3.new(0, 0, 0),BackgroundTransparency=0.5,BorderColor3=Color3.new(0.239216, 0.670588, 1),BorderSizePixel=2,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.681799471, 0, 0.359761, 0),Rotation=0,Selectable=true,Size=UDim2.new(0, 80, 0, 80),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='slot5',Parent = p1})
        local slot6 = CreateInstance('TextButton',{Font=Enum.Font.Fantasy,FontSize=Enum.FontSize.Size24,Text='None',TextColor3=Color3.new(1, 1, 1),TextScaled=false,TextSize=21,TextStrokeColor3=Color3.new(0, 0, 0),TextStrokeTransparency=1,TextTransparency=0,TextWrapped=true,TextXAlignment=Enum.TextXAlignment.Left,TextYAlignment=Enum.TextYAlignment.Center,AutoButtonColor=true,Modal=false,Selected=false,Style=Enum.ButtonStyle.Custom,Active=true,AnchorPoint=Vector2.new(0, 0),BackgroundColor3=Color3.new(0, 0, 0),BackgroundTransparency=0.5,BorderColor3=Color3.new(0.239216, 0.670588, 1),BorderSizePixel=2,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.0567995012, 0, 0.359761, 0),Rotation=0,Selectable=true,Size=UDim2.new(0, 80, 0, 80),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='slot6',Parent = p1})
        local slot7 = CreateInstance('TextButton',{Font=Enum.Font.Fantasy,FontSize=Enum.FontSize.Size24,Text='None',TextColor3=Color3.new(1, 1, 1),TextScaled=false,TextSize=21,TextStrokeColor3=Color3.new(0, 0, 0),TextStrokeTransparency=1,TextTransparency=0,TextWrapped=true,TextXAlignment=Enum.TextXAlignment.Left,TextYAlignment=Enum.TextYAlignment.Center,AutoButtonColor=true,Modal=false,Selected=false,Style=Enum.ButtonStyle.Custom,Active=true,AnchorPoint=Vector2.new(0, 0),BackgroundColor3=Color3.new(0, 0, 0),BackgroundTransparency=0.5,BorderColor3=Color3.new(0.239216, 0.670588, 1),BorderSizePixel=2,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.366817623, 0, 0.659761012, 0),Rotation=0,Selectable=true,Size=UDim2.new(0, 80, 0, 80),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='slot7',Parent = p1})
        local slot8 = CreateInstance('TextButton',{Font=Enum.Font.Fantasy,FontSize=Enum.FontSize.Size24,Text='None',TextColor3=Color3.new(1, 1, 1),TextScaled=false,TextSize=21,TextStrokeColor3=Color3.new(0, 0, 0),TextStrokeTransparency=1,TextTransparency=0,TextWrapped=true,TextXAlignment=Enum.TextXAlignment.Left,TextYAlignment=Enum.TextYAlignment.Center,AutoButtonColor=true,Modal=false,Selected=false,Style=Enum.ButtonStyle.Custom,Active=true,AnchorPoint=Vector2.new(0, 0),BackgroundColor3=Color3.new(0, 0, 0),BackgroundTransparency=0.5,BorderColor3=Color3.new(0.239216, 0.670588, 1),BorderSizePixel=2,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.0567995012, 0, 0.659761012, 0),Rotation=0,Selectable=true,Size=UDim2.new(0, 80, 0, 80),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='slot8',Parent = p1})
        local slot9 = CreateInstance('TextButton',{Font=Enum.Font.Fantasy,FontSize=Enum.FontSize.Size24,Text='None',TextColor3=Color3.new(1, 1, 1),TextScaled=false,TextSize=21,TextStrokeColor3=Color3.new(0, 0, 0),TextStrokeTransparency=1,TextTransparency=0,TextWrapped=true,TextXAlignment=Enum.TextXAlignment.Left,TextYAlignment=Enum.TextYAlignment.Center,AutoButtonColor=true,Modal=false,Selected=false,Style=Enum.ButtonStyle.Custom,Active=true,AnchorPoint=Vector2.new(0, 0),BackgroundColor3=Color3.new(0, 0, 0),BackgroundTransparency=0.5,BorderColor3=Color3.new(0.239216, 0.670588, 1),BorderSizePixel=2,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.681799471, 0, 0.659761012, 0),Rotation=0,Selectable=true,Size=UDim2.new(0, 80, 0, 80),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='slot9',Parent = p1})
        local p2 = CreateInstance('Frame',{Style=Enum.FrameStyle.Custom,Active=false,AnchorPoint=Vector2.new(0, 0),BackgroundColor3=Color3.new(1, 1, 1),BackgroundTransparency=1,BorderColor3=Color3.new(0.105882, 0.164706, 0.207843),BorderSizePixel=1,ClipsDescendants=false,Draggable=false,Position=UDim2.new(-0.0611096621, 0, 0.0608196221, 0),Rotation=0,Selectable=false,Size=UDim2.new(0, 302, 0, 276),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=false,ZIndex=1,Name = 'p2',Parent = backstor})
        local slot10 = CreateInstance('TextButton',{Font=Enum.Font.Fantasy,FontSize=Enum.FontSize.Size24,Text='None',TextColor3=Color3.new(1, 1, 1),TextScaled=false,TextSize=21,TextStrokeColor3=Color3.new(0, 0, 0),TextStrokeTransparency=1,TextTransparency=0,TextWrapped=true,TextXAlignment=Enum.TextXAlignment.Left,TextYAlignment=Enum.TextYAlignment.Center,AutoButtonColor=true,Modal=false,Selected=false,Style=Enum.ButtonStyle.Custom,Active=true,AnchorPoint=Vector2.new(0, 0),BackgroundColor3=Color3.new(0, 0, 0),BackgroundTransparency=0.5,BorderColor3=Color3.new(0.239216, 0.670588, 1),BorderSizePixel=2,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.366817623, 0, 0.059760984, 0),Rotation=0,Selectable=true,Size=UDim2.new(0, 80, 0, 80),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='slot10',Parent = p2})
        local slot11 = CreateInstance('TextButton',{Font=Enum.Font.Fantasy,FontSize=Enum.FontSize.Size24,Text='None',TextColor3=Color3.new(1, 1, 1),TextScaled=false,TextSize=21,TextStrokeColor3=Color3.new(0, 0, 0),TextStrokeTransparency=1,TextTransparency=0,TextWrapped=true,TextXAlignment=Enum.TextXAlignment.Left,TextYAlignment=Enum.TextYAlignment.Center,AutoButtonColor=true,Modal=false,Selected=false,Style=Enum.ButtonStyle.Custom,Active=true,AnchorPoint=Vector2.new(0, 0),BackgroundColor3=Color3.new(0, 0, 0),BackgroundTransparency=0.5,BorderColor3=Color3.new(0.239216, 0.670588, 1),BorderSizePixel=2,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.681799471, 0, 0.059760984, 0),Rotation=0,Selectable=true,Size=UDim2.new(0, 80, 0, 80),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='slot11',Parent = p2})
        local slot12 = CreateInstance('TextButton',{Font=Enum.Font.Fantasy,FontSize=Enum.FontSize.Size24,Text='None',TextColor3=Color3.new(1, 1, 1),TextScaled=false,TextSize=21,TextStrokeColor3=Color3.new(0, 0, 0),TextStrokeTransparency=1,TextTransparency=0,TextWrapped=true,TextXAlignment=Enum.TextXAlignment.Left,TextYAlignment=Enum.TextYAlignment.Center,AutoButtonColor=true,Modal=false,Selected=false,Style=Enum.ButtonStyle.Custom,Active=true,AnchorPoint=Vector2.new(0, 0),BackgroundColor3=Color3.new(0, 0, 0),BackgroundTransparency=0.5,BorderColor3=Color3.new(0.239216, 0.670588, 1),BorderSizePixel=2,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.0567995012, 0, 0.059760984, 0),Rotation=0,Selectable=true,Size=UDim2.new(0, 80, 0, 80),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='slot12',Parent = p2})
        local slot13 = CreateInstance('TextButton',{Font=Enum.Font.Fantasy,FontSize=Enum.FontSize.Size24,Text='None',TextColor3=Color3.new(1, 1, 1),TextScaled=false,TextSize=21,TextStrokeColor3=Color3.new(0, 0, 0),TextStrokeTransparency=1,TextTransparency=0,TextWrapped=true,TextXAlignment=Enum.TextXAlignment.Left,TextYAlignment=Enum.TextYAlignment.Center,AutoButtonColor=true,Modal=false,Selected=false,Style=Enum.ButtonStyle.Custom,Active=true,AnchorPoint=Vector2.new(0, 0),BackgroundColor3=Color3.new(0, 0, 0),BackgroundTransparency=0.5,BorderColor3=Color3.new(0.239216, 0.670588, 1),BorderSizePixel=2,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.366817623, 0, 0.359761, 0),Rotation=0,Selectable=true,Size=UDim2.new(0, 80, 0, 80),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='slot13',Parent = p2})
        local slot14 = CreateInstance('TextButton',{Font=Enum.Font.Fantasy,FontSize=Enum.FontSize.Size24,Text='None',TextColor3=Color3.new(1, 1, 1),TextScaled=false,TextSize=21,TextStrokeColor3=Color3.new(0, 0, 0),TextStrokeTransparency=1,TextTransparency=0,TextWrapped=true,TextXAlignment=Enum.TextXAlignment.Left,TextYAlignment=Enum.TextYAlignment.Center,AutoButtonColor=true,Modal=false,Selected=false,Style=Enum.ButtonStyle.Custom,Active=true,AnchorPoint=Vector2.new(0, 0),BackgroundColor3=Color3.new(0, 0, 0),BackgroundTransparency=0.5,BorderColor3=Color3.new(0.239216, 0.670588, 1),BorderSizePixel=2,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.681799471, 0, 0.359761, 0),Rotation=0,Selectable=true,Size=UDim2.new(0, 80, 0, 80),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='slot14',Parent = p2})
        local slot16 = CreateInstance('TextButton',{Font=Enum.Font.Fantasy,FontSize=Enum.FontSize.Size24,Text='None',TextColor3=Color3.new(1, 1, 1),TextScaled=false,TextSize=21,TextStrokeColor3=Color3.new(0, 0, 0),TextStrokeTransparency=1,TextTransparency=0,TextWrapped=true,TextXAlignment=Enum.TextXAlignment.Left,TextYAlignment=Enum.TextYAlignment.Center,AutoButtonColor=true,Modal=false,Selected=false,Style=Enum.ButtonStyle.Custom,Active=true,AnchorPoint=Vector2.new(0, 0),BackgroundColor3=Color3.new(0, 0, 0),BackgroundTransparency=0.5,BorderColor3=Color3.new(0.239216, 0.670588, 1),BorderSizePixel=2,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.366817623, 0, 0.659761012, 0),Rotation=0,Selectable=true,Size=UDim2.new(0, 80, 0, 80),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='slot16',Parent = p2})
        local slot17 = CreateInstance('TextButton',{Font=Enum.Font.Fantasy,FontSize=Enum.FontSize.Size24,Text='None',TextColor3=Color3.new(1, 1, 1),TextScaled=false,TextSize=21,TextStrokeColor3=Color3.new(0, 0, 0),TextStrokeTransparency=1,TextTransparency=0,TextWrapped=true,TextXAlignment=Enum.TextXAlignment.Left,TextYAlignment=Enum.TextYAlignment.Center,AutoButtonColor=true,Modal=false,Selected=false,Style=Enum.ButtonStyle.Custom,Active=true,AnchorPoint=Vector2.new(0, 0),BackgroundColor3=Color3.new(0, 0, 0),BackgroundTransparency=0.5,BorderColor3=Color3.new(0.239216, 0.670588, 1),BorderSizePixel=2,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.0567995012, 0, 0.659761012, 0),Rotation=0,Selectable=true,Size=UDim2.new(0, 80, 0, 80),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='slot17',Parent = p2})
        local slot18 = CreateInstance('TextButton',{Font=Enum.Font.Fantasy,FontSize=Enum.FontSize.Size24,Text='None',TextColor3=Color3.new(1, 1, 1),TextScaled=false,TextSize=21,TextStrokeColor3=Color3.new(0, 0, 0),TextStrokeTransparency=1,TextTransparency=0,TextWrapped=true,TextXAlignment=Enum.TextXAlignment.Left,TextYAlignment=Enum.TextYAlignment.Center,AutoButtonColor=true,Modal=false,Selected=false,Style=Enum.ButtonStyle.Custom,Active=true,AnchorPoint=Vector2.new(0, 0),BackgroundColor3=Color3.new(0, 0, 0),BackgroundTransparency=0.5,BorderColor3=Color3.new(0.239216, 0.670588, 1),BorderSizePixel=2,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.681799471, 0, 0.659761012, 0),Rotation=0,Selectable=true,Size=UDim2.new(0, 80, 0, 80),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='slot18',Parent = p2})
        local slot15 = CreateInstance('TextButton',{Font=Enum.Font.Fantasy,FontSize=Enum.FontSize.Size24,Text='None',TextColor3=Color3.new(1, 1, 1),TextScaled=false,TextSize=21,TextStrokeColor3=Color3.new(0, 0, 0),TextStrokeTransparency=1,TextTransparency=0,TextWrapped=true,TextXAlignment=Enum.TextXAlignment.Left,TextYAlignment=Enum.TextYAlignment.Center,AutoButtonColor=true,Modal=false,Selected=false,Style=Enum.ButtonStyle.Custom,Active=true,AnchorPoint=Vector2.new(0, 0),BackgroundColor3=Color3.new(0, 0, 0),BackgroundTransparency=0.5,BorderColor3=Color3.new(0.239216, 0.670588, 1),BorderSizePixel=2,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.0567995012, 0, 0.359761, 0),Rotation=0,Selectable=true,Size=UDim2.new(0, 80, 0, 80),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='slot15',Parent = p2})
        local s =CreateInstance("Sound",{Name='s',SoundId = "http://www.roblox.com/asset/?id=3318726694",Volume = 1.2,Pitch = 1,Looped = false,archivable = false,Parent = game.Workspace})
        worthused = false
        reqused = false
        Enabled = false
        traittg = {}
        target = {}
        slotnumber = 0
        storagestand = false
        lucky = false
        local newcolor = Color3.new(0.117647,0.117647,0.117647)
        local oldcolor = Color3.new(0,1,0.498039)
        local texold = Color3.new(255,255,255)
        local texnew = Color3.new(0,0,0)
        StandsGUI:TweenPosition(UDim2.new(0.498945326, 0, 0.545793176, 0))
        --MainButtons
        closegui.MouseButton1Click:Connect(function()
            StandsGUI:TweenPosition(UDim2.new(2, 0, 0.545793176, 0), 'Out', 'Bounce', 1, true)
        end)
        btnNext.MouseButton1Click:Connect(function()
           c1.Visible=false;c2.Visible=true;btnNext.Visible=false;btnBack.Visible=true
        end)  
        btnBack.MouseButton1Click:Connect(function()
            c1.Visible=true;c2.Visible=false;btnNext.Visible=true;btnBack.Visible=false
         end) 
        closetrait.MouseButton1Click:Connect(function()
            Menu.Visible=false
        end)
        game.Players.LocalPlayer:GetMouse().KeyDown:connect(function(menu)
            if (menu=="x") then
                Enabled = false
                error("Stop")
            end
        end)
        function removebyKey(tab, val)
            for i, v in pairs (tab) do 
                if (v == val) then
                    tab[i] = nil
                end
            end
        end
        closestor.MouseButton1Click:connect(function()
            backstor.Visible=false
        end)
        btngetstorage.MouseButton1Click:connect(function()
            backstor.Visible=false
            Menu.Visible=true
        end)
        nextstor.MouseButton1Click:connect(function()
            p2.Visible=true
            p1.Visible=false
            nextstor.Visible=false
            backstore.Visible=true
            namestore.Text = 'Gamepass Only'
        end)
        backstore.MouseButton1Click:connect(function()
            p2.Visible=false
            p1.Visible=true
            nextstor.Visible=true
            backstore.Visible=false
            namestore.Text = 'Choose Storage'
        end)
        slot1.Text = game.Players.LocalPlayer.storedstand1.Value 
        slot2.Text = game.Players.LocalPlayer.storedstand2.Value
        slot3.Text = game.Players.LocalPlayer.storedstand3.Value
        slot4.Text = game.Players.LocalPlayer.storedstand4.Value
        slot5.Text = game.Players.LocalPlayer.storedstand5.Value
        slot6.Text = game.Players.LocalPlayer.storedstand6.Value
        slot7.Text = game.Players.LocalPlayer.storedstand7.Value
        slot8.Text = game.Players.LocalPlayer.storedstand8.Value
        slot9.Text = game.Players.LocalPlayer.storedstand9.Value
        slot10.Text = game.Players.LocalPlayer.storedstand10.Value 
        slot11.Text = game.Players.LocalPlayer.storedstand11.Value
        slot12.Text = game.Players.LocalPlayer.storedstand12.Value
        slot13.Text = game.Players.LocalPlayer.storedstand13.Value
        slot14.Text = game.Players.LocalPlayer.storedstand14.Value
        slot15.Text = game.Players.LocalPlayer.storedstand15.Value
        slot16.Text = game.Players.LocalPlayer.storedstand16.Value
        slot17.Text = game.Players.LocalPlayer.storedstand17.Value
        slot18.Text = game.Players.LocalPlayer.storedstand18.Value
        slot1.MouseButton1Click:Connect(function()
            slot1.Text = 'Selected!'
            wait(1)
            slot1.Text = game.Players.LocalPlayer.storedstand1.Value
            slotnumber = 1
        end)
        slot2.MouseButton1Click:Connect(function()
            slot2.Text = 'Selected!'
            wait(1)
            slot2.Text = game.Players.LocalPlayer.storedstand2.Value
            slotnumber = 2
        end)
        slot3.MouseButton1Click:Connect(function()
            slot3.Text = 'Selected!'
            wait(1)
            slot3.Text = game.Players.LocalPlayer.storedstand3.Value
            slotnumber = 3
        end)
        slot4.MouseButton1Click:Connect(function()
            slot4.Text = 'Selected!'
            wait(1)
            slot4.Text = game.Players.LocalPlayer.storedstand4.Value
            slotnumber = 4
        end)
        slot5.MouseButton1Click:Connect(function()
            slot5.Text = 'Selected!'
            wait(1)
            slot5.Text = game.Players.LocalPlayer.storedstand5.Value
            slotnumber = 5
        end)
        slot6.MouseButton1Click:Connect(function()
            slot6.Text = 'Selected!'
            wait(1)
            slot6.Text = game.Players.LocalPlayer.storedstand6.Value
            slotnumber = 6
        end)
        slot7.MouseButton1Click:Connect(function()
            slot7.Text = 'Selected!'
            wait(1)
            slot7.Text = game.Players.LocalPlayer.storedstand7.Value
            slotnumber = 7
        end)
        slot8.MouseButton1Click:Connect(function()
            slot8.Text = 'Selected!'
            wait(1)
            slot8.Text = game.Players.LocalPlayer.storedstand8.Value
            slotnumber = 8
        end)
        slot9.MouseButton1Click:Connect(function()
            slot9.Text = 'Selected!'
            wait(1)
            slot9.Text = game.Players.LocalPlayer.storedstand9.Value
            slotnumber = 9
        end)
        slot10.MouseButton1Click:Connect(function()
            slot10.Text = 'Selected!'
            wait(1)
            slot10.Text = game.Players.LocalPlayer.storedstand10.Value
            slotnumber = 10
        end)
        slot11.MouseButton1Click:Connect(function()
            slot11.Text = 'Selected!'
            wait(1)
            slot11.Text = game.Players.LocalPlayer.storedstand11.Value
            slotnumber = 11
        end)
        slot12.MouseButton1Click:Connect(function()
            slot12.Text = 'Selected!'
            wait(1)
            slot1.Text = game.Players.LocalPlayer.storedstand12.Value
            slotnumber = 12
        end)
        slot13.MouseButton1Click:Connect(function()
            slot13.Text = 'Selected!'
            wait(1)
            slot13.Text = game.Players.LocalPlayer.storedstand13.Value
            slotnumber = 13
        end)
        slot14.MouseButton1Click:Connect(function()
            slot14.Text = 'Selected!'
            wait(1)
            slot14.Text = game.Players.LocalPlayer.storedstand14.Value
            slotnumber = 14
        end)
        slot15.MouseButton1Click:Connect(function()
            slot15.Text = 'Selected!'
            wait(1)
            slot15.Text = game.Players.LocalPlayer.storedstand15.Value
            slotnumber = 15
        end)
        slot16.MouseButton1Click:Connect(function()
            slot16.Text = 'Selected!'
            wait(1)
            slot16.Text = game.Players.LocalPlayer.storedstand16.Value
            slotnumber = 16
        end)
        slot17.MouseButton1Click:Connect(function()
            slot17.Text = 'Selected!'
            wait(1)
            slot17.Text = game.Players.LocalPlayer.storedstand17.Value
            slotnumber = 17
        end)
        slot18.MouseButton1Click:Connect(function()
            slot18.Text = 'Selected!'
            wait(1)
            slot18.Text = game.Players.LocalPlayer.storedstand18.Value
            slotnumber = 18
        end)
        Agile.MouseButton1Click:Connect(function()
            if Agile.BackgroundColor3 == newcolor then
                Agile.BackgroundColor3 = oldcolor
                Agile.TextColor3 = texnew
                table.insert(traittg, "Agile")
            else if Agile.BackgroundColor3 == oldcolor then
                    Agile.BackgroundColor3 = newcolor
                    Agile.TextColor3 = texold
                    removebyKey(traittg, "Agile")	
                end
            end
        end)
        Balanced.MouseButton1Click:Connect(function()
            if Balanced.BackgroundColor3 == newcolor then
                Balanced.BackgroundColor3 = oldcolor
                Balanced.TextColor3 = texnew
                table.insert(traittg, "Balanced")
            else if Balanced.BackgroundColor3 == oldcolor then
                    Balanced.BackgroundColor3 = newcolor
                    Balanced.TextColor3 = texold
                    removebyKey(traittg, "Balanced")	
                end
            end
        end)
        Brute.MouseButton1Click:Connect(function()
            if Brute.BackgroundColor3 == newcolor then
                Brute.BackgroundColor3 = oldcolor
                Brute.TextColor3 = texnew
                table.insert(traittg, "Brute")
            else if Brute.BackgroundColor3 == oldcolor then
                    Brute.BackgroundColor3 = newcolor
                    Brute.TextColor3 = texold
                    removebyKey(traittg, "Brute")	
                end
            end
        end)
        Elegant.MouseButton1Click:Connect(function()
            if Elegant.BackgroundColor3 == newcolor then
                Elegant.BackgroundColor3 = oldcolor
                Elegant.TextColor3 = texnew
                table.insert(traittg, "Elegant")
            else if Elegant.BackgroundColor3 == oldcolor then
                    Elegant.BackgroundColor3 = newcolor
                    Elegant.TextColor3 = texold
                    removebyKey(traittg, "Elegant")	
                end
            end
        end)
        Godly.MouseButton1Click:Connect(function()
            if Godly.BackgroundColor3 == newcolor then
                Godly.BackgroundColor3 = oldcolor
                Godly.TextColor3 = texnew
                table.insert(traittg, "Godly")
            else if Godly.BackgroundColor3 == oldcolor then
                    Godly.BackgroundColor3 = newcolor
                    Godly.TextColor3 = texold
                    removebyKey(traittg, "Godly")	
                end
            end
        end)
        Humble.MouseButton1Click:Connect(function()
            if Humble.BackgroundColor3 == newcolor then
                Humble.BackgroundColor3 = oldcolor
                Humble.TextColor3 = texnew
                table.insert(traittg, "Humble")
            else if Humble.BackgroundColor3 == oldcolor then
                    Humble.BackgroundColor3 = newcolor
                    Humble.TextColor3 = texold
                    removebyKey(traittg, "Humble")	
                end
            end
        end)
        Hypersonic.MouseButton1Click:Connect(function()
            if Hypersonic.BackgroundColor3 == newcolor then
                Hypersonic.BackgroundColor3 = oldcolor
                Hypersonic.TextColor3 = texnew
                table.insert(traittg, "Hypersonic")
            else if Hypersonic.BackgroundColor3 == oldcolor then
                    Hypersonic.BackgroundColor3 = newcolor
                    Hypersonic.TextColor3 = texold
                    removebyKey(traittg, "Hypersonic")	
                end
            end
        end)
        Indestructible.MouseButton1Click:Connect(function()
            if Indestructible.BackgroundColor3 == newcolor then
                Indestructible.BackgroundColor3 = oldcolor
                Indestructible.TextColor3 = texnew
                table.insert(traittg, "Indestructible")
            else if Indestructible.BackgroundColor3 == oldcolor then
                    Indestructible.BackgroundColor3 = newcolor
                    Indestructible.TextColor3 = texold
                    removebyKey(traittg, "Indestructible")	
                end
            end
        end)
        Legendary.MouseButton1Click:Connect(function()
            if Legendary.BackgroundColor3 == newcolor then
                Legendary.BackgroundColor3 = oldcolor
                Legendary.TextColor3 = texnew
                table.insert(traittg, "Legendary")
            else if Legendary.BackgroundColor3 == oldcolor then
                    Legendary.BackgroundColor3 = newcolor
                    Legendary.TextColor3 = texold
                    removebyKey(traittg, "Legendary")	
                end
            end
        end)
        Mighty.MouseButton1Click:Connect(function()
            if Mighty.BackgroundColor3 == newcolor then
                Mighty.BackgroundColor3 = oldcolor
                Mighty.TextColor3 = texnew
                table.insert(traittg, "Mighty")
            else if Mighty.BackgroundColor3 == oldcolor then
                    Mighty.BackgroundColor3 = newcolor
                    Mighty.TextColor3 = texold
                    removebyKey(traittg, "Mighty")	
                end
            end
        end)
        Powerhouse.MouseButton1Click:Connect(function()
            if Powerhouse.BackgroundColor3 == newcolor then
                Powerhouse.BackgroundColor3 = oldcolor
                Powerhouse.TextColor3 = texnew
                table.insert(traittg, "Powerhouse")
            else if Powerhouse.BackgroundColor3 == oldcolor then
                    Powerhouse.BackgroundColor3 = newcolor
                    Powerhouse.TextColor3 = texold
                    removebyKey(traittg, "Powerhouse")	
                end
            end
        end)
        Quick.MouseButton1Click:Connect(function()
            if Quick.BackgroundColor3 == newcolor then
                Quick.BackgroundColor3 = oldcolor
                Quick.TextColor3 = texnew
                table.insert(traittg, "Quick")
            else if Quick.BackgroundColor3 == oldcolor then
                    Quick.BackgroundColor3 = newcolor
                    Quick.TextColor3 = texold
                    removebyKey(traittg, "Quick")	
                end
            end
        end)
        Resilient.MouseButton1Click:Connect(function()
            if Resilient.BackgroundColor3 == newcolor then
                Resilient.BackgroundColor3 = oldcolor
                Resilient.TextColor3 = texnew
                table.insert(traittg, "Resilient")
            else if Resilient.BackgroundColor3 == oldcolor then
                    Resilient.BackgroundColor3 = newcolor
                    Resilient.TextColor3 = texold
                    removebyKey(traittg, "Resilient")	
                end
            end
        end)
        Slugger.MouseButton1Click:Connect(function()
            if Slugger.BackgroundColor3 == newcolor then
                Slugger.BackgroundColor3 = oldcolor
                Slugger.TextColor3 = texnew
                table.insert(traittg, "Slugger")
            else if Slugger.BackgroundColor3 == oldcolor then
                    Slugger.BackgroundColor3 = newcolor
                    Slugger.TextColor3 = texold
                    removebyKey(traittg, "Slugger")	
                end
            end
        end)
        Speedy.MouseButton1Click:Connect(function()
            if Speedy.BackgroundColor3 == newcolor then
                Speedy.BackgroundColor3 = oldcolor
                Speedy.TextColor3 = texnew
                table.insert(traittg, "Speedy")
            else if Speedy.BackgroundColor3 == oldcolor then
                    Speedy.BackgroundColor3 = newcolor
                    Speedy.TextColor3 = texold
                    removebyKey(traittg, "Speedy")	
                end
            end
        end)
        Strong.MouseButton1Click:Connect(function()
            if Strong.BackgroundColor3 == newcolor then
                Strong.BackgroundColor3 = oldcolor
                Strong.TextColor3 = texnew
                table.insert(traittg, "Strong")
            else if Strong.BackgroundColor3 == oldcolor then
                    Strong.BackgroundColor3 = newcolor
                    Strong.TextColor3 = texold
                    removebyKey(traittg, "Strong")	
                end
            end
        end)
        Tank.MouseButton1Click:Connect(function()
            if Tank.BackgroundColor3 == newcolor then
                Tank.BackgroundColor3 = oldcolor
                Tank.TextColor3 = texnew
                table.insert(traittg, "Tank")
            else if Tank.BackgroundColor3 == oldcolor then
                    Tank.BackgroundColor3 = newcolor
                    Tank.TextColor3 = texold
                    removebyKey(traittg, "Tank")	
                end
            end
        end)
        Timid.MouseButton1Click:Connect(function()
            if Timid.BackgroundColor3 == newcolor then
                Timid.BackgroundColor3 = oldcolor
                Timid.TextColor3 = texnew
                table.insert(traittg, "Timid")
            else if Timid.BackgroundColor3 == oldcolor then
                    Timid.BackgroundColor3 = newcolor
                    Timid.TextColor3 = texold
                    removebyKey(traittg, "Timid")	
                end
            end
        end)
        anyone.MouseButton1Click:Connect(function()
            if anyone.BackgroundColor3 == newcolor then
                anyone.BackgroundColor3 = oldcolor
                anyone.TextColor3 = texnew
                table.insert(traittg, "Agile")
                table.insert(traittg, "Balanced")
                table.insert(traittg, "Brute")
                table.insert(traittg, "Elegant")
                table.insert(traittg, "Godly")
                table.insert(traittg, "Humble")
                table.insert(traittg, "Hypersonic")
                table.insert(traittg, "Indestructible")
                table.insert(traittg, "Legendary")
                table.insert(traittg, "Mighty")
                table.insert(traittg, "Powerhouse")
                table.insert(traittg, "Quick")
                table.insert(traittg, "Resilient")
                table.insert(traittg, "Slugger")
                table.insert(traittg, "Speedy")
                table.insert(traittg, "Strong")
                table.insert(traittg, "Tank")
                table.insert(traittg, "Timid")
            else if anyone.BackgroundColor3 == oldcolor then
                    anyone.BackgroundColor3 = newcolor
                    anyone.TextColor3 = texold
                    removebyKey(traittg, "Agile")
                    removebyKey(traittg, "Balanced")
                    removebyKey(traittg, "Brute")
                    removebyKey(traittg, "Elegant")
                    removebyKey(traittg, "Godly")
                    removebyKey(traittg, "Humble")
                    removebyKey(traittg, "Hypersonic")
                    removebyKey(traittg, "Indestructible")
                    removebyKey(traittg, "Legendary")
                    removebyKey(traittg, "Mighty")
                    removebyKey(traittg, "Powerhouse")
                    removebyKey(traittg, "Quick")
                    removebyKey(traittg, "Resilient")
                    removebyKey(traittg, "Slugger")
                    removebyKey(traittg, "Speedy")
                    removebyKey(traittg, "Strong")
                    removebyKey(traittg, "Tank")
                    removebyKey(traittg, "Timid")	
                end
            end
        end)
    
    local Novaconfg = {}

    
    function Novaconfg:CreateButton(text,name,par)
            if par == "c1" then
                par = c1
            elseif par == "c2" then
                par = c2
            end
       local TextButton = CreateInstance('TextButton',{Font=Enum.Font.SourceSans,FontSize=Enum.FontSize.Size18,Text=text,TextColor3=Color3.new(1, 1, 1),TextScaled=false,TextSize=18,TextStrokeColor3=Color3.new(0, 0, 0),TextStrokeTransparency=1,TextTransparency=0,TextWrapped=true,TextXAlignment=Enum.TextXAlignment.Center,TextYAlignment=Enum.TextYAlignment.Center,AutoButtonColor=true,Modal=false,Selected=false,Style=Enum.ButtonStyle.Custom,Active=true,AnchorPoint=Vector2.new(0, 0),BackgroundColor3=Color3.new(0.117647, 0.117647, 0.117647),BackgroundTransparency=0,BorderColor3=Color3.new(0.105882, 0.164706, 0.207843),BorderSizePixel=0,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.0130718956, 0, 0.0238805972, 0),Rotation=0,Selectable=true,Size=UDim2.new(0, 150, 0, 25),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='TextButton',Parent = par})
        TextButton.MouseButton1Click:Connect(function()
            if TextButton.BackgroundColor3 == newcolor then
                TextButton.BackgroundColor3 = Color3.new(0.701961, 0.827451, 0.921569)
                TextButton.TextColor3 = texnew
                table.insert(target, name)
                else if TextButton.BackgroundColor3 == Color3.new(0.701961, 0.827451, 0.921569) then
                    TextButton.BackgroundColor3 = newcolor
                    TextButton.TextColor3 = texold
                        removebyKey(target, name)	
                end
            end
        end)
    end
    function Novaconfg:CreateTier(text,color,par)
        if par == "c1" then
            par = c1
        elseif par == "c2" then
            par = c2
        end
        local TierText = CreateInstance('TextLabel',{Font=Enum.Font.GothamSemibold,FontSize=Enum.FontSize.Size14,Text=text,TextColor3=Color3.new(0, 0, 0),TextScaled=false,TextSize=14,TextStrokeColor3=Color3.new(0, 0, 0),TextStrokeTransparency=1,TextTransparency=0,TextWrapped=false,TextXAlignment=Enum.TextXAlignment.Left,TextYAlignment=Enum.TextYAlignment.Center,Active=false,AnchorPoint=Vector2.new(0.5, 0.5),BackgroundColor3=color,BackgroundTransparency=0,BorderColor3=Color3.new(0.105882, 0.164706, 0.207843),BorderSizePixel=0,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.0633471161, 0, 0.0768541992, 0),Rotation=0,Selectable=false,Size=UDim2.new(0, 66, 0, 25),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='TierText',Parent = par})
    end
    function Novaconfg:CreateText(text)
        local TextLabel = CreateInstance('TextLabel',{Font=Enum.Font.GothamSemibold,FontSize=Enum.FontSize.Size14,Text=text,TextColor3=Color3.new(1, 1, 1),TextScaled=false,TextSize=14,TextStrokeColor3=Color3.new(0, 0, 0),TextStrokeTransparency=1,TextTransparency=0,TextWrapped=true,TextXAlignment=Enum.TextXAlignment.Left,TextYAlignment=Enum.TextYAlignment.Center,Active=false,AnchorPoint=Vector2.new(0.5, 0.5),BackgroundColor3=Color3.new(1, 1, 1),BackgroundTransparency=1,BorderColor3=Color3.new(0.105882, 0.164706, 0.207843),BorderSizePixel=0,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.0633471161, 0, 0.0768541992, 0),Rotation=0,Selectable=false,Size=UDim2.new(0, 66, 0, 25),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='TextLabel',Parent = c2})
    end
    function Novaconfg:Createworth()
        local useworth = CreateInstance('ImageButton',{Image='http://www.roblox.com/asset/?id=1974474320',ImageColor3=Color3.new(1, 0.172549, 0.184314),ImageRectOffset=Vector2.new(0, 0),ImageRectSize=Vector2.new(0, 0),ImageTransparency=0,ScaleType=Enum.ScaleType.Crop,SliceCenter=Rect.new(0, 0, 0, 0),AutoButtonColor=true,Modal=false,Selected=false,Style=Enum.ButtonStyle.Custom,Active=true,AnchorPoint=Vector2.new(0.5, 0.5),BackgroundColor3=Color3.new(1, 1, 1),BackgroundTransparency=1,BorderColor3=Color3.new(0.105882, 0.164706, 0.207843),BorderSizePixel=1,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.81209147, 0, 0.710447788, 0),Rotation=0,Selectable=true,Size=UDim2.new(0, 20, 0, 20),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='useworth',Parent = c2})
        useworth.MouseButton1Click:Connect(function()
            if useworth.ImageColor3 ==  Color3.new(1, 0.172549, 0.184314) then
                useworth.ImageColor3=Color3.new(0.462745, 1, 0.298039)
                worthused=true
            elseif useworth.ImageColor3 ==  Color3.new(0.462745, 1, 0.298039) then
                useworth.ImageColor3 = Color3.new(1, 0.172549, 0.184314)
                worthused=false
            end
        end)
    end
    function Novaconfg:Createluck()
        local luckb = CreateInstance('ImageButton',{Image='http://www.roblox.com/asset/?id=1974474320',ImageColor3=Color3.new(1, 0.172549, 0.184314),ImageRectOffset=Vector2.new(0, 0),ImageRectSize=Vector2.new(0, 0),ImageTransparency=0,ScaleType=Enum.ScaleType.Crop,SliceCenter=Rect.new(0, 0, 0, 0),AutoButtonColor=true,Modal=false,Selected=false,Style=Enum.ButtonStyle.Custom,Active=true,AnchorPoint=Vector2.new(0.5, 0.5),BackgroundColor3=Color3.new(1, 1, 1),BackgroundTransparency=1,BorderColor3=Color3.new(0.105882, 0.164706, 0.207843),BorderSizePixel=1,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.81209147, 0, 0.710447788, 0),Rotation=0,Selectable=true,Size=UDim2.new(0, 20, 0, 20),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='useluck',Parent = c2})
        luckb.MouseButton1Click:Connect(function()
            if luckb.ImageColor3 ==  Color3.new(1, 0.172549, 0.184314) then
                luckb.ImageColor3=Color3.new(0.462745, 1, 0.298039)
                lucky=true
            elseif luckb.ImageColor3 ==  Color3.new(0.462745, 1, 0.298039) then
                luckb.ImageColor3 = Color3.new(1, 0.172549, 0.184314)
                lucky=false
            end
        end)
    end
    function Novaconfg:CreateStorage()
        local store = CreateInstance('ImageButton',{Image='http://www.roblox.com/asset/?id=1974474320',ImageColor3=Color3.new(1, 0.172549, 0.184314),ImageRectOffset=Vector2.new(0, 0),ImageRectSize=Vector2.new(0, 0),ImageTransparency=0,ScaleType=Enum.ScaleType.Crop,SliceCenter=Rect.new(0, 0, 0, 0),AutoButtonColor=true,Modal=false,Selected=false,Style=Enum.ButtonStyle.Custom,Active=true,AnchorPoint=Vector2.new(0.5, 0.5),BackgroundColor3=Color3.new(1, 1, 1),BackgroundTransparency=1,BorderColor3=Color3.new(0.105882, 0.164706, 0.207843),BorderSizePixel=1,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.81209147, 0, 0.710447788, 0),Rotation=0,Selectable=true,Size=UDim2.new(0, 20, 0, 20),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='useluck',Parent = c2})
        store.MouseButton1Click:Connect(function()
            if store.ImageColor3 ==  Color3.new(1, 0.172549, 0.184314) then
                store.ImageColor3=Color3.new(0.462745, 1, 0.298039)
                storagestand=true
            elseif store.ImageColor3 ==  Color3.new(0.462745, 1, 0.298039) then
                store.ImageColor3 = Color3.new(1, 0.172549, 0.184314)
                storagestand=false
            end
        end)
    end
    function Novaconfg:Createreq()
        local usereq = CreateInstance('ImageButton',{Image='http://www.roblox.com/asset/?id=1974474320',ImageColor3=Color3.new(1, 0.172549, 0.184314),ImageRectOffset=Vector2.new(0, 0),ImageRectSize=Vector2.new(0, 0),ImageTransparency=0,ScaleType=Enum.ScaleType.Crop,SliceCenter=Rect.new(0, 0, 0, 0),AutoButtonColor=true,Modal=false,Selected=false,Style=Enum.ButtonStyle.Custom,Active=true,AnchorPoint=Vector2.new(0.5, 0.5),BackgroundColor3=Color3.new(1, 1, 1),BackgroundTransparency=1,BorderColor3=Color3.new(0.105882, 0.164706, 0.207843),BorderSizePixel=1,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.81209147, 0, 0.710447788, 0),Rotation=0,Selectable=true,Size=UDim2.new(0, 20, 0, 20),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='usereq',Parent = c2})
        usereq.MouseButton1Click:Connect(function()
            if usereq.ImageColor3 ==  Color3.new(1, 0.172549, 0.184314) then
                usereq.ImageColor3=Color3.new(0.462745, 1, 0.298039)
                reqused=true
            elseif usereq.ImageColor3 ==  Color3.new(0.462745, 1, 0.298039) then
                usereq.ImageColor3 = Color3.new(1, 0.172549, 0.184314)
                reqused=false
            end
        end)
    end
    function Novaconfg:Createexecute()
        local Executep = CreateInstance('TextButton',{Font=Enum.Font.SourceSans,FontSize=Enum.FontSize.Size32,Text='Execute',TextColor3=Color3.new(1, 1, 1),TextScaled=false,TextSize=30,TextStrokeColor3=Color3.new(0, 0, 0),TextStrokeTransparency=1,TextTransparency=0,TextWrapped=true,TextXAlignment=Enum.TextXAlignment.Center,TextYAlignment=Enum.TextYAlignment.Center,AutoButtonColor=true,Modal=false,Selected=false,Style=Enum.ButtonStyle.Custom,Active=true,AnchorPoint=Vector2.new(0, 0),BackgroundColor3=Color3.new(0.117647, 0.117647, 0.117647),BackgroundTransparency=0,BorderColor3=Color3.new(0.105882, 0.164706, 0.207843),BorderSizePixel=0,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.0130718956, 0, 0.0238805972, 0),Rotation=0,Selectable=true,Size=UDim2.new(0, 150, 0, 25),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='Executep',Parent = c2})
        Executep.MouseButton1Click:Connect(function()
            if storagestand ==true then
                backstor.Visible=true
            else   
            Menu.Visible=true
            end
        end)
    end        
    function Novaconfg:Createexecutefinal(callback)
     local btngetchoosed = CreateInstance('TextButton',{Font=Enum.Font.GothamSemibold,FontSize=Enum.FontSize.Size18,Text='Execute',TextColor3=Color3.new(1, 1, 1),TextScaled=false,TextSize=16,TextStrokeColor3=Color3.new(0, 0, 0),TextStrokeTransparency=1,TextTransparency=0,TextWrapped=true,TextXAlignment=Enum.TextXAlignment.Center,TextYAlignment=Enum.TextYAlignment.Center,AutoButtonColor=true,Modal=false,Selected=false,Style=Enum.ButtonStyle.Custom,Active=true,AnchorPoint=Vector2.new(0, 0),BackgroundColor3=Color3.new(0.376471, 0.792157, 0.313726),BackgroundTransparency=0,BorderColor3=Color3.new(0.105882, 0.164706, 0.207843),BorderSizePixel=0,ClipsDescendants=false,Draggable=false,Position=UDim2.new(0.746304214, 0, 0.929008543, 0),Rotation=0,Selectable=true,Size=UDim2.new(0, 71, 0, 23),SizeConstraint=Enum.SizeConstraint.RelativeXY,Visible=true,ZIndex=1,Name='btngetchoosed',Parent = Menu})
      btngetchoosed.MouseButton1Click:Connect(function()
        callback(btngetchoosed)
      end)
    end
  return Novaconfg;
end
return Nova;
