1.20 CHERNARUS & LIVONIA cfggameplay.json UNLIMITED SPRINT / STAMINA,  BUILD ANYWHERE & MAP ACCESS Mod Changelog & Terms Of Use

Limited Testing on PC Chernarus & Livonia Local Server DAYZ  Version 1.20 Feb 2023.

Many thanks to bhaalshad for his amazing Discord:

https://discord.gg/bhaalshad

Stamina code snippets by bhaalshad, others by scalespeeder.. Please report bugs & errors to scalespeeder@gmail.com with screenshots.

TERMS OF USE
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS
OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN
AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH
THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Using these modded xml files could break the functioning of your DAYZ server, requiring a reinstall that would wipe
all player progress.

Using these modded xml files neccessitates increased regular restarts to prevent server crashing.

It is suggested you thoroughly test your server after applying these files to ensure proper
functioning of your server.

These cfggameplayfiles will give you unlimited sprint & stamina (sort of), build anywhere & map access (you can see you position on map - on PC by pressing M, on console by owning tourist map).

To install these files simply copy the relevant files to your mission folder and remove the map prefix, then restart your server.

Code Snippets for customisation:

Unlimited Sprint / Stamina:

"StaminaData":
		{
			"sprintStaminaModifierErc": 0,
			"sprintStaminaModifierCro": 0,
			"staminaWeightLimitThreshold": 6000.0,
			"staminaMax": 100.0,
			"staminaKgToStaminaPercentPenalty": 0,
			"staminaMinCap": 5.0,
			"sprintSwimmingStaminaModifier": 0,
			"sprintLadderStaminaModifier": 0,
			"meleeStaminaModifier": 0,
			"obstacleTraversalStaminaModifier": 1,
			"holdBreathStaminaModifier": 0
		},
		
Build Anywhere:

"BaseBuildingData":
	{
		"HologramData":
		{
			"disableIsCollidingBBoxCheck": true,
			"disableIsCollidingPlayerCheck": true,
			"disableIsClippingRoofCheck": true,
			"disableIsBaseViableCheck": true,
			"disableIsCollidingGPlotCheck": true,
			"disableIsCollidingAngleCheck": true,
			"disableIsPlacementPermittedCheck": true,
			"disableHeightPlacementCheck": true,
			"disableIsUnderwaterCheck": true,
			"disableIsInTerrainCheck": true
		},
		"ConstructionData":
		{
			"disablePerformRoofCheck": true,
			"disableIsCollidingCheck": true,
			"disableDistanceCheck": true
		}
	},

Map Access:

"MapData":
	{
		"ignoreMapOwnership": true,
		"ignoreNavItemsOwnership": true,
		"displayPlayerPosition": true,
		"displayNavInfo": true
	}	

GOOD LUCK!
