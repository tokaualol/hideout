## VALVE
<hr>

[SteamDB](https://steamdb.info)<br>
Database covering the entire Steam catalog. Player charts, price history across all regions, update histories, and detailed data for every product.

[Steam Status](https://steamstat.us)<br>
Steam server status.

[SteamID](https://steamid.uk)<br>
Steam profile lookup with history.

[ChatterBox for Source](https://ralphorama.github.io)<br>
Generate a list of say binds that rotate.

<hr>
Remove Featured Badge on profile (1)
{ .annotate }

1. 1. Edit Profile<br>
    2. Featured Badge<br>
    3. Paste in Console<br>
    4. Save

![badge](../assets/img/badge.png)
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

[CSFloat Market Checker](https://chromewebstore.google.com/detail/csfloat-market-checker/jjicbefpemnphinccgikpdaagjebbnhg)<br>
Shows the float value, paint seed, and more of Counter-Strike items on the Steam Market or Inventories.

[NoLobbyReservation](https://github.com/honey-malviya/No-Lobby-Reservation)<br>
A SourceMod plugin which allows CSGO servers to be joinable again.

## Deadlock