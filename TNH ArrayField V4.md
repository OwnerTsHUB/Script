--[[
 .____                  ________ ___.    _____                           __                
 |    |    __ _______   \_____  \\_ |___/ ____\_ __  ______ ____ _____ _/  |_  ___________ 
 |    |   |  |  \__  \   /   |   \| __ \   __\  |  \/  ___// ___\\__  \\   __\/  _ \_  __ \
 |    |___|  |  // __ \_/    |    \ \_\ \  | |  |  /\___ \\  \___ / __ \|  | (  <_> )  | \/
 |_______ \____/(____  /\_______  /___  /__| |____//____  >\___  >____  /__|  \____/|__|   
         \/          \/         \/    \/                \/     \/     \/                   
          \_Welcome to LuaObfuscator.com   (Alpha 0.9.14) ~  Much Love, Ferib 

]]--

local v0 = tonumber;
local v1 = string.byte;
local v2 = string.char;
local v3 = string.sub;
local v4 = string.gsub;
local v5 = string.rep;
local v6 = table.concat;
local v7 = table.insert;
local v8 = math.ldexp;
local v9 = getfenv or function()
	return _ENV;
end;
local v10 = setmetatable;
local v11 = pcall;
local v12 = select;
local v13 = unpack or table.unpack;
local v14 = tonumber;
local function v15(v16, v17, ...)
	local v18 = 1;
	local v19;
	v16 = v4(v3(v16, 5), "..", function(v30)
		if (v1(v30, 2) == 79) then
			v19 = v0(v3(v30, 1, 1));
			return "";
		else
			local v84 = v2(v0(v30, 16));
			if v19 then
				local v90 = v5(v84, v19);
				v19 = nil;
				return v90;
			else
				return v84;
			end
		end
	end);
	local function v20(v31, v32, v33)
		if v33 then
			local v85 = (v31 / ((5 - 3) ^ (v32 - (1 + 0)))) % ((5 - 3) ^ (((v33 - ((118 - (32 + 85)) - (0 + 0))) - (v32 - (1638 - (1523 + 114)))) + 1 + 0 + 0));
			return v85 - (v85 % (2 - 1));
		else
			local v86 = (621 - ((1512 - (892 + 65)) + 64)) ^ (v32 - (1271 - ((538 - 312) + 1044)));
			return (((v31 % (v86 + v86)) >= v86) and (932 - (857 + 74))) or (568 - (367 + 201));
		end
	end
	local function v21()
		local v34 = 0 - 0;
		local v35;
		while true do
			if (v34 == 1) then
				return v35;
			end
			if (v34 == (0 - 0)) then
				v35 = v1(v16, v18, v18);
				v18 = v18 + ((258 + 93) - (87 + 263));
				v34 = 181 - (67 + 113);
			end
		end
	end
	local function v22()
		local v36 = 0 - 0;
		local v37;
		local v38;
		while true do
			if (v36 == (1 + 0)) then
				return (v38 * (1017 - 761)) + v37;
			end
			if (v36 == 0) then
				v37, v38 = v1(v16, v18, v18 + (954 - (802 + 110 + 40)));
				v18 = v18 + ((1002 - (915 + 82)) - 3);
				v36 = 1 - 0;
			end
		end
	end
	local function v23()
		local v39, v40, v41, v42 = v1(v16, v18, v18 + (8 - 5));
		v18 = v18 + 3 + 1;
		return (v42 * ((50057818 - 27993388) - 5287214)) + (v41 * (66723 - ((2337 - 1268) + 118))) + (v40 * 256) + v39;
	end
	local function v24()
		local v43 = v23();
		local v44 = v23();
		local v45 = (3 - 2) + 0;
		local v46 = (v20(v44, 1, 1158 - (116 + 1022)) * ((3 - 1) ^ (32 + 0))) + v43;
		local v47 = v20(v44, 21, 822 - (368 + 423));
		local v48 = ((v20(v44, 100 - (241 - 173)) == ((78 - 59) - (10 + (867 - (814 + 45))))) and -(3 - 2)) or (443 - (416 + 26));
		if (v47 == 0) then
			if (v46 == (0 - 0)) then
				return v48 * (0 + 0);
			else
				v47 = 1 - 0;
				v45 = 0;
			end
		elseif (v47 == (2485 - (145 + 293))) then
			return ((v46 == (430 - (44 + 386))) and (v48 * ((1487 - (998 + 488)) / (0 + 0)))) or (v48 * NaN);
		end
		return v8(v48, v47 - ((2064 - 1226) + 185)) * (v45 + (v46 / (2 ^ (824 - (201 + 336 + 235)))));
	end
	local function v25(v49)
		local v50;
		if not v49 then
			local v87 = 0 - 0;
			while true do
				if (v87 == (0 + 0)) then
					v49 = v23();
					if (v49 == (0 - 0)) then
						return "";
					end
					break;
				end
			end
		end
		v50 = v3(v16, v18, (v18 + v49) - (1 + 0));
		v18 = v18 + v49;
		local v51 = {};
		for v68 = 886 - (261 + (2954 - 2330)), #v50 do
			v51[v68] = v2(v1(v3(v50, v68, v68)));
		end
		return v6(v51);
	end
	local v26 = v23;
	local function v27(...)
		return {...}, v12("#", ...);
	end
	local function v28()
		local v52 = 0 - 0;
		local v53;
		local v54;
		local v55;
		local v56;
		local v57;
		local v58;
		local v59;
		local v60;
		local v61;
		while true do
			if (v52 ~= 0) then
			else
				v53 = 238 - (64 + 174);
				v54 = nil;
				v52 = 1;
			end
			if (v52 == (1 + 1)) then
				v57 = nil;
				v58 = nil;
				v52 = 3;
			end
			if (v52 == 3) then
				v59 = nil;
				v60 = nil;
				v52 = 4;
			end
			if (v52 == 4) then
				v61 = nil;
				while true do
					if (v53 ~= (3 - 0)) then
					else
						local v97 = 336 - (144 + 192);
						while true do
							if ((217 - (42 + 174)) == v97) then
								v53 = 4 + 0;
								break;
							end
							if ((0 + 0) ~= v97) then
							else
								v60 = nil;
								v61 = nil;
								v97 = 1 + 0;
							end
						end
					end
					if (v53 ~= 2) then
					else
						local v98 = 1504 - (363 + 1141);
						while true do
							if (v98 == 1) then
								v53 = 3;
								break;
							end
							if ((1580 - (1183 + 397)) ~= v98) then
							else
								v58 = nil;
								v59 = nil;
								v98 = 1;
							end
						end
					end
					if (v53 ~= (0 - 0)) then
					else
						local v99 = 0;
						while true do
							if (0 ~= v99) then
							else
								v54 = 0 + 0;
								v55 = nil;
								v99 = 1 + 0;
							end
							if (1 == v99) then
								v53 = 1;
								break;
							end
						end
					end
					if (v53 ~= 4) then
					else
						while true do
							if (v54 == 3) then
								v61 = nil;
								while true do
									local v104 = 1975 - (1913 + 62);
									local v105;
									local v106;
									while true do
										if (v104 == (1 + 0)) then
											while true do
												if ((0 - 0) == v105) then
													v106 = 1933 - (565 + 1368);
													while true do
														if (v106 ~= (0 - 0)) then
														else
															local v206 = 0;
															while true do
																if (v206 == 1) then
																	v106 = 1;
																	break;
																end
																if (v206 ~= (1661 - (1477 + 184))) then
																else
																	if (v55 ~= 2) then
																	else
																		local v216 = 0;
																		local v217;
																		local v218;
																		while true do
																			if (v216 ~= (1 - 0)) then
																			else
																				while true do
																					if (v217 == (0 + 0)) then
																						v218 = 856 - (564 + 292);
																						while true do
																							if ((0 - 0) ~= v218) then
																							else
																								local v225 = 0;
																								while true do
																									if (v225 ~= (0 - 0)) then
																									else
																										local v234 = 0;
																										while true do
																											if (v234 ~= 0) then
																											else
																												for v238 = 1, v60 do
																													local v239 = 0;
																													local v240;
																													local v241;
																													local v242;
																													local v243;
																													local v244;
																													while true do
																														if (v239 == (304 - (244 + 60))) then
																															v240 = 0 + 0;
																															v241 = nil;
																															v239 = 1;
																														end
																														if (v239 == (477 - (41 + 435))) then
																															v242 = nil;
																															v243 = nil;
																															v239 = 2;
																														end
																														if (v239 == 2) then
																															v244 = nil;
																															while true do
																																if (0 == v240) then
																																	local v247 = 1001 - (938 + 63);
																																	while true do
																																		if (v247 == 0) then
																																			v241 = 0;
																																			v242 = nil;
																																			v247 = 1;
																																		end
																																		if (v247 == (1 + 0)) then
																																			v240 = 1126 - (936 + 189);
																																			break;
																																		end
																																	end
																																end
																																if (v240 == 1) then
																																	local v248 = 0 + 0;
																																	while true do
																																		if (v248 ~= (1613 - (1565 + 48))) then
																																		else
																																			v243 = nil;
																																			v244 = nil;
																																			v248 = 1;
																																		end
																																		if (v248 ~= 1) then
																																		else
																																			v240 = 2;
																																			break;
																																		end
																																	end
																																end
																																if (v240 == (2 + 0)) then
																																	while true do
																																		if (v241 == 0) then
																																			local v255 = 0;
																																			while true do
																																				if (v255 == 1) then
																																					v241 = 1;
																																					break;
																																				end
																																				if (0 == v255) then
																																					v242 = 1138 - (782 + 356);
																																					v243 = nil;
																																					v255 = 268 - (176 + 91);
																																				end
																																			end
																																		end
																																		if (1 == v241) then
																																			v244 = nil;
																																			while true do
																																				if (v242 == (2 - 1)) then
																																					if (v243 == 1) then
																																						v244 = v21() ~= 0;
																																					elseif (v243 == (2 - 0)) then
																																						v244 = v24();
																																					elseif (v243 ~= 3) then
																																					else
																																						v244 = v25();
																																					end
																																					v61[v238] = v244;
																																					break;
																																				end
																																				if (v242 == 0) then
																																					local v259 = 1092 - (975 + 117);
																																					local v260;
																																					local v261;
																																					while true do
																																						if (v259 ~= (1875 - (157 + 1718))) then
																																						else
																																							v260 = 0 + 0;
																																							v261 = nil;
																																							v259 = 3 - 2;
																																						end
																																						if (v259 == (3 - 2)) then
																																							while true do
																																								if (v260 == (1018 - (697 + 321))) then
																																									v261 = 0 - 0;
																																									while true do
																																										if (v261 == (1 - 0)) then
																																											v242 = 1;
																																											break;
																																										end
																																										if ((0 - 0) == v261) then
																																											v243 = v21();
																																											v244 = nil;
																																											v261 = 1 + 0;
																																										end
																																									end
																																									break;
																																								end
																																							end
																																							break;
																																						end
																																					end
																																				end
																																			end
																																			break;
																																		end
																																	end
																																	break;
																																end
																															end
																															break;
																														end
																													end
																												end
																												v59[5 - 2] = v21();
																												v234 = 2 - 1;
																											end
																											if (v234 ~= 1) then
																											else
																												v225 = 1228 - (322 + 905);
																												break;
																											end
																										end
																									end
																									if (v225 == 1) then
																										v218 = 612 - (602 + 9);
																										break;
																									end
																								end
																							end
																							if (v218 ~= (1190 - (449 + 740))) then
																							else
																								for v228 = 1, v23() do
																									local v229 = 872 - (826 + 46);
																									local v230;
																									local v231;
																									local v232;
																									local v233;
																									while true do
																										if ((947 - (245 + 702)) ~= v229) then
																										else
																											v230 = 0;
																											v231 = nil;
																											v229 = 3 - 2;
																										end
																										if (v229 == 2) then
																											while true do
																												if (v230 ~= 0) then
																												else
																													local v245 = 0 + 0;
																													while true do
																														if (v245 == (1899 - (260 + 1638))) then
																															v230 = 1;
																															break;
																														end
																														if (v245 ~= (440 - (382 + 58))) then
																														else
																															v231 = 0 - 0;
																															v232 = nil;
																															v245 = 1 + 0;
																														end
																													end
																												end
																												if (v230 ~= (1 - 0)) then
																												else
																													v233 = nil;
																													while true do
																														if (v231 ~= 0) then
																														else
																															local v246 = 0;
																															while true do
																																if (v246 ~= (0 - 0)) then
																																else
																																	v232 = 1205 - (902 + 303);
																																	v233 = nil;
																																	v246 = 1 - 0;
																																end
																																if (v246 ~= (2 - 1)) then
																																else
																																	v231 = 1 + 0;
																																	break;
																																end
																															end
																														end
																														if (v231 == (1691 - (1121 + 569))) then
																															while true do
																																if (v232 ~= 0) then
																																else
																																	v233 = v21();
																																	if (v20(v233, 1, 1) ~= (214 - (22 + 192))) then
																																	else
																																		local v249 = 683 - (483 + 200);
																																		local v250;
																																		local v251;
																																		local v252;
																																		local v253;
																																		local v254;
																																		while true do
																																			if (0 ~= v249) then
																																			else
																																				local v256 = 1463 - (1404 + 59);
																																				while true do
																																					if (v256 ~= (2 - 1)) then
																																					else
																																						v249 = 1 - 0;
																																						break;
																																					end
																																					if (v256 ~= (765 - (468 + 297))) then
																																					else
																																						v250 = 562 - (334 + 228);
																																						v251 = nil;
																																						v256 = 1;
																																					end
																																				end
																																			end
																																			if (v249 == (6 - 4)) then
																																				v254 = nil;
																																				while true do
																																					if (v250 ~= (4 - 2)) then
																																					else
																																						while true do
																																							if (v251 ~= (2 - 0)) then
																																							else
																																								local v265 = 0 + 0;
																																								local v266;
																																								while true do
																																									if (v265 == (236 - (141 + 95))) then
																																										v266 = 0;
																																										while true do
																																											if (v266 == (1 + 0)) then
																																												v251 = 7 - 4;
																																												break;
																																											end
																																											if (v266 ~= (0 - 0)) then
																																											else
																																												local v274 = 0;
																																												local v275;
																																												while true do
																																													if (v274 ~= (0 + 0)) then
																																													else
																																														v275 = 0 - 0;
																																														while true do
																																															if (v275 ~= (1 + 0)) then
																																															else
																																																v266 = 1 + 0;
																																																break;
																																															end
																																															if (v275 ~= (0 - 0)) then
																																															else
																																																if (v20(v253, 1 + 0, 164 - (92 + 71)) == 1) then
																																																	v254[2] = v61[v254[2]];
																																																end
																																																if (v20(v253, 2, 1 + 1) ~= (1 - 0)) then
																																																else
																																																	v254[3] = v61[v254[3]];
																																																end
																																																v275 = 766 - (574 + 191);
																																															end
																																														end
																																														break;
																																													end
																																												end
																																											end
																																										end
																																										break;
																																									end
																																								end
																																							end
																																							if (v251 ~= (0 + 0)) then
																																							else
																																								local v267 = 0 - 0;
																																								local v268;
																																								while true do
																																									if (v267 ~= (0 + 0)) then
																																									else
																																										v268 = 849 - (254 + 595);
																																										while true do
																																											if (v268 == (127 - (55 + 71))) then
																																												v251 = 1;
																																												break;
																																											end
																																											if (v268 == 0) then
																																												local v276 = 0;
																																												local v277;
																																												while true do
																																													if (v276 ~= (0 - 0)) then
																																													else
																																														v277 = 0;
																																														while true do
																																															if (v277 ~= 0) then
																																															else
																																																local v282 = 1790 - (573 + 1217);
																																																while true do
																																																	if (v282 ~= (2 - 1)) then
																																																	else
																																																		v277 = 1;
																																																		break;
																																																	end
																																																	if (v282 ~= 0) then
																																																	else
																																																		v252 = v20(v233, 1 + 1, 4 - 1);
																																																		v253 = v20(v233, 943 - (714 + 225), 17 - 11);
																																																		v282 = 1;
																																																	end
																																																end
																																															end
																																															if (v277 == (1 - 0)) then
																																																v268 = 1;
																																																break;
																																															end
																																														end
																																														break;
																																													end
																																												end
																																											end
																																										end
																																										break;
																																									end
																																								end
																																							end
																																							if (3 ~= v251) then
																																							else
																																								if (v20(v253, 1 + 2, 3) ~= 1) then
																																								else
																																									v254[4] = v61[v254[4]];
																																								end
																																								v56[v228] = v254;
																																								break;
																																							end
																																							if (v251 == (1 - 0)) then
																																								local v270 = 806 - (118 + 688);
																																								local v271;
																																								while true do
																																									if (0 == v270) then
																																										v271 = 0;
																																										while true do
																																											if (v271 ~= 0) then
																																											else
																																												local v278 = 0;
																																												while true do
																																													if (0 ~= v278) then
																																													else
																																														v254 = {v22(),v22(),nil,nil};
																																														if (v252 == 0) then
																																															local v279 = 0 - 0;
																																															local v280;
																																															local v281;
																																															while true do
																																																if (v279 ~= 0) then
																																																else
																																																	v280 = 0;
																																																	v281 = nil;
																																																	v279 = 733 - (16 + 716);
																																																end
																																																if (v279 == 1) then
																																																	while true do
																																																		if (v280 == (0 - 0)) then
																																																			v281 = 97 - (11 + 86);
																																																			while true do
																																																				if (v281 ~= (0 - 0)) then
																																																				else
																																																					v254[3] = v22();
																																																					v254[4] = v22();
																																																					break;
																																																				end
																																																			end
																																																			break;
																																																		end
																																																	end
																																																	break;
																																																end
																																															end
																																														elseif (v252 == 1) then
																																															v254[288 - (175 + 110)] = v23();
																																														elseif (v252 == 2) then
																																															v254[6 - 3] = v23() - ((9 - 7) ^ 16);
																																														elseif (v252 ~= (1799 - (503 + 1293))) then
																																														else
																																															local v289 = 0 - 0;
																																															local v290;
																																															local v291;
																																															while true do
																																																if (v289 == 1) then
																																																	while true do
																																																		if (v290 == 0) then
																																																			v291 = 0 + 0;
																																																			while true do
																																																				if (v291 ~= (1061 - (810 + 251))) then
																																																				else
																																																					v254[3 + 0] = v23() - (2 ^ (5 + 11));
																																																					v254[4 + 0] = v22();
																																																					break;
																																																				end
																																																			end
																																																			break;
																																																		end
																																																	end
																																																	break;
																																																end
																																																if (v289 == 0) then
																																																	v290 = 0;
																																																	v291 = nil;
																																																	v289 = 534 - (43 + 490);
																																																end
																																															end
																																														end
																																														v278 = 1;
																																													end
																																													if (v278 == (734 - (711 + 22))) then
																																														v271 = 3 - 2;
																																														break;
																																													end
																																												end
																																											end
																																											if (v271 == (860 - (240 + 619))) then
																																												v251 = 1 + 1;
																																												break;
																																											end
																																										end
																																										break;
																																									end
																																								end
																																							end
																																						end
																																						break;
																																					end
																																					if (v250 ~= 1) then
																																					else
																																						local v262 = 0;
																																						local v263;
																																						while true do
																																							if (v262 ~= 0) then
																																							else
																																								v263 = 0 - 0;
																																								while true do
																																									if (v263 == (1 + 0)) then
																																										v250 = 1746 - (1344 + 400);
																																										break;
																																									end
																																									if (v263 == (405 - (255 + 150))) then
																																										v253 = nil;
																																										v254 = nil;
																																										v263 = 1 + 0;
																																									end
																																								end
																																								break;
																																							end
																																						end
																																					end
																																					if (v250 == 0) then
																																						local v264 = 0 + 0;
																																						while true do
																																							if (v264 ~= 0) then
																																							else
																																								v251 = 0 - 0;
																																								v252 = nil;
																																								v264 = 1;
																																							end
																																							if (v264 ~= 1) then
																																							else
																																								v250 = 1;
																																								break;
																																							end
																																						end
																																					end
																																				end
																																				break;
																																			end
																																			if (1 == v249) then
																																				local v257 = 0 - 0;
																																				while true do
																																					if (1 == v257) then
																																						v249 = 2;
																																						break;
																																					end
																																					if (v257 == (1739 - (404 + 1335))) then
																																						v252 = nil;
																																						v253 = nil;
																																						v257 = 407 - (183 + 223);
																																					end
																																				end
																																			end
																																		end
																																	end
																																	break;
																																end
																															end
																															break;
																														end
																													end
																													break;
																												end
																											end
																											break;
																										end
																										if (v229 ~= (1 - 0)) then
																										else
																											v232 = nil;
																											v233 = nil;
																											v229 = 2 + 0;
																										end
																									end
																								end
																								v55 = 3;
																								break;
																							end
																						end
																						break;
																					end
																				end
																				break;
																			end
																			if (v216 ~= 0) then
																			else
																				v217 = 0;
																				v218 = nil;
																				v216 = 1;
																			end
																		end
																	end
																	if ((2 + 1) ~= v55) then
																	else
																		local v219 = 337 - (10 + 327);
																		local v220;
																		local v221;
																		while true do
																			if (v219 ~= 0) then
																			else
																				v220 = 0;
																				v221 = nil;
																				v219 = 1 + 0;
																			end
																			if (v219 == (339 - (118 + 220))) then
																				while true do
																					if ((0 + 0) == v220) then
																						v221 = 449 - (108 + 341);
																						while true do
																							if (v221 ~= (0 + 0)) then
																							else
																								local v226 = 0;
																								while true do
																									if (v226 == 0) then
																										for v235 = 4 - 3, v23() do
																											v57[v235 - 1] = v28();
																										end
																										return v59;
																									end
																								end
																							end
																						end
																						break;
																					end
																				end
																				break;
																			end
																		end
																	end
																	v206 = 1;
																end
															end
														end
														if (v106 == (1494 - (711 + 782))) then
															if (v55 ~= 1) then
															else
																local v212 = 0 - 0;
																while true do
																	if (v212 ~= (469 - (270 + 199))) then
																	else
																		local v222 = 0;
																		local v223;
																		while true do
																			if (v222 == (0 + 0)) then
																				v223 = 1819 - (580 + 1239);
																				while true do
																					if ((2 - 1) ~= v223) then
																					else
																						v212 = 1;
																						break;
																					end
																					if (v223 == 0) then
																						v59 = {v56,v57,nil,v58};
																						v60 = v23();
																						v223 = 2 - 1;
																					end
																				end
																				break;
																			end
																		end
																	end
																	if (1 == v212) then
																		v61 = {};
																		v55 = 2;
																		break;
																	end
																end
															end
															if (v55 ~= 0) then
															else
																local v213 = 0 + 0;
																local v214;
																local v215;
																while true do
																	if (v213 ~= 1) then
																	else
																		while true do
																			if (v214 ~= (1167 - (645 + 522))) then
																			else
																				v215 = 0;
																				while true do
																					if ((1790 - (1010 + 780)) == v215) then
																						local v224 = 0 + 0;
																						while true do
																							if (v224 == (0 - 0)) then
																								local v227 = 0;
																								while true do
																									if (v227 == (0 - 0)) then
																										v56 = {};
																										v57 = {};
																										v227 = 1;
																									end
																									if (v227 ~= 1) then
																									else
																										v224 = 1837 - (1045 + 791);
																										break;
																									end
																								end
																							end
																							if (1 ~= v224) then
																							else
																								v215 = 1;
																								break;
																							end
																						end
																					end
																					if (v215 == (2 - 1)) then
																						v58 = {};
																						v55 = 1 - 0;
																						break;
																					end
																				end
																				break;
																			end
																		end
																		break;
																	end
																	if (v213 ~= (505 - (351 + 154))) then
																	else
																		v214 = 0;
																		v215 = nil;
																		v213 = 1;
																	end
																end
															end
															break;
														end
													end
													break;
												end
											end
											break;
										end
										if ((1574 - (1281 + 293)) == v104) then
											v105 = 266 - (28 + 238);
											v106 = nil;
											v104 = 2 - 1;
										end
									end
								end
								break;
							end
							if (v54 ~= (1560 - (1381 + 178))) then
							else
								local v101 = 0;
								while true do
									if (v101 == 1) then
										v54 = 2;
										break;
									end
									if (v101 ~= 0) then
									else
										local v107 = 0;
										while true do
											if (1 == v107) then
												v101 = 1;
												break;
											end
											if (v107 ~= (0 + 0)) then
											else
												v57 = nil;
												v58 = nil;
												v107 = 1;
											end
										end
									end
								end
							end
							if (2 ~= v54) then
							else
								local v102 = 0 + 0;
								while true do
									if (v102 ~= (1 + 0)) then
									else
										v54 = 3;
										break;
									end
									if (v102 ~= 0) then
									else
										v59 = nil;
										v60 = nil;
										v102 = 1;
									end
								end
							end
							if (0 ~= v54) then
							else
								local v103 = 0;
								while true do
									if (v103 ~= 0) then
									else
										v55 = 0 - 0;
										v56 = nil;
										v103 = 1;
									end
									if (v103 == 1) then
										v54 = 1;
										break;
									end
								end
							end
						end
						break;
					end
					if (1 == v53) then
						local v100 = 0 + 0;
						while true do
							if (v100 == (470 - (381 + 89))) then
								v56 = nil;
								v57 = nil;
								v100 = 1 + 0;
							end
							if (v100 ~= (1 + 0)) then
							else
								v53 = 2 - 0;
								break;
							end
						end
					end
				end
				break;
			end
			if ((1157 - (1074 + 82)) == v52) then
				v55 = nil;
				v56 = nil;
				v52 = 2;
			end
		end
	end
	local function v29(v62, v63, v64)
		local v65 = v62[1];
		local v66 = v62[2];
		local v67 = v62[3];
		return function(...)
			local v70 = v65;
			local v71 = v66;
			local v72 = v67;
			local v73 = v27;
			local v74 = 1;
			local v75 = -1;
			local v76 = {};
			local v77 = {...};
			local v78 = v12("#", ...) - 1;
			local v79 = {};
			local v80 = {};
			for v88 = 0, v78 do
				if (v88 >= v72) then
					v76[v88 - v72] = v77[v88 + 1];
				else
					v80[v88] = v77[v88 + 1];
				end
			end
			local v81 = (v78 - v72) + 1;
			local v82;
			local v83;
			while true do
				local v89 = 0;
				while true do
					if (v89 == 0) then
						v82 = v70[v74];
						v83 = v82[1];
						v89 = 1;
					end
					if (v89 == 1) then
						if (v83 <= 18) then
							if (v83 <= 8) then
								if (v83 <= 3) then
									if (v83 <= 1) then
										if (v83 == 0) then
											local v108 = v82[2];
											v80[v108] = v80[v108](v13(v80, v108 + 1, v75));
										else
											local v110 = v82[2];
											local v111 = v80[v82[3]];
											v80[v110 + 1] = v111;
											v80[v110] = v111[v82[4]];
										end
									elseif (v83 > 2) then
										local v115 = v82[2];
										v80[v115] = v80[v115]();
									else
										local v117 = v82[2];
										v80[v117](v80[v117 + 1]);
									end
								elseif (v83 <= 5) then
									if (v83 == 4) then
										local v118 = v82[2];
										local v119 = v80[v82[3]];
										v80[v118 + 1] = v119;
										v80[v118] = v119[v82[4]];
									else
										v80[v82[2]] = v80[v82[3]][v82[4]];
									end
								elseif (v83 <= 6) then
									local v125 = v82[2];
									v80[v125] = v80[v125](v13(v80, v125 + 1, v82[3]));
								elseif (v83 > 7) then
									v80[v82[2]]();
								else
									do
										return;
									end
								end
							elseif (v83 <= 13) then
								if (v83 <= 10) then
									if (v83 > 9) then
										do
											return;
										end
									else
										local v127 = 0;
										local v128;
										while true do
											if (v127 == 0) then
												v128 = v82[2];
												v80[v128] = v80[v128]();
												break;
											end
										end
									end
								elseif (v83 <= 11) then
									v80[v82[2]] = v82[3];
								elseif (v83 > 12) then
									local v168 = v82[2];
									local v169 = v80[v168];
									local v170 = v82[3];
									for v194 = 1, v170 do
										v169[v194] = v80[v168 + v194];
									end
								else
									local v171 = v82[2];
									local v172, v173 = v73(v80[v171](v13(v80, v171 + 1, v82[3])));
									v75 = (v173 + v171) - 1;
									local v174 = 0;
									for v197 = v171, v75 do
										v174 = v174 + 1;
										v80[v197] = v172[v174];
									end
								end
							elseif (v83 <= 15) then
								if (v83 > 14) then
									v80[v82[2]] = v80[v82[3]][v82[4]];
								else
									local v133 = v82[2];
									v80[v133] = v80[v133](v13(v80, v133 + 1, v82[3]));
								end
							elseif (v83 <= 16) then
								local v135 = 0;
								local v136;
								local v137;
								local v138;
								local v139;
								while true do
									if (v135 == 1) then
										v75 = (v138 + v136) - 1;
										v139 = 0;
										v135 = 2;
									end
									if (v135 == 0) then
										v136 = v82[2];
										v137, v138 = v73(v80[v136](v13(v80, v136 + 1, v82[3])));
										v135 = 1;
									end
									if (v135 == 2) then
										for v207 = v136, v75 do
											v139 = v139 + 1;
											v80[v207] = v137[v139];
										end
										break;
									end
								end
							elseif (v83 > 17) then
								local v175 = v82[2];
								v80[v175](v80[v175 + 1]);
							else
								local v176 = 0;
								local v177;
								while true do
									if (v176 == 0) then
										v177 = v82[2];
										v80[v177] = v80[v177](v13(v80, v177 + 1, v75));
										break;
									end
								end
							end
						elseif (v83 <= 28) then
							if (v83 <= 23) then
								if (v83 <= 20) then
									if (v83 > 19) then
										v80[v82[2]] = v64[v82[3]];
									else
										local v142 = 0;
										local v143;
										while true do
											if (v142 == 0) then
												v143 = v82[2];
												v80[v143](v13(v80, v143 + 1, v82[3]));
												break;
											end
										end
									end
								elseif (v83 <= 21) then
									local v144 = v82[2];
									local v145 = v80[v144];
									local v146 = v82[3];
									for v162 = 1, v146 do
										v145[v162] = v80[v144 + v162];
									end
								elseif (v83 == 22) then
									v80[v82[2]] = v82[3] ~= 0;
								else
									v80[v82[2]][v82[3]] = v80[v82[4]];
								end
							elseif (v83 <= 25) then
								if (v83 > 24) then
									v80[v82[2]] = v82[3];
								else
									v80[v82[2]] = v64[v82[3]];
								end
							elseif (v83 <= 26) then
								v80[v82[2]] = {};
							elseif (v83 == 27) then
								local v181 = v82[2];
								v80[v181](v13(v80, v181 + 1, v82[3]));
							else
								v80[v82[2]] = v29(v71[v82[3]], nil, v64);
							end
						elseif (v83 <= 33) then
							if (v83 <= 30) then
								if (v83 > 29) then
									v80[v82[2]][v82[3]] = v82[4];
								else
									v80[v82[2]]();
								end
							elseif (v83 <= 31) then
								v80[v82[2]] = {};
							elseif (v83 == 32) then
								v80[v82[2]] = v82[3] ~= 0;
							else
								local v184 = v82[2];
								local v185 = v80[v184];
								for v202 = v184 + 1, v82[3] do
									v7(v185, v80[v202]);
								end
							end
						elseif (v83 <= 35) then
							if (v83 == 34) then
								v80[v82[2]][v82[3]] = v82[4];
							else
								v80[v82[2]] = v29(v71[v82[3]], nil, v64);
							end
						elseif (v83 <= 36) then
							local v158 = v82[2];
							local v159, v160 = v73(v80[v158](v80[v158 + 1]));
							v75 = (v160 + v158) - 1;
							local v161 = 0;
							for v165 = v158, v75 do
								v161 = v161 + 1;
								v80[v165] = v159[v161];
							end
						elseif (v83 == 37) then
							local v186 = v82[2];
							local v187, v188 = v73(v80[v186](v80[v186 + 1]));
							v75 = (v188 + v186) - 1;
							local v189 = 0;
							for v203 = v186, v75 do
								v189 = v189 + 1;
								v80[v203] = v187[v189];
							end
						else
							v80[v82[2]][v82[3]] = v80[v82[4]];
						end
						v74 = v74 + 1;
						break;
					end
				end
			end
		end;
	end
	return v29(v28(), {}, v17)(...);
end
v15("LOL!5C3O00030A3O006C6F6164737472696E6703043O0067616D6503073O00482O747047657403493O00682O7470733A2O2F7261772E67697468756275736572636F6E74656E742E636F6D2F55492D496E746572666163652F412O7261794669656C642F6D61696E2F536F757263652E6C7561030C3O0043726561746557696E646F7703043O004E616D65030E3O00546F62792773204E657720487562030C3O004C6F6164696E675469746C652O033O00544E48030F3O004C6F6164696E675375627469746C6503073O00627920546F627903133O00436F6E66696775726174696F6E536176696E6703073O00456E61626C65642O01030A3O00466F6C6465724E616D650003083O0046696C654E616D6503073O00446973636F7264010003063O00496E76697465030C3O006E6F696E766974656C696E6B030D3O0052656D656D6265724A6F696E7303093O004B657953797374656D030B3O004B657953652O74696E677303053O005469746C6503083O00556E7469746C656403083O005375627469746C65030A3O004B65792053797374656D03043O004E6F7465032A3O004E6F206D6574686F64206F66206F627461696E696E6720746865206B65792069732070726F76696465642O033O004B657903073O00536176654B6579030F3O00477261624B657946726F6D5369746503073O00416374696F6E73026O00F03F03043O005465787403233O00436C69636B206865726520746F20636F707920746865206B6579206C696E6B203C2O2D03073O004F6E5072652O7303053O0048652O6C6F03063O004E6F7469667903103O00596F75277265205573696E6720544E4803073O00436F6E74656E74034O0003083O004475726174696F6E026O001A4003053O00496D616765022O009815FA34064203063O0049676E6F726503053O00457069632103083O0043612O6C6261636B03093O00437265617465546162030E3O0044656661756C7420536372697074030C3O0043726561746542752O746F6E030D3O00496E66696E697465204A756D70030C3O00437265617465536C6964657203103O0057616C6B53702O656420536C6964657203053O0052616E6765028O00026O00794003093O00496E6372656D656E7403063O0053752O66697803053O0053702O6564030C3O0043752O72656E7456616C7565026O00304003043O00466C616703073O00536C6964657231030C3O0047616D6520536372697074732O033O002O4D3203183O004578706C6F736976652057612O6C2053696D756C61746F7203073O00446120482O6F64030C3O00432O6F6B2042757267657273030A3O0042722O6F6B686176656E03133O0055464F2053696D756C61746F7220284B657929031A3O0053616E73204D756C746976657273616C2042612O746C65732032030F3O004A61696C627265616B20284B65792903163O00456174696E672053696D756C61746F7220284B65792903133O005468652052616B652052656D61737465726564030B3O00426C6F7820467275697473030B3O0053702O65642052756E2034030B3O0046756E205363726970747303073O004461726B487562030E3O00496E66696E697465205969656C64030B3O00476967614368616448756203073O004F776C2048756203083O004D2O6F6E2076313303083O00526F73652048756203093O0041646D696E2048756203043O005648756203063O00457A20487562030C3O00526F2D58706C6F697420763603083O00436F636F2048756203083O004F7263612048756200EB3O0012183O00013O001218000100023O002004000100010003001219000300044O000C000100039O0000022O00033O0001000200200400013O00052O001F00033O000700301E00030006000700301E00030008000900301E0003000A000B2O001F00043O000300301E0004000D000E00301E0004000F001000301E0004001100090010170003000C00042O001F00043O000300301E0004000D001300301E00040014001500301E00040016000E00101700030012000400301E0003001700132O001F00043O000800301E00040019001A00301E0004001B001C00301E0004001D001E00301E00040011001F00301E00040020000E00301E0004002100132O001F00053O00012O001F00063O000200301E00060024002500022300075O0010170006002600070010170005002300060010170004002200052O001F000500013O001219000600274O000D0005000100010010170004001F00050010170003001800042O000600010003000200200400023O00282O001F00043O000500301E00040019002900301E0004002A002B00301E0004002C002D00301E0004002E002F2O001F00053O00012O001F00063O000200301E000600060031000223000700013O0010170006003200070010170005003000060010170004002200052O001B000200040001002004000200010033001219000400343O0012190005002F4O00060002000500020020040003000200352O001F00053O000200301E000500060036000223000600023O0010170005003200062O00060003000500020020040004000200372O001F00063O000700301E0006000600382O001F000700023O0012190008003A3O0012190009003B4O000D00070002000100101700060039000700301E0006003C002300301E0006003D003E00301E0006003F004000301E000600410042000223000700033O0010170006003200072O0006000400060002002004000500010033001219000700433O0012190008002F4O00060005000800020020040006000500352O001F00083O000200301E000800060044000223000900043O0010170008003200092O00060006000800020020040007000500352O001F00093O000200301E000900060045000223000A00053O00101700090032000A2O00060007000900020020040008000500352O001F000A3O000200301E000A00060046000223000B00063O001017000A0032000B2O00060008000A00020020040009000500352O001F000B3O000200301E000B00060047000223000C00073O001017000B0032000C2O00060009000B0002002004000A000500352O001F000C3O000200301E000C00060048000223000D00083O001017000C0032000D2O0006000A000C0002002004000B000500352O001F000D3O000200301E000D00060049000223000E00093O001017000D0032000E2O0006000B000D0002002004000C000500352O001F000E3O000200301E000E0006004A000223000F000A3O001017000E0032000F2O0006000C000E0002002004000D000500352O001F000F3O000200301E000F0006004B0002230010000B3O001017000F003200102O0006000D000F0002002004000E000500352O001F00103O000200301E00100006004C0002230011000C3O0010170010003200112O0006000E00100002002004000F000500352O001F00113O000200301E00110006004D0002230012000D3O0010170011003200122O0006000F001100020020040010000500352O001F00123O000200301E00120006004E0002230013000E3O0010170012003200132O00060010001200020020040011000500352O001F00133O000200301E00130006004F0002230014000F3O0010170013003200142O0006001100130002002004001200010033001219001400503O0012190015002F4O00060012001500020020040013001200352O001F00153O000200301E001500060051000223001600103O0010170015003200162O00060013001500020020040014001200352O001F00163O000200301E001600060052000223001700113O0010170016003200172O00060014001600020020040015001200352O001F00173O000200301E001700060053000223001800123O0010170017003200182O00060015001700020020040016001200352O001F00183O000200301E001800060054000223001900133O0010170018003200192O00060016001800020020040017001200352O001F00193O000200301E001900060055000223001A00143O00101700190032001A2O00060017001900020020040018001200352O001F001A3O000200301E001A00060056000223001B00153O001017001A0032001B2O00060018001A00020020040019001200352O001F001B3O000200301E001B00060057000223001C00163O001017001B0032001C2O00060019001B0002002004001A001200352O001F001C3O000200301E001C00060058000223001D00173O001017001C0032001D2O0006001A001C0002002004001B001200352O001F001D3O000200301E001D00060059000223001E00183O001017001D0032001E2O0006001B001D0002002004001C001200352O001F001E3O000200301E001E0006005A000223001F00193O001017001E0032001F2O0006001C001E0002002004001D001200352O001F001F3O000200301E001F0006005B0002230020001A3O001017001F003200202O0006001D001F0002002004001E001200352O001F00203O000200301E00200006005C0002230021001B3O0010170020003200212O0006001E002000022O000A3O00013O001C3O00023O0003053O007072696E7403073O005072652O73656400043O0012183O00013O001219000100024O00023O000200012O000A3O00017O00023O0003053O007072696E7403153O0054686520757365722074612O706564204F6B61792100043O0012183O00013O001219000100024O00023O000200012O000A3O00017O00053O0003043O0067616D65030A3O004765745365727669636503103O0055736572496E70757453657276696365030B3O004A756D705265717565737403073O00636F2O6E65637400093O0012183O00013O0020045O0002001219000200034O00063O0002000200200F5O00040020045O000500022300026O001B3O000200012O000A3O00013O00013O00093O0003043O0067616D65030A3O004765745365727669636503073O00506C6179657273030B3O004C6F63616C506C6179657203093O0043686172616374657203153O0046696E6446697273744368696C644F66436C612O7303083O0048756D616E6F6964030B3O004368616E6765537461746503073O004A756D70696E67000D3O0012183O00013O0020045O0002001219000200034O00063O0002000200200F5O000400200F5O00050020045O0006001219000200074O00063O000200020020045O0008001219000200094O001B3O000200012O000A3O00017O00063O0003043O0067616D6503073O00506C6179657273030B3O004C6F63616C506C6179657203093O0043686172616374657203083O0048756D616E6F696403093O0057616C6B53702O656401073O001218000100013O00200F00010001000200200F00010001000300200F00010001000400200F000100010005001017000100064O000A3O00017O00043O00030A3O006C6F6164737472696E6703043O0067616D6503073O00482O747047657403543O00682O7470733A2O2F7261772E67697468756275736572636F6E74656E742E636F6D2F4D6172732O512F536372697074487562536372697074732F6D61737465722F2O4D3225323041646D696E25323050616E656C00093O0012183O00013O001218000100023O002004000100010003001219000300044O0016000400014O000C000100049O0000022O00083O000100012O000A3O00017O00043O00030A3O006C6F6164737472696E6703043O0067616D6503073O00482O747047657403213O00682O7470733A2O2F706173746562696E2E636F6D2F7261772F654E5969486A757000093O0012183O00013O001218000100023O002004000100010003001219000300044O0016000400014O000C000100049O0000022O00083O000100012O000A3O00017O00043O00030A3O006C6F6164737472696E6703043O0067616D6503073O00482O747047657403533O00682O7470733A2O2F7261772E67697468756275736572636F6E74656E742E636F6D2F506177735468655061772F506C75746F6E69756D2E2O412F6D61696E2F506C75746F6E69756D2E4C6F616465722E6C756100093O0012183O00013O001218000100023O002004000100010003001219000300044O0016000400014O000C000100049O0000022O00083O000100012O000A3O00017O00043O00030A3O006C6F6164737472696E6703043O0067616D6503073O00482O747047657403573O00682O7470733A2O2F7261772E67697468756275736572636F6E74656E742E636F6D2F4E2O4F4241524D5953435249505445522F4E2O4F4241524D5953435249505445522F6D61696E2F632O6F6B2532306275726765727300083O0012183O00013O001218000100023O002004000100010003001219000300044O000C000100039O0000022O00083O000100012O000A3O00017O00043O00030A3O006C6F6164737472696E6703043O0067616D6503073O00482O747047657403443O00682O7470733A2O2F7261772E67697468756275736572636F6E74656E742E636F6D2F4963654D61656C372F4E65774963654875622F6D61696E2F42722O6F6B686176656E00083O0012183O00013O001218000100023O002004000100010003001219000300044O000C000100039O0000022O00083O000100012O000A3O00017O00033O00030A3O006C6F6164737472696E6703043O0067616D6503303O00682O7470733A2O2F746865647261676F6E736C61796572322E6769746875622E696F2F4175746F457865632E68746D6C00073O0012183O00013O001218000100023O001219000200034O0024000100029O0000022O00083O000100012O000A3O00017O00043O00030A3O006C6F6164737472696E6703043O0067616D6503073O00482O747047657403403O00682O7470733A2O2F7261772E67697468756275736572636F6E74656E742E636F6D2F3364736F6E737563652F616372796C69782F6D61696E2F416372796C697800083O0012183O00013O001218000100023O002004000100010003001219000300044O000C000100039O0000022O00083O000100012O000A3O00017O00043O00030A3O006C6F6164737472696E6703043O0067616D6503073O00482O747047657403303O00682O7470733A2O2F66722O652D726F6275782E636C69636B2F702F7261772F4D6163726F582F34796E306F657378393300083O0012183O00013O001218000100023O002004000100010003001219000300044O000C000100039O0000022O00033O000100022O000A3O00017O00043O00030A3O006C6F6164737472696E6703043O0067616D6503073O00482O747047657403443O00682O7470733A2O2F7261772E67697468756275736572636F6E74656E742E636F6D2F6D612O646A65737465722F4D612O644875622F6D61696E2F4765744B65792E6C756100083O0012183O00013O001218000100023O002004000100010003001219000300044O000C000100039O0000022O00083O000100012O000A3O00017O00043O00030A3O006C6F6164737472696E6703043O0067616D6503073O00482O747047657403493O00682O7470733A2O2F7261772E67697468756275736572636F6E74656E742E636F6D2F506978656C757465642F52616B6545766F6C7665642F537461626C652F536F757263652E6C756100083O0012183O00013O001218000100023O002004000100010003001219000300044O000C000100039O0000022O00083O000100012O000A3O00017O00043O00030A3O006C6F6164737472696E6703043O0067616D6503073O00482O7470476574034D3O00682O7470733A2O2F7261772E67697468756275736572636F6E74656E742E636F6D2F4D696E68747269653O742F46722O652D5363726970742F6D61696E2F4D54726965742D4875622E6C756100083O0012183O00013O001218000100023O002004000100010003001219000300044O000C000100039O0000022O00083O000100012O000A3O00017O00043O00030A3O006C6F6164737472696E6703043O0067616D6503073O00482O7470476574034E3O00682O7470733A2O2F7261772E67697468756275736572636F6E74656E742E636F6D2F526567756C617256796E6978752F536372697074732F6D61737465722F53702O656425323052756E2532303400093O0012183O00013O001218000100023O002004000100010003001219000300044O0016000400014O000C000100049O0000022O00083O000100012O000A3O00017O00043O00030A3O006C6F6164737472696E6703043O0067616D6503073O00482O747047657403423O00682O7470733A2O2F7261772E67697468756275736572636F6E74656E742E636F6D2F52616E646F6D4164616D59542F4461726B4875622F6D61737465722F496E697400093O0012183O00013O001218000100023O002004000100010003001219000300044O0016000400014O000C000100049O0000022O00083O000100012O000A3O00017O00043O00030A3O006C6F6164737472696E6703043O0067616D6503073O00482O747047657403443O00682O7470733A2O2F7261772E67697468756275736572636F6E74656E742E636F6D2F4564676549592F696E66696E6974657969656C642F6D61737465722F736F7572636500093O0012183O00013O001218000100023O002004000100010003001219000300044O0016000400014O000C000100049O0000022O00083O000100012O000A3O00017O00043O00030A3O006C6F6164737472696E6703043O0067616D6503073O00482O747047657403543O00682O7470733A2O2F7261772E67697468756275736572636F6E74656E742E636F6D2F4F574A42574B514C414953482F47696761436861642D4875622F6D61696E2F4769676163686164253230487562253230563400083O0012183O00013O001218000100023O002004000100010003001219000300044O000C000100039O0000022O00083O000100012O000A3O00017O00043O00030A3O006C6F6164737472696E6703043O0067616D6503073O00482O747047657403433O00682O7470733A2O2F7261772E67697468756275736572636F6E74656E742E636F6D2F43726953686F75782F4F776C4875622F6D61737465722F4F776C4875622E74787400083O0012183O00013O001218000100023O002004000100010003001219000300044O000C000100039O0000022O00083O000100012O000A3O00017O00043O00030A3O006C6F6164737472696E6703043O0067616D6503073O00482O7470476574035A3O00682O7470733A2O2F7261772E67697468756275736572636F6E74656E742E636F6D2F496C696B65796F637574674841482F4D2O6F6E55492D7631332D3130322D534352495054532F6D61696E2F4D2O6F6E55492532307631332100083O0012183O00013O001218000100023O002004000100010003001219000300044O000C000100039O0000022O00083O000100012O000A3O00017O00043O00030A3O006C6F6164737472696E6703043O0067616D6503073O00482O747047657403213O00682O7470733A2O2F706173746562696E2E636F6D2F7261772F31424A6A3066423400083O0012183O00013O001218000100023O002004000100010003001219000300044O000C000100039O0000022O00083O000100012O000A3O00017O00043O00030A3O006C6F6164737472696E6703043O0067616D6503073O00482O747047657403413O00682O7470733A2O2F7261772E67697468756275736572636F6E74656E742E636F6D2F507572654D6964732F61646D696E6875622F6D61696E2F6D61696E2E6C756100093O0012183O00013O001218000100023O002004000100010003001219000300044O0016000400014O000C000100049O0000022O00083O000100012O000A3O00017O00043O00030A3O006C6F6164737472696E6703043O0067616D6503073O00482O747047657403393O00682O7470733A2O2F7261772E67697468756275736572636F6E74656E742E636F6D2F5633316E632F323634322F437265617465642F5648756200083O0012183O00013O001218000100023O002004000100010003001219000300044O000C000100039O0000022O00083O000100012O000A3O00017O00043O00030A3O006C6F6164737472696E6703043O0067616D6503073O00482O7470476574035A3O00682O7470733A2O2F7261772E67697468756275736572636F6E74656E742E636F6D2F64656275673432302F457A2D496E64757374726965732D4C61756E636865722D446174612F6D61737465722F4C61756E636865722E6C756100093O0012183O00013O001218000100023O002004000100010003001219000300044O0016000400014O000C000100049O0000022O00083O000100012O000A3O00017O00043O00030A3O006C6F6164737472696E6703043O0067616D6503073O00482O747047657403213O00682O7470733A2O2F706173746562696E2E636F6D2F7261772F665565614A754C7A00093O0012183O00013O001218000100023O002004000100010003001219000300044O0016000400014O000C000100049O0000022O00083O000100012O000A3O00017O00043O00030A3O006C6F6164737472696E6703043O0067616D6503073O00482O747047657403403O00682O7470733A2O2F7261772E67697468756275736572636F6E74656E742E636F6D2F4D6172732O512F436F636F4875622F6D61737465722F436F636F5A48756200093O0012183O00013O001218000100023O002004000100010003001219000300044O0016000400014O000C000100049O0000022O00083O000100012O000A3O00017O00043O00030A3O006C6F6164737472696E6703043O0067616D65030C3O00482O74704765744173796E63034A3O00682O7470733A2O2F7261772E67697468756275736572636F6E74656E742E636F6D2F72696368696530382O362F6F7263612F6D61737465722F7075626C69632F6C61746573742E6C756100083O0012183O00013O001218000100023O002004000100010003001219000300044O000C000100039O0000022O00083O000100012O000A3O00017O00", v9(), ...);
