# POST Pregame_LockCharacter

Lock in an agent  
**DO NOT USE THIS FOR INSTALOCKING**  
Riot doesn't like this. You may get banned or get the API restricted for the rest of us.  


Method: `POST`  
URL: `https://glz-{region}-1.{region}.a.pvp.net/pregame/v1/matches/{pre-game match id}/lock/{agent id}`  
Headers:
 - `X-Riot-Entitlements-JWT`: `{Riot entitlement}`
 - `Authorization`: `Bearer {base64 encoded Riot token}`

Variables:
 - `{Riot entitlement}`: Read [Common Components - Riot Entitlement](../common-components.md#riot-entitlement)
 - `{base64 encoded Riot token}`: Read [Common Components - Riot Token](../common-components.md#riot-token)
 - `{region}`: Read [Common Components - Region](../common-components.md#region)
 - `{pre-game match id}`: Read [Common Components - Pregame Match ID](../common-components.md#pregame-match-id)
 - `{agent id}`: The ID of the agent. You can get this ID from the [Content_FetchContent](../PVP%20Endpoints/GET%20Content_FetchContent.md) endpoint.
