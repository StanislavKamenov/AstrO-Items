# Astro-items
Simple script for create a weapon items and other items for crime

I dont have images just find 

--AstrO--ITEMS--
	["empty_armor"] 		         	 = {["name"] = "empty_armor", 		              	["label"] = "Празна Жилетка", 		        	["weight"] = 100, 		["type"] = "item", 		["image"] = "empty_armor.png", 	            ["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = {accept = {'armor_plates'}, reward = 'armor', anim = {['dict'] = 'anim@amb@business@weed@weed_inspecting_high_dry@', ['lib'] = 'weed_inspecting_high_base_inspector', ['text'] = 'Пълните празната жилетка с плочи', ['timeOut'] = 10000}},   ["description"] = "Нещо интересно ?"},
	["armor_plates"] 		         	 = {["name"] = "armor_plates", 		              	["label"] = "Плочи", 		        	["weight"] = 100, 		["type"] = "item", 		["image"] = "plates.png", 	            ["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil ,   ["description"] = "Плочи за бронежилетка"},
	["empty_bulletspistol"] 		         	 = {["name"] = "empty_bulletspistol", 		              	["label"] = "Празни патрони за пистолет", 		        	["weight"] = 100, 		["type"] = "item", 		["image"] = "empty_bullets.png", 	            ["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = {accept = {'gunpowder'}, reward = 'pistol_ammo', anim = {['dict'] = 'anim@amb@business@weed@weed_inspecting_high_dry@', ['lib'] = 'weed_inspecting_high_base_inspector', ['text'] = 'Пълните патроните с барут', ['timeOut'] = 10000}},   ["description"] = "Дали са изпозлвани ?"},
	["empty_bulletssmg"] 		         	 = {["name"] = "empty_bulletssmg", 		              	["label"] = "Празни патрони за СМГ", 		        	["weight"] = 100, 		["type"] = "item", 		["image"] = "empty_bullets.png", 	            ["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = {accept = {'gunpowder'}, reward = 'smg_ammo', anim = {['dict'] = 'anim@amb@business@weed@weed_inspecting_high_dry@', ['lib'] = 'weed_inspecting_high_base_inspector', ['text'] = 'Пълните патроните с барут', ['timeOut'] = 10000}},   ["description"] = "Дали са изпозлвани ?"},
	["empty_bulletsrifle"] 		         	 = {["name"] = "empty_bulletsrifle", 		              	["label"] = "Празни патрони за Райфъл", 		        	["weight"] = 100, 		["type"] = "item", 		["image"] = "empty_bullets.png", 	            ["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = {accept = {'gunpowder'}, reward = 'rifle_ammo', anim = {['dict'] = 'anim@amb@business@weed@weed_inspecting_high_dry@', ['lib'] = 'weed_inspecting_high_base_inspector', ['text'] = 'Пълните патроните с барут', ['timeOut'] = 10000}},   ["description"] = "Дали са изпозлвани ?"},
	["empty_bulletsshotgun"] 		         	 = {["name"] = "empty_bulletsshotgun", 		              	["label"] = "Празни патрони за Помпа", 		        	["weight"] = 100, 		["type"] = "item", 		["image"] = "empty_bullets.png", 	            ["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = {accept = {'gunpowder'}, reward = 'shotgun_ammo', anim = {['dict'] = 'anim@amb@business@weed@weed_inspecting_high_dry@', ['lib'] = 'weed_inspecting_high_base_inspector', ['text'] = 'Пълните патроните с барут', ['timeOut'] = 10000}},   ["description"] = "Дали са изпозлвани ?"},
	["gunpowder"] 		         	 = {["name"] = "gunpowder", 		              	["label"] = "Барут", 		        	["weight"] = 100, 		["type"] = "item", 		["image"] = "gunpowder.png", 	            ["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil , ["description"] = "Барут за патрони"},
    --WeaponsItems--
	["pistol_body"] 		         	 = {["name"] = "pistol_body", 		              	["label"] = "Тяло на пистолет", 		        	["weight"] = 100, 		["type"] = "item", 		["image"] = "pistol_body.png", 	            ["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil , ["description"] = "Част за оръжие"},
	["pistol_trigger"] 		         	 = {["name"] = "pistol_trigger", 		              	["label"] = "Спусък за пистолет", 		        	["weight"] = 100, 		["type"] = "item", 		["image"] = "pistol_trigger.png", 	            ["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil , ["description"] = "Част за оръжие"},
	["pistol_magazine"] 		         	 = {["name"] = "pistol_magazine", 		              	["label"] = "Пълнител за пистолет", 		        	["weight"] = 100, 		["type"] = "item", 		["image"] = "pistol_magazine.png", 	            ["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil , ["description"] = "Част за оръжие"},
	["pistol_barrel"] 		         	 = {["name"] = "pistol_barrel", 		              	["label"] = "Цев за пистолет", 		        	["weight"] = 100, 		["type"] = "item", 		["image"] = "pistol_barrel.png", 	            ["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil , ["description"] = "Част за оръжие"},
	["pump_body"] 		         	 = {["name"] = "pump_body", 		              	["label"] = "Тяло на помпа", 		        	["weight"] = 100, 		["type"] = "item", 		["image"] = "pump_body.png", 	            ["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil , ["description"] = "Част за оръжие"},
	["pump_trigger"] 		         	 = {["name"] = "pump_trigger", 		              	["label"] = "Спусък за пистолет", 		        	["weight"] = 100, 		["type"] = "item", 		["image"] = "pump_trigger.png", 	            ["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil , ["description"] = "Част за оръжие"},
	["pump_magazine"] 		         	 = {["name"] = "pump_magazine", 		              	["label"] = "Пълнител за помпа", 		        	["weight"] = 100, 		["type"] = "item", 		["image"] = "pump_magazine.png", 	            ["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil , ["description"] = "Част за оръжие"},
	["pump_barrel"] 		         	 = {["name"] = "pump_barrel", 		              	["label"] = "Цев за помпа", 		        	["weight"] = 100, 		["type"] = "item", 		["image"] = "pump_barrel.png", 	            ["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil , ["description"] = "Част за оръжие"},
	["smg_body"] 		         	 = {["name"] = "smg_body", 		              	["label"] = "Тяло на СМГ", 		        	["weight"] = 100, 		["type"] = "item", 		["image"] = "smg_body.png", 	            ["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil , ["description"] = "Част за оръжие"},
	["smg_trigger"] 		         	 = {["name"] = "smg_trigger", 		              	["label"] = "Спусък за СМГ", 		        	["weight"] = 100, 		["type"] = "item", 		["image"] = "smg_trigger.png", 	            ["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil , ["description"] = "Част за оръжие"},
	["smg_magazine"] 		         	 = {["name"] = "smg_magazine", 		              	["label"] = "Пълнител за СМГ", 		        	["weight"] = 100, 		["type"] = "item", 		["image"] = "smg_magazine.png", 	            ["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil , ["description"] = "Част за оръжие"},
	["smg_barrel"] 		         	 = {["name"] = "smg_barrel", 		              	["label"] = "Цев за СМГ", 		        	["weight"] = 100, 		["type"] = "item", 		["image"] = "smg_barrel.png", 	            ["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil , ["description"] = "Част за оръжие"},
	["assault_body"] 		         	 = {["name"] = "assault_body", 		              	["label"] = "Тяло на Райфъл", 		        	["weight"] = 100, 		["type"] = "item", 		["image"] = "assault_body.png", 	            ["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil , ["description"] = "Част за оръжие"},
	["assault_magazine"] 		         	 = {["name"] = "assault_magazine", 		              	["label"] = "Спусък за Райфъл", 		        	["weight"] = 100, 		["type"] = "item", 		["image"] = "assault_magazine.png", 	            ["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil , ["description"] = "Част за оръжие"},
	["assault_barrel"] 		         	 = {["name"] = "assault_barrel", 		              	["label"] = "Пълнител за Райфъл", 		        	["weight"] = 100, 		["type"] = "item", 		["image"] = "assault_barrel.png", 	            ["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil , ["description"] = "Част за оръжие"},
	["assault_trigger"] 		         	 = {["name"] = "assault_trigger", 		              	["label"] = "Цев за Райфъл", 		        	["weight"] = 100, 		["type"] = "item", 		["image"] = "assault_trigger.png", 	            ["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil , ["description"] = "Част за оръжие"},
	--KnifeParts
    ["switchblade_part1"] 		         	 = {["name"] = "switchblade_part1", 		              	["label"] = "Дръжка за нож", 		        	["weight"] = 100, 		["type"] = "item", 		["image"] = "switchpart1.png", 	            ["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = {accept = {'switchblade_part2'}, reward = 'weapon_switchblade', anim = {['dict'] = 'anim@amb@business@weed@weed_inspecting_high_dry@', ['lib'] = 'weed_inspecting_high_base_inspector', ['text'] = 'Сглобявате нож', ['timeOut'] = 10000}} , ["description"] = "Част за нож"},
	["switchblade_part2"] 		         	 = {["name"] = "switchblade_part2", 		              	["label"] = "Острие на нож", 		        	["weight"] = 100, 		["type"] = "item", 		["image"] = "switchpart2.png", 	            ["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,    ["combinable"] = nil , ["description"] = "Част за нож"},
