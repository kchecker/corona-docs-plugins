# showSelectPlayers

> --------------------- ------------------------------------------------------------------------------------------
> __Type__              [Event][api.type.Event]
> __Revision__          [REVISION_LABEL](REVISION_URL)
> __Keywords__          Google Play Games Services, game network, gpgs
> __See also__          [gpgs2.multiplayer.*][plugin.gpgs2.multiplayer]
>                       [gpgs2.multiplayer.realtime.*][plugin.gpgs2.multiplayer.realtime]
>                       [gpgs2.*][plugin.gpgs2]
> --------------------- ------------------------------------------------------------------------------------------

## Overview

Indicates that the show players view was closed. Also carries selected players ids and other information.

## Gotchas

`event.isError` will be `true` because the view was `"cancelled"`, that's not an error per se, but for consistency it is treated as an error.

## Properties

#### [event.name][plugin.gpgs2.multiplayer.realtime.event.showSelectPlayers.name]

#### [event.isError][plugin.gpgs2.multiplayer.realtime.event.showSelectPlayers.isError]

#### [event.errorMessage][plugin.gpgs2.multiplayer.realtime.event.showSelectPlayers.errorMessage]

#### [event.errorCode][plugin.gpgs2.multiplayer.realtime.event.showSelectPlayers.errorCode]

#### [event.playerIds][plugin.gpgs2.multiplayer.realtime.event.showSelectPlayers.playerIds]

#### [event.automatch][plugin.gpgs2.multiplayer.realtime.event.showSelectPlayers.automatch]