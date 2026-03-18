## VALVE

[SteamID](https://steamid.uk)<br>
Steam profile lookup with history

<hr>
Remove Featured Badge on profile (1)
{ .annotate }

1. 1. Edit Profile<br>
    2. Featured Badge<br>
    3. Paste in Console<br>
    4. Save

![badge](../assets/images/badge.png)
```js
var access_token =  $J("[data-loyaltystore]").data("loyaltystore").webapi_token;
var badgeid = 0;

SetFavoriteFeaturedBadge(access_token, badgeid);

function SetFavoriteFeaturedBadge(access_token, badgeid) {
    $J.post( 'https://api.steampowered.com/IPlayerService/SetFavoriteBadge/v1?', {
        access_token: access_token,
        badgeid: badgeid
    });
} 
```
<hr>

## Counter-Strike

## Deadlock