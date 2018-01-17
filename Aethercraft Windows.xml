<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE MudletPackage>
<MudletPackage version="1.001">
    <TriggerPackage>
        <Trigger isActive="yes" isFolder="no" isTempTrigger="no" isMultiline="no" isPerlSlashGOption="no" isColorizerTrigger="no" isFilterTrigger="no" isSoundTrigger="no" isColorTrigger="no" isColorTriggerFg="no" isColorTriggerBg="no">
            <name>grid lock</name>
            <script>allmodules = {}
turret_check = false
grid_container:show()
send(&quot;grid modules&quot;)</script>
            <triggerType>0</triggerType>
            <conditonLineDelta>0</conditonLineDelta>
            <mStayOpen>0</mStayOpen>
            <mCommand></mCommand>
            <packageName></packageName>
            <mFgColor>#ff0000</mFgColor>
            <mBgColor>#ffff00</mBgColor>
            <mSoundFile></mSoundFile>
            <colorTriggerFgColor>#000000</colorTriggerFgColor>
            <colorTriggerBgColor>#000000</colorTriggerBgColor>
            <regexCodeList>
                <string>You step up to the empathic grid, locking yourself into the module and linking your mind to the controls of the ship. After a moment, you begin to sense your command of the module in your own brain.</string>
            </regexCodeList>
            <regexCodePropertyList>
                <integer>3</integer>
            </regexCodePropertyList>
        </Trigger>
        <Trigger isActive="yes" isFolder="no" isTempTrigger="no" isMultiline="no" isPerlSlashGOption="no" isColorizerTrigger="no" isFilterTrigger="no" isSoundTrigger="no" isColorTrigger="no" isColorTriggerFg="no" isColorTriggerBg="no">
            <name>grid unlock</name>
            <script>allmodules = {}
turret_check = false
grid_container:hide()</script>
            <triggerType>0</triggerType>
            <conditonLineDelta>0</conditonLineDelta>
            <mStayOpen>0</mStayOpen>
            <mCommand></mCommand>
            <packageName></packageName>
            <mFgColor>#ff0000</mFgColor>
            <mBgColor>#ffff00</mBgColor>
            <mSoundFile></mSoundFile>
            <colorTriggerFgColor>#000000</colorTriggerFgColor>
            <colorTriggerBgColor>#000000</colorTriggerBgColor>
            <regexCodeList>
                <string>With a long, slow blink, you allow your mind to drift free from the ship, and release your lock on the command of the empathic grid.</string>
            </regexCodeList>
            <regexCodePropertyList>
                <integer>3</integer>
            </regexCodePropertyList>
        </Trigger>
        <Trigger isActive="yes" isFolder="no" isTempTrigger="no" isMultiline="no" isPerlSlashGOption="no" isColorizerTrigger="no" isFilterTrigger="no" isSoundTrigger="no" isColorTrigger="no" isColorTriggerFg="no" isColorTriggerBg="no">
            <name>grid capture</name>
            <script>
local module = matches[2]
if module == &quot;chair&quot; then
allmodules[&quot;chair&quot;] = matches[3]
end
if module == &quot;grid&quot; then
allmodules[&quot;grid&quot;] = matches[3]
end
if module == &quot;turret&quot; then
	if turret_check == false then
		allmodules[&quot;turret1&quot;] = matches[3]
		turret_check = 1
	elseif turret_check == 1 then
		allmodules[&quot;turret2&quot;] = matches[3]
		turret_check = 2
	elseif turret_check == 2 then
		allmodules[&quot;turret3&quot;] = matches[3]
		turret_check = false
	end
end
if module == &quot;orb&quot; then
	allmodules[&quot;orb&quot;] = matches[3]
end</script>
            <triggerType>0</triggerType>
            <conditonLineDelta>0</conditonLineDelta>
            <mStayOpen>0</mStayOpen>
            <mCommand></mCommand>
            <packageName></packageName>
            <mFgColor>#ff0000</mFgColor>
            <mBgColor>#ffff00</mBgColor>
            <mSoundFile></mSoundFile>
            <colorTriggerFgColor>#000000</colorTriggerFgColor>
            <colorTriggerBgColor>#000000</colorTriggerBgColor>
            <regexCodeList>
                <string>^\&quot;(chair|grid|turret|collector|orb|ramhead)(\d+)\&quot;\s+(the command chair|a battle turret|a shield orb|the empathic grid|an energy collector)\s+(\d+)\% / (no damage|light damage|heavy damage|moderate damage|critical damage)(?:\s+\[(\w+)\]|)</string>
            </regexCodeList>
            <regexCodePropertyList>
                <integer>1</integer>
            </regexCodePropertyList>
        </Trigger>
        <Trigger isActive="yes" isFolder="no" isTempTrigger="no" isMultiline="no" isPerlSlashGOption="no" isColorizerTrigger="no" isFilterTrigger="no" isSoundTrigger="no" isColorTrigger="no" isColorTriggerFg="no" isColorTriggerBg="no">
            <name>chair lock</name>
            <script>chair_container:show()</script>
            <triggerType>0</triggerType>
            <conditonLineDelta>0</conditonLineDelta>
            <mStayOpen>0</mStayOpen>
            <mCommand></mCommand>
            <packageName></packageName>
            <mFgColor>#ff0000</mFgColor>
            <mBgColor>#ffff00</mBgColor>
            <mSoundFile></mSoundFile>
            <colorTriggerFgColor>#000000</colorTriggerFgColor>
            <colorTriggerBgColor>#000000</colorTriggerBgColor>
            <regexCodeList>
                <string>You step up to the command chair, locking yourself into the module and linking your mind to the controls of the ship. After a moment, you begin to sense your command of the module in your own brain.</string>
            </regexCodeList>
            <regexCodePropertyList>
                <integer>3</integer>
            </regexCodePropertyList>
        </Trigger>
        <Trigger isActive="yes" isFolder="no" isTempTrigger="no" isMultiline="no" isPerlSlashGOption="no" isColorizerTrigger="no" isFilterTrigger="no" isSoundTrigger="no" isColorTrigger="no" isColorTriggerFg="no" isColorTriggerBg="no">
            <name>chair unlock</name>
            <script>chair_container:hide()</script>
            <triggerType>0</triggerType>
            <conditonLineDelta>0</conditonLineDelta>
            <mStayOpen>0</mStayOpen>
            <mCommand></mCommand>
            <packageName></packageName>
            <mFgColor>#ff0000</mFgColor>
            <mBgColor>#ffff00</mBgColor>
            <mSoundFile></mSoundFile>
            <colorTriggerFgColor>#000000</colorTriggerFgColor>
            <colorTriggerBgColor>#000000</colorTriggerBgColor>
            <regexCodeList>
                <string>With a long, slow blink, you allow your mind to drift free from the ship, and release your lock on the command of the command chair.</string>
            </regexCodeList>
            <regexCodePropertyList>
                <integer>3</integer>
            </regexCodePropertyList>
        </Trigger>
    </TriggerPackage>
    <TimerPackage>
        <Timer isActive="no" isFolder="no" isTempTimer="no" isOffsetTimer="no">
            <name>grid_drag_window</name>
            <script>local x, y = getMousePosition()
windowpositions.grid_x = x
windowpositions.grid_y = y
table.save(getMudletHomeDir() .. &quot;/windowpositions&quot;, windowpositions)
grid_container:move(getMousePosition())
</script>
            <command></command>
            <packageName></packageName>
            <time>00:00:00.025</time>
        </Timer>
        <Timer isActive="no" isFolder="no" isTempTimer="no" isOffsetTimer="no">
            <name>chair_drag_window</name>
            <script>local x, y = getMousePosition()
windowpositions.chair_x = x
windowpositions.chair_y = y
table.save(getMudletHomeDir() .. &quot;/windowpositions&quot;, windowpositions)
chair_container:move(getMousePosition())
</script>
            <command></command>
            <packageName></packageName>
            <time>00:00:00.025</time>
        </Timer>
        <Timer isActive="no" isFolder="no" isTempTimer="no" isOffsetTimer="no">
            <name>grid_resize_window</name>
            <script>local x, y = getMousePosition()
grid_new_width = windowpositions.grid_width + (x - windowpositions.grid_start_x)
grid_new_height = windowpositions.grid_height + (y - windowpositions.grid_start_y)

grid_container:resize(grid_new_width, grid_new_height)</script>
            <command></command>
            <packageName></packageName>
            <time>00:00:00.025</time>
        </Timer>
        <Timer isActive="no" isFolder="no" isTempTimer="no" isOffsetTimer="no">
            <name>chair_resize_window</name>
            <script>local x, y = getMousePosition()
chair_new_width = windowpositions.chair_width + (x - windowpositions.chair_start_x)
chair_new_height = windowpositions.chair_height + (y - windowpositions.chair_start_y)

chair_container:resize(chair_new_width, chair_new_height)</script>
            <command></command>
            <packageName></packageName>
            <time>00:00:00.025</time>
        </Timer>
    </TimerPackage>
    <AliasPackage/>
    <ActionPackage/>
    <ScriptPackage>
        <Script isActive="yes" isFolder="no">
            <name>file_exists</name>
            <packageName></packageName>
            <script>function file_exists(name)
   local f=io.open(name,&quot;r&quot;)
   if f~=nil then io.close(f) return true else return false end
end</script>
            <eventHandlerList/>
        </Script>
        <Script isActive="yes" isFolder="no">
            <name>Grid Window</name>
            <packageName></packageName>
            <script>
windowpositions = {
	grid_x = 50,
	grid_y = 50,
	chair_x = 50,
	chair_y = 50,
	chair_width = 400,
	chair_height = 300,
	grid_width = 400,
	grid_height = 300,
	chair_start_x = nil,
	chair_start_y = nil,
	grid_start_x = nil,
	grid_start_y = nil,
}
if file_exists(getMudletHomeDir()..&quot;/windowpositions&quot;) then
table.load(getMudletHomeDir() .. &quot;/windowpositions&quot;, windowpositions)
end
target_ship = 11111

local background_color = &quot;rgb(153, 179, 255)&quot;
local title_color = &quot;rgb(0 , 85, 128)&quot;
local border_color = &quot;rgb(122, 122, 82)&quot;
local button_color = &quot;rgb(27, 30, 35)&quot;
local text_color = &quot;goldenrod&quot;  --this one has to be a word, until I can figure out how to do it differently

--[[ 
https://www.w3schools.com/colors/colors_picker.asp
--]]

allmodules = {}
allmodules[&quot;grid&quot;] = 1
allmodules[&quot;chair&quot;] = 1
allmodules[&quot;turret1&quot;] = 1
allmodules[&quot;turret2&quot;] = 1
allmodules[&quot;turret3&quot;] = 1
allmodules[&quot;orb&quot;] = 1


grid_container = Geyser.Container:new({
	name = &quot;grid_container&quot;,
	x = windowpositions.grid_x, y = windowpositions.grid_y,
	width = windowpositions.grid_width,
	height = windowpositions.grid_height,
})

grid_background_label = Geyser.Label:new({
	name = &quot;grid_background_label&quot;,
	x = 0, y = 0,
	width = &quot;100%&quot;,
	height = &quot;100%&quot;,
}, grid_container)

grid_background_label:setStyleSheet([[
	background-color: ]]..background_color..[[;
]])

grid_title_bar = Geyser.Label:new({
	name = &quot;grid_title_bar&quot;,
	x = &quot;5%&quot;, y = 0,
	height = &quot;8%&quot;,
	width = &quot;95%&quot;,
	fgColor = text_color,
	message = [[&lt;center&gt;Grid Module&lt;/center&gt;]]
}, grid_container)

grid_title_bar:setStyleSheet([[
	background-color: ]]..title_color..[[;
]])

grid_drag_move = Geyser.Label:new({
	name = &quot;grid_drag_move&quot;,
	x = 0, y = 0,
	width = &quot;5%&quot;,
	height = &quot;8%&quot;,
	fgColor = text_color,
	message = [[+]]
}, grid_container)

grid_drag_move:setStyleSheet([[
	background-color: ]]..title_color..[[;
]])
grid_hide = Geyser.Label:new({
	name = &quot;grid_hide&quot;,
	x = &quot;95%&quot;, y = 0,
	width = &quot;5%&quot;,
	height = &quot;8%&quot;,
	fgColor = text_color,
	message = [[&lt;center&gt;X&lt;/center&gt;]]
}, grid_container)
grid_hide:setStyleSheet([[
	background-color: ]]..title_color..[[
]])
function gridhide()
grid_container:hide()
end
grid_hide:setClickCallback(&quot;gridhide&quot;)

local left_buttons = {
	{text = &quot;Repair Hull&quot;, send = &quot;grid repair hull&quot;},
	{text = &quot;Repair Grid&quot;, send = &quot;grid repair module &quot;..allmodules[&quot;grid&quot;]},
	{text = &quot;Repair Chair&quot;, send = &quot;grid repair module &quot;..allmodules[&quot;chair&quot;]},
	{text = &quot;Repair Turret1&quot;, send = &quot;grid repair module &quot;..allmodules[&quot;turret1&quot;]},
	{text = &quot;Repair Turret2&quot;, send = &quot;grid repair module &quot;..allmodules[&quot;turret2&quot;]},
	{text = &quot;Repair Turret3&quot;, send = &quot;grid repair module &quot;..allmodules[&quot;turret3&quot;]},
	{text = &quot;Repair Orb&quot;, send = &quot;grid repair module &quot;..allmodules[&quot;orb&quot;]},
}
local middle_buttons = {
	{text = &quot;Repair Module&quot;, send = &quot;grid repair module&quot;},
	{text = &quot;Clarity Grid&quot;, send = &quot;grid clarity &quot;..allmodules[&quot;grid&quot;]},
	{text = &quot;Clarity Chair&quot;, send = &quot;grid clarity &quot;..allmodules[&quot;chair&quot;]},
	{text = &quot;Clarity Turret1&quot;, send = &quot;grid clarity &quot;..allmodules[&quot;turret1&quot;]},
	{text = &quot;Clarity Turret2&quot;, send = &quot;grid clarity &quot;..allmodules[&quot;turret2&quot;]},
	{text = &quot;Clarity Turret3&quot;, send = &quot;grid clarity &quot;..allmodules[&quot;turret3&quot;]},
	{text = &quot;Clarity Orb&quot;, send = &quot;grid clarity &quot;..allmodules[&quot;orb&quot;]},
}
local right_buttons = {
	{text = &quot;Analyze Ship&quot;, send = &quot;grid analyze ship &quot;..target_ship},
	{text = &quot;Planarbond&quot;, send = &quot;grid planarbond&quot;},
	{text = &quot;Flush&quot;, send = &quot;grid flush&quot;},
	{text = &quot;Regenerate Chair&quot;, send = &quot;grid regenerate &quot;..allmodules[&quot;chair&quot;]},
	{text = &quot;Regenerate Turret1&quot;, send = &quot;grid regenerate &quot;..allmodules[&quot;turret1&quot;]},
	{text = &quot;Regenerate Turret2&quot;, send = &quot;grid regenerate &quot;..allmodules[&quot;turret2&quot;]},
	{text = &quot;Regenerate Turret3&quot;, send = &quot;grid regenerate &quot;..allmodules[&quot;turret3&quot;]},
}

 grid_vbox1 = Geyser.VBox:new({
	name = &quot;grid_vbox1&quot;,
	x = 0, y = &quot;8%&quot;,
	width = &quot;33%&quot;,
	height = &quot;92%&quot;,
}, grid_container)
 grid_vbox2 = Geyser.VBox:new({
	name = &quot;grid_vbox2&quot;,
	x = &quot;33%&quot;, y = &quot;8%&quot;,
	width = &quot;33%&quot;,
	height = &quot;92%&quot;,
}, grid_container)
 grid_vbox3 = Geyser.VBox:new({
	name = &quot;grid_vbox3&quot;,
	x = &quot;66%&quot;, y = &quot;8%&quot;,
	width = &quot;34%&quot;,
	height = &quot;92%&quot;,
}, grid_container)
function grid_button(data)
send(&quot;&quot;..data)
end
for k, v in ipairs(left_buttons) do
	local name = v.text
	name = Geyser.Label:new({
	name = name,
	fgColor = text_color,
	message = [[&lt;center&gt;]]..v.text..[[&lt;/center&gt;]]
	}, grid_vbox1)
	name:setStyleSheet([[
	background-color: ]]..button_color..[[;
  border-width: 1px;
  border-style: solid;
  border-color: ]]..border_color..[[;
  border-radius: 10px;
	]])
	name:setClickCallback(&quot;grid_button&quot;, v.send)
end
for k, v in ipairs(middle_buttons) do
	local name = v.text
	name = Geyser.Label:new({
	name = name,
	fgColor = text_color,
	message = [[&lt;center&gt;]]..v.text..[[&lt;/center&gt;]]
	}, grid_vbox2)
	name:setStyleSheet([[
	background-color: ]]..button_color..[[;
  border-width: 1px;
  border-style: solid;
  border-color: ]]..border_color..[[;
  border-radius: 10px;
	]])
	name:setClickCallback(&quot;grid_button&quot;, v.send)
end
for k, v in ipairs(right_buttons) do
	local name = v.text
	name = Geyser.Label:new({
	name = name,
	fgColor = text_color,
	message = [[&lt;center&gt;]]..v.text..[[&lt;/center&gt;]]
	}, grid_vbox3)
	name:setStyleSheet([[
	background-color: ]]..button_color..[[;
  border-width: 1px;
  border-style: solid;
  border-color: ]]..border_color..[[;
  border-radius: 10px;
	]])
	name:setClickCallback(&quot;grid_button&quot;, v.send)
end

grid_resize_label = Geyser.Label:new({
	x = &quot;95%&quot;, y = &quot;95%&quot;,
	width = &quot;5%&quot;,
	height = &quot;5%&quot;,
	message = [[&lt;center&gt;*&lt;/center&gt;]]
}, grid_container)
grid_resize_label:setStyleSheet([[
	background-color: rgba(0,0,0,0%);
]])
function grid_drag_click()
enableTimer(&quot;grid_drag_window&quot;)
end
function grid_drag_release()
disableTimer(&quot;grid_drag_window&quot;)
end
function grid_resize_click()
windowpositions.grid_start_x, windowpositions.grid_start_y = getMousePosition()
enableTimer(&quot;grid_resize_window&quot;)
end
function grid_resize_release()
disableTimer(&quot;grid_resize_window&quot;)
windowpositions.grid_width = grid_new_width
windowpositions.grid_height = grid_new_height
table.save(getMudletHomeDir() .. &quot;/windowpositions&quot;, windowpositions)
end
grid_resize_label:setClickCallback(&quot;grid_resize_click&quot;)
grid_resize_label:setReleaseCallback(&quot;grid_resize_release&quot;)
grid_drag_move:setClickCallback(&quot;grid_drag_click&quot;)
grid_drag_move:setReleaseCallback(&quot;grid_drag_release&quot;)
grid_container:show()</script>
            <eventHandlerList/>
        </Script>
        <Script isActive="yes" isFolder="no">
            <name>Pilot Module</name>
            <packageName></packageName>
            <script>
windowpositions = {
	grid_x = 50,
	grid_y = 50,
	chair_x = 50,
	chair_y = 50,
	chair_width = 400,
	chair_height = 300,
	grid_width = 400,
	grid_height = 300,
	chair_start_x = nil,
	chair_start_y = nil,
	grid_start_x = nil,
	grid_start_y = nil,
}

if file_exists(getMudletHomeDir()..&quot;/windowpositions&quot;) then
table.load(getMudletHomeDir() .. &quot;/windowpositions&quot;, windowpositions)
end


local background_color = &quot;rgb(153, 179, 255)&quot;
local title_color = &quot;rgb(0 , 85, 128)&quot;
local border_color = &quot;rgb(122, 122, 82)&quot;
local button_color = &quot;rgb(27, 30, 35)&quot;
local text_color = &quot;goldenrod&quot;  --this one has to be a word, until I can figure out how to do it differently

--[[ 
https://www.w3schools.com/colors/colors_picker.asp
--]]

chair_container = Geyser.Container:new({
	name = &quot;chair_container&quot;,
	x = windowpositions.chair_x, y = windowpositions.chair_y,
	width = windowpositions.chair_width,
	height = windowpositions.chair_height,	
})

chair_background_label = Geyser.Label:new({
	name = &quot;chair_background_label&quot;,
	x = 0, y = 0,
	width = &quot;100%&quot;,
	height = &quot;100%&quot;,
	
}, chair_container)
chair_background_label:setStyleSheet([[
	background-color: ]]..background_color..[[;
]])

chair_title_bar = Geyser.Label:new({
	name = &quot;chair_title_bar&quot;,
	x = &quot;5%&quot;, y = 0,
	width = &quot;95%&quot;,
	height = &quot;8%&quot;,
	fgColor = text_color,
	message = [[&lt;center&gt;Chair Module&lt;/center&gt;]]
}, chair_container)
chair_title_bar:setStyleSheet([[
	background-color: ]]..title_color..[[;
]])

chair_drag_move = Geyser.Label:new({
	name = &quot;chair_drag_move&quot;,
	x = 0, y = 0,
	width = &quot;5%&quot;,
	height = &quot;8%&quot;,
	fgColor = text_color,
	message = [[&lt;center&gt;+&lt;/center&gt;]]
}, chair_container)
chair_drag_move:setStyleSheet([[
	background-color: ]]..title_color..[[;
]])
chair_hide = Geyser.Label:new({
	name = &quot;chair_hide&quot;,
	x = &quot;95%&quot;, y = 0,
	width = &quot;5%&quot;,
	height = &quot;8%&quot;,
	fgColor = text_color,
	message = [[&lt;center&gt;X&lt;/center&gt;]]
}, chair_container)
chair_hide:setStyleSheet([[
	background-color: ]]..title_color..[[;
]])
function chairhide()
chair_container:hide()
end
chair_hide:setClickCallback(&quot;chairhide&quot;)
local col1 = {
	{text = &quot;G-NW&quot;, send = &quot;pilot glide nw&quot;},
	{text = &quot;1&quot;, send = &quot;&quot;},
	{text = &quot;G-W&quot;, send = &quot;pilot glide w&quot;},
	{text = &quot;2&quot;, send = &quot;&quot;},
	{text = &quot;G-SW&quot;, send = &quot;pilot glide sw&quot;},
}
local col2 = {
	{text = &quot;3&quot;, send = &quot;&quot;},
	{text = &quot;NW&quot;, send = &quot;pilot steer nw&quot;},
	{text = &quot;W&quot;, send = &quot;pilot steer w&quot;},
	{text = &quot;SW&quot;, send = &quot;pilot steer sw&quot;},
	{text = &quot;4&quot;, send = &quot;&quot;},
}
local col3 = {
	{text = &quot;G-N&quot;, send = &quot;pilot glide n&quot;},
	{text = &quot;N&quot;, send = &quot;pilot steer n&quot;},
	{text = &quot;Stop&quot;, send = &quot;pilot glide stop&quot;},
	{text = &quot;S&quot;, send = &quot;pilot steer s&quot;},
	{text = &quot;G-S&quot;, send = &quot;pilot glide s&quot;},
}
local col4 = {
	{text = &quot;5&quot;, send = &quot;&quot;},
	{text = &quot;NE&quot;, send = &quot;pilot steer ne&quot;},
	{text = &quot;E&quot;, send = &quot;pilot steer e&quot;},
	{text = &quot;SE&quot;, send = &quot;pilot steer se&quot;},
	{text = &quot;6&quot;, send = &quot;&quot;},
}
local col5 = {
	{text = &quot;G-NE&quot;, send = &quot;pilot glide ne&quot;},
	{text = &quot;Launch&quot;, send = &quot;pilot launch&quot;},
	{text = &quot;G-E&quot;, send = &quot;pilot glide e&quot;},
	{text = &quot;Dock&quot;, send = &quot;pilot dock&quot;},
	{text = &quot;G-SE&quot;, send = &quot;pilot glide se&quot;},
}
local col6 = {
	{text = &quot;Silent On&quot;, send = &quot;pilot silentrun start&quot;},
	{text = &quot;Silent Off&quot;, send = &quot;pilot silentrun stop&quot;},
	{text = &quot;Farhorizon On&quot;, send = &quot;pilot farhorizon start&quot;},
	{text = &quot;Farhorizon Off&quot;, send = &quot;pilot farhorizon stop&quot;},
	{text = &quot;Forcefield&quot;, send = &quot;pilot forcefield&quot;},	
}
local width = 15

 chair_vbox1 = Geyser.VBox:new({
	name = &quot;chair_vbox1&quot;,
	x = 0, y = &quot;8%&quot;,
	width = width..&quot;%&quot;,
	height = &quot;77%&quot;,
}, chair_container)

 chair_vbox2 = Geyser.VBox:new({
	name = &quot;chair_vbox2&quot;,
	x = &quot;15%&quot;, y = &quot;8%&quot;,
	width = width..&quot;%&quot;,
	height = &quot;77%&quot;,
}, chair_container)

 chair_vbox3 = Geyser.VBox:new({
	name = &quot;chair_vbox3&quot;,
	x = &quot;30%&quot;, y = &quot;8%&quot;,
	width = width..&quot;%&quot;,
	height = &quot;77%&quot;,
}, chair_container)
 chair_vbox4 = Geyser.VBox:new({
	name = &quot;chair_vbox4&quot;,
	x = &quot;45%&quot;, y = &quot;8%&quot;,
	width = width..&quot;%&quot;,
	height = &quot;77%&quot;,
}, chair_container)
 chair_vbox5 = Geyser.VBox:new({
	name = &quot;chair_vbox5&quot;,
	x = &quot;60%&quot;, y = &quot;8%&quot;,
	width = width..&quot;%&quot;,
	height = &quot;77%&quot;,
}, chair_container)
 chair_vbox6 = Geyser.VBox:new({
	name = &quot;chair_vbox6&quot;,
	x = &quot;75%&quot;, y = &quot;8%&quot;,
	width = &quot;25%&quot;,
	height = &quot;77%&quot;,
}, chair_container)
chair_hbox1 = Geyser.HBox:new({
	name = &quot;chair_hbox1&quot;,
	x = 0, y = &quot;85%&quot;,
	width = &quot;100%&quot;,
	height = &quot;15%&quot;,
}, chair_container)
ship_look = Geyser.Label:new({
	name = &quot;ship_look&quot;,
	fgColor = text_color,
	message = [[&lt;center&gt;Ship Look&lt;/center&gt;]]
	
}, chair_hbox1)
ship_look:setStyleSheet([[
	background-color: ]]..button_color..[[;
  border-width: 1px;
  border-style: solid;
  border-color: ]]..border_color..[[;
  border-radius: 10px;
]])
ship_status = Geyser.Label:new({
	name = &quot;ship_status&quot;,
	fgColor = text_color,
	message = [[&lt;center&gt;Ship Status&lt;/center&gt;]]
	
}, chair_hbox1)
ship_status:setStyleSheet([[
	background-color: ]]..button_color..[[;
  border-width: 1px;
  border-style: solid;
  border-color: ]]..border_color..[[;
  border-radius: 10px;
]])

function chair_button(data)
send(data)
end
ship_look:setClickCallback(&quot;chair_button&quot;, &quot;ship look&quot;)
ship_status:setClickCallback(&quot;chair_button&quot;, &quot;ship status&quot;)
for k, v in ipairs(col1) do
	local name = v.text
	if string.match(v.text, &quot;%d+&quot;) then
	msg = &quot; &quot;
	else
	msg = v.text
	end
	name = Geyser.Label:new({
	name = name,
	fgColor = text_color,
	message = [[&lt;center&gt;]]..msg..[[&lt;/center&gt;]]
	}, chair_vbox1)
	name:setStyleSheet([[
	background-color: ]]..button_color..[[;
  border-width: 1px;
  border-style: solid;
  border-color: ]]..border_color..[[;
  border-radius: 10px;
	]])
  name:setClickCallback(&quot;chair_button&quot;, v.send)
end

for k, v in ipairs(col2) do
	local name = v.text
	if string.match(v.text, &quot;%d+&quot;) then
	msg = &quot; &quot;
	else
	msg = v.text
	end
	name = Geyser.Label:new({
	name = name,
	fgColor = text_color,
	message = [[&lt;center&gt;]]..msg..[[&lt;/center&gt;]]
	}, chair_vbox2)
	name:setStyleSheet([[
	background-color: ]]..button_color..[[;
  border-width: 1px;
  border-style: solid;
  border-color: ]]..border_color..[[;
  border-radius: 10px;
	]])
	name:setClickCallback(&quot;chair_button&quot;, v.send)
end

for k, v in ipairs(col3) do
	local name = v.text
	if string.match(v.text, &quot;%d+&quot;) then
	msg = &quot; &quot;
	else
	msg = v.text
	end
	name = Geyser.Label:new({
	name = name,
	fgColor = text_color,
	message = [[&lt;center&gt;]]..msg..[[&lt;/center&gt;]]
	}, chair_vbox3)
	name:setStyleSheet([[
	background-color: ]]..button_color..[[;
  border-width: 1px;
  border-style: solid;
  border-color: ]]..border_color..[[;
  border-radius: 10px;
	]])
	name:setClickCallback(&quot;chair_button&quot;, v.send)
end

for k, v in ipairs(col4) do
	local name = v.text
	if string.match(v.text, &quot;%d+&quot;) then
	msg = &quot; &quot;
	else
	msg = v.text
	end
	name = Geyser.Label:new({
	name = name,
	fgColor = text_color,
	message = [[&lt;center&gt;]]..msg..[[&lt;/center&gt;]]
	}, chair_vbox4)
	name:setStyleSheet([[
	background-color: ]]..button_color..[[;
  border-width: 1px;
  border-style: solid;
  border-color: ]]..border_color..[[;
  border-radius: 10px;
	]])
	name:setClickCallback(&quot;chair_button&quot;, v.send)
end

for k, v in ipairs(col5) do
	local name = v.text
	if string.match(v.text, &quot;%d&quot;) then
	msg = &quot; &quot;
	else
	msg = v.text
	end
	name = Geyser.Label:new({
	name = name,
	fgColor = text_color,
	message = [[&lt;center&gt;]]..msg..[[&lt;/center&gt;]]
	}, chair_vbox5)
	name:setStyleSheet([[
	background-color: ]]..button_color..[[;
  border-width: 1px;
  border-style: solid;
  border-color: ]]..border_color..[[;
  border-radius: 10px;
	]])
	name:setClickCallback(&quot;chair_button&quot;, v.send)
end

for k, v in ipairs(col6) do
	local name = v.text
	if string.match(v.text, &quot;%d&quot;) then
	msg = &quot; &quot;
	else
	msg = v.text
	end
	name = Geyser.Label:new({
	name = name,
	fgColor = text_color,
	message = [[&lt;center&gt;]]..msg..[[&lt;/center&gt;]]
	}, chair_vbox6)
	name:setStyleSheet([[
	background-color: ]]..button_color..[[;
  border-width: 1px;
  border-style: solid;
  border-color: ]]..border_color..[[;
  border-radius: 10px;
	]])
	name:setClickCallback(&quot;chair_button&quot;, v.send)
end

function chair_on_click()
enableTimer(&quot;chair_drag_window&quot;)
end
function chair_on_release()
disableTimer(&quot;chair_drag_window&quot;)
end

chair_resize_label = Geyser.Label:new({
	x = &quot;95%&quot;, y = &quot;95%&quot;,
	width = &quot;5%&quot;,
	height = &quot;5%&quot;,
	message = [[&lt;center&gt;*&lt;/center&gt;]]
}, chair_container)
chair_resize_label:setStyleSheet([[
	background-color: rgba(0,0,0,0%);
]])
function chair_drag_click()
enableTimer(&quot;chair_drag_window&quot;)
end
function chair_drag_release()
disableTimer(&quot;chair_drag_window&quot;)
end
function chair_resize_click()
windowpositions.chair_start_x, windowpositions.chair_start_y = getMousePosition()
enableTimer(&quot;chair_resize_window&quot;)
end
function chair_resize_release()
disableTimer(&quot;chair_resize_window&quot;)
windowpositions.chair_width = chair_new_width
windowpositions.chair_height = chair_new_height
table.save(getMudletHomeDir() .. &quot;/windowpositions&quot;, windowpositions)
end
chair_resize_label:setClickCallback(&quot;chair_resize_click&quot;)
chair_resize_label:setReleaseCallback(&quot;chair_resize_release&quot;)
chair_drag_move:setClickCallback(&quot;chair_drag_click&quot;)
chair_drag_move:setReleaseCallback(&quot;chair_drag_release&quot;)
chair_container:show()</script>
            <eventHandlerList/>
        </Script>
    </ScriptPackage>
    <KeyPackage/>
</MudletPackage>
