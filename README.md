# capacitor-plugin-musickit

Requires iOS 16 or higher

## Install

```bash
npm install capacitor-plugin-musickit
npx cap sync
```

## API

<docgen-index>

* [`addListener('playbackStateDidChange', ...)`](#addlistenerplaybackstatedidchange)
* [`addListener('nowPlayingItemDidChange', ...)`](#addlistenernowplayingitemdidchange)
* [`addListener('authorizationStatusDidChange', ...)`](#addlistenerauthorizationstatusdidchange)
* [`addRating(...)`](#addrating)
* [`authorize()`](#authorize)
* [`configure(...)`](#configure)
* [`deleteRating(...)`](#deleterating)
* [`echo(...)`](#echo)
* [`getCurrentIndex()`](#getcurrentindex)
* [`getCurrentPlaybackTime()`](#getcurrentplaybacktime)
* [`getCurrentSong()`](#getcurrentsong)
* [`getLibraryAlbums(...)`](#getlibraryalbums)
* [`getLibraryArtists(...)`](#getlibraryartists)
* [`getLibraryPlaylists(...)`](#getlibraryplaylists)
* [`getLibrarySongs(...)`](#getlibrarysongs)
* [`getQueueSongs()`](#getqueuesongs)
* [`getRatings(...)`](#getratings)
* [`getRepeatMode()`](#getrepeatmode)
* [`getShuffleMode()`](#getshufflemode)
* [`hasMusicSubscription()`](#hasmusicsubscription)
* [`isAuthorized()`](#isauthorized)
* [`nextPlay()`](#nextplay)
* [`pause()`](#pause)
* [`play(...)`](#play)
* [`previousPlay()`](#previousplay)
* [`seekToTime(...)`](#seektotime)
* [`setQueue(...)`](#setqueue)
* [`setRepeatMode(...)`](#setrepeatmode)
* [`setShuffleMode(...)`](#setshufflemode)
* [`stop()`](#stop)
* [`unauthorize()`](#unauthorize)
* [Interfaces](#interfaces)
* [Type Aliases](#type-aliases)

</docgen-index>

<docgen-api>
<!--Update the source file JSDoc comments and rerun docgen to update the docs below-->

### addListener('playbackStateDidChange', ...)

```typescript
addListener(eventName: "playbackStateDidChange", listenerFunc: PlaybackStateDidChangeListener) => Promise<PluginListenerHandle> & PluginListenerHandle
```

| Param              | Type                                                                                      |
| ------------------ | ----------------------------------------------------------------------------------------- |
| **`eventName`**    | <code>'playbackStateDidChange'</code>                                                     |
| **`listenerFunc`** | <code><a href="#playbackstatedidchangelistener">PlaybackStateDidChangeListener</a></code> |

**Returns:** <code>Promise&lt;<a href="#pluginlistenerhandle">PluginListenerHandle</a>&gt; & <a href="#pluginlistenerhandle">PluginListenerHandle</a></code>

--------------------


### addListener('nowPlayingItemDidChange', ...)

```typescript
addListener(eventName: "nowPlayingItemDidChange", listenerFunc: NowPlayingItemDidChangeListener) => Promise<PluginListenerHandle> & PluginListenerHandle
```

| Param              | Type                                                                                        |
| ------------------ | ------------------------------------------------------------------------------------------- |
| **`eventName`**    | <code>'nowPlayingItemDidChange'</code>                                                      |
| **`listenerFunc`** | <code><a href="#nowplayingitemdidchangelistener">NowPlayingItemDidChangeListener</a></code> |

**Returns:** <code>Promise&lt;<a href="#pluginlistenerhandle">PluginListenerHandle</a>&gt; & <a href="#pluginlistenerhandle">PluginListenerHandle</a></code>

--------------------


### addListener('authorizationStatusDidChange', ...)

```typescript
addListener(eventName: "authorizationStatusDidChange", listenerFunc: AuthorizationStatusDidChangeListener) => Promise<PluginListenerHandle> & PluginListenerHandle
```

| Param              | Type                                                                                                  |
| ------------------ | ----------------------------------------------------------------------------------------------------- |
| **`eventName`**    | <code>'authorizationStatusDidChange'</code>                                                           |
| **`listenerFunc`** | <code><a href="#authorizationstatusdidchangelistener">AuthorizationStatusDidChangeListener</a></code> |

**Returns:** <code>Promise&lt;<a href="#pluginlistenerhandle">PluginListenerHandle</a>&gt; & <a href="#pluginlistenerhandle">PluginListenerHandle</a></code>

--------------------


### addRating(...)

```typescript
addRating(options: AddRatingOptions) => Promise<RatingsResult>
```

| Param         | Type                                                          |
| ------------- | ------------------------------------------------------------- |
| **`options`** | <code><a href="#addratingoptions">AddRatingOptions</a></code> |

**Returns:** <code>Promise&lt;<a href="#ratingsresult">RatingsResult</a>&gt;</code>

--------------------


### authorize()

```typescript
authorize() => Promise<void>
```

--------------------


### configure(...)

```typescript
configure(options: ConfigureOptions) => Promise<ActionResult>
```

| Param         | Type                                                          |
| ------------- | ------------------------------------------------------------- |
| **`options`** | <code><a href="#configureoptions">ConfigureOptions</a></code> |

**Returns:** <code>Promise&lt;<a href="#actionresult">ActionResult</a>&gt;</code>

--------------------


### deleteRating(...)

```typescript
deleteRating(options: DeleteRatingOptions) => Promise<RatingsResult>
```

| Param         | Type                                                                |
| ------------- | ------------------------------------------------------------------- |
| **`options`** | <code><a href="#deleteratingoptions">DeleteRatingOptions</a></code> |

**Returns:** <code>Promise&lt;<a href="#ratingsresult">RatingsResult</a>&gt;</code>

--------------------


### echo(...)

```typescript
echo(options: EchoOptions) => Promise<EchoResult>
```

| Param         | Type                                                |
| ------------- | --------------------------------------------------- |
| **`options`** | <code><a href="#echooptions">EchoOptions</a></code> |

**Returns:** <code>Promise&lt;<a href="#echoresult">EchoResult</a>&gt;</code>

--------------------


### getCurrentIndex()

```typescript
getCurrentIndex() => Promise<GetCurrentIndexResult>
```

**Returns:** <code>Promise&lt;<a href="#getcurrentindexresult">GetCurrentIndexResult</a>&gt;</code>

--------------------


### getCurrentPlaybackTime()

```typescript
getCurrentPlaybackTime() => Promise<GetCurrentPlaybackTimeResult>
```

**Returns:** <code>Promise&lt;<a href="#getcurrentplaybacktimeresult">GetCurrentPlaybackTimeResult</a>&gt;</code>

--------------------


### getCurrentSong()

```typescript
getCurrentSong() => Promise<GetCurrentSongResult>
```

**Returns:** <code>Promise&lt;<a href="#getcurrentsongresult">GetCurrentSongResult</a>&gt;</code>

--------------------


### getLibraryAlbums(...)

```typescript
getLibraryAlbums(options: GetLibraryAlbumsOptions) => Promise<GetLibraryAlbumsResult>
```

| Param         | Type                                                                        |
| ------------- | --------------------------------------------------------------------------- |
| **`options`** | <code><a href="#getlibraryalbumsoptions">GetLibraryAlbumsOptions</a></code> |

**Returns:** <code>Promise&lt;<a href="#getlibraryalbumsresult">GetLibraryAlbumsResult</a>&gt;</code>

--------------------


### getLibraryArtists(...)

```typescript
getLibraryArtists(options: GetLibraryArtistsOptions) => Promise<GetLibraryArtistsResult>
```

| Param         | Type                                                                          |
| ------------- | ----------------------------------------------------------------------------- |
| **`options`** | <code><a href="#getlibraryartistsoptions">GetLibraryArtistsOptions</a></code> |

**Returns:** <code>Promise&lt;<a href="#getlibraryartistsresult">GetLibraryArtistsResult</a>&gt;</code>

--------------------


### getLibraryPlaylists(...)

```typescript
getLibraryPlaylists(options: GetLibraryPlaylistsOptions) => Promise<GetLibraryPlaylistsResult>
```

| Param         | Type                                                                              |
| ------------- | --------------------------------------------------------------------------------- |
| **`options`** | <code><a href="#getlibraryplaylistsoptions">GetLibraryPlaylistsOptions</a></code> |

**Returns:** <code>Promise&lt;<a href="#getlibraryplaylistsresult">GetLibraryPlaylistsResult</a>&gt;</code>

--------------------


### getLibrarySongs(...)

```typescript
getLibrarySongs(options: GetLibrarySongsOptions) => Promise<GetLibrarySongsResult>
```

| Param         | Type                                                                      |
| ------------- | ------------------------------------------------------------------------- |
| **`options`** | <code><a href="#getlibrarysongsoptions">GetLibrarySongsOptions</a></code> |

**Returns:** <code>Promise&lt;<a href="#getlibrarysongsresult">GetLibrarySongsResult</a>&gt;</code>

--------------------


### getQueueSongs()

```typescript
getQueueSongs() => Promise<GetQueueSongsResult>
```

**Returns:** <code>Promise&lt;<a href="#getqueuesongsresult">GetQueueSongsResult</a>&gt;</code>

--------------------


### getRatings(...)

```typescript
getRatings(options: GetRatingsOptions) => Promise<RatingsResult>
```

| Param         | Type                                                            |
| ------------- | --------------------------------------------------------------- |
| **`options`** | <code><a href="#getratingsoptions">GetRatingsOptions</a></code> |

**Returns:** <code>Promise&lt;<a href="#ratingsresult">RatingsResult</a>&gt;</code>

--------------------


### getRepeatMode()

```typescript
getRepeatMode() => Promise<GetRepeatModeResult>
```

**Returns:** <code>Promise&lt;<a href="#getrepeatmoderesult">GetRepeatModeResult</a>&gt;</code>

--------------------


### getShuffleMode()

```typescript
getShuffleMode() => Promise<GetShuffleModeResult>
```

**Returns:** <code>Promise&lt;<a href="#getshufflemoderesult">GetShuffleModeResult</a>&gt;</code>

--------------------


### hasMusicSubscription()

```typescript
hasMusicSubscription() => Promise<ActionResult>
```

**Returns:** <code>Promise&lt;<a href="#actionresult">ActionResult</a>&gt;</code>

--------------------


### isAuthorized()

```typescript
isAuthorized() => Promise<ActionResult>
```

**Returns:** <code>Promise&lt;<a href="#actionresult">ActionResult</a>&gt;</code>

--------------------


### nextPlay()

```typescript
nextPlay() => Promise<ActionResult>
```

**Returns:** <code>Promise&lt;<a href="#actionresult">ActionResult</a>&gt;</code>

--------------------


### pause()

```typescript
pause() => Promise<ActionResult>
```

**Returns:** <code>Promise&lt;<a href="#actionresult">ActionResult</a>&gt;</code>

--------------------


### play(...)

```typescript
play(options: PlayOptions) => Promise<ActionResult>
```

| Param         | Type                                                |
| ------------- | --------------------------------------------------- |
| **`options`** | <code><a href="#playoptions">PlayOptions</a></code> |

**Returns:** <code>Promise&lt;<a href="#actionresult">ActionResult</a>&gt;</code>

--------------------


### previousPlay()

```typescript
previousPlay() => Promise<ActionResult>
```

**Returns:** <code>Promise&lt;<a href="#actionresult">ActionResult</a>&gt;</code>

--------------------


### seekToTime(...)

```typescript
seekToTime(options: SeekToTimeOptions) => Promise<ActionResult>
```

| Param         | Type                                                            |
| ------------- | --------------------------------------------------------------- |
| **`options`** | <code><a href="#seektotimeoptions">SeekToTimeOptions</a></code> |

**Returns:** <code>Promise&lt;<a href="#actionresult">ActionResult</a>&gt;</code>

--------------------


### setQueue(...)

```typescript
setQueue(options: SetQueueOptions) => Promise<SetQueueResult>
```

| Param         | Type                                                        |
| ------------- | ----------------------------------------------------------- |
| **`options`** | <code><a href="#setqueueoptions">SetQueueOptions</a></code> |

**Returns:** <code>Promise&lt;<a href="#setqueueresult">SetQueueResult</a>&gt;</code>

--------------------


### setRepeatMode(...)

```typescript
setRepeatMode(options: SetRepeatModeOptions) => Promise<ActionResult>
```

| Param         | Type                                                                  |
| ------------- | --------------------------------------------------------------------- |
| **`options`** | <code><a href="#setrepeatmodeoptions">SetRepeatModeOptions</a></code> |

**Returns:** <code>Promise&lt;<a href="#actionresult">ActionResult</a>&gt;</code>

--------------------


### setShuffleMode(...)

```typescript
setShuffleMode(options: SetShuffleModeOptions) => Promise<ActionResult>
```

| Param         | Type                                                                    |
| ------------- | ----------------------------------------------------------------------- |
| **`options`** | <code><a href="#setshufflemodeoptions">SetShuffleModeOptions</a></code> |

**Returns:** <code>Promise&lt;<a href="#actionresult">ActionResult</a>&gt;</code>

--------------------


### stop()

```typescript
stop() => Promise<ActionResult>
```

**Returns:** <code>Promise&lt;<a href="#actionresult">ActionResult</a>&gt;</code>

--------------------


### unauthorize()

```typescript
unauthorize() => Promise<void>
```

--------------------


### Interfaces


#### PluginListenerHandle

| Prop         | Type                                      |
| ------------ | ----------------------------------------- |
| **`remove`** | <code>() =&gt; Promise&lt;void&gt;</code> |


#### ActionResult

| Prop         | Type                 |
| ------------ | -------------------- |
| **`result`** | <code>boolean</code> |


#### ConfigureOptions

| Prop         | Type                                |
| ------------ | ----------------------------------- |
| **`config`** | <code>MusicKit.Configuration</code> |


#### EchoResult

| Prop        | Type                |
| ----------- | ------------------- |
| **`value`** | <code>string</code> |


#### EchoOptions

| Prop        | Type                |
| ----------- | ------------------- |
| **`value`** | <code>string</code> |


#### GetCurrentIndexResult

| Prop        | Type                |
| ----------- | ------------------- |
| **`index`** | <code>number</code> |


#### GetCurrentPlaybackTimeResult

| Prop       | Type                |
| ---------- | ------------------- |
| **`time`** | <code>number</code> |


#### GetCurrentSongResult

| Prop       | Type                            |
| ---------- | ------------------------------- |
| **`item`** | <code>MusicKit.MediaItem</code> |


#### GetMultiDataOptions

| Prop         | Type                  |
| ------------ | --------------------- |
| **`ids`**    | <code>string[]</code> |
| **`limit`**  | <code>number</code>   |
| **`offset`** | <code>number</code>   |


#### GetQueueSongsResult

| Prop        | Type                     |
| ----------- | ------------------------ |
| **`items`** | <code>MediaItem[]</code> |


#### GetRepeatModeResult

| Prop       | Type                                  |
| ---------- | ------------------------------------- |
| **`mode`** | <code>'none' \| 'one' \| 'all'</code> |


#### GetShuffleModeResult

| Prop       | Type                          |
| ---------- | ----------------------------- |
| **`mode`** | <code>'off' \| 'songs'</code> |


#### PlayOptions

| Prop        | Type                |
| ----------- | ------------------- |
| **`index`** | <code>number</code> |


#### SeekToTimeOptions

| Prop       | Type                |
| ---------- | ------------------- |
| **`time`** | <code>number</code> |


#### SetQueueResult

| Prop        | Type                     |
| ----------- | ------------------------ |
| **`items`** | <code>MediaItem[]</code> |


#### SetQueueOptions

| Prop      | Type                  |
| --------- | --------------------- |
| **`ids`** | <code>string[]</code> |


#### SetRepeatModeOptions

| Prop       | Type                                  |
| ---------- | ------------------------------------- |
| **`mode`** | <code>'none' \| 'one' \| 'all'</code> |


#### SetShuffleModeOptions

| Prop       | Type                          |
| ---------- | ----------------------------- |
| **`mode`** | <code>'off' \| 'songs'</code> |


### Type Aliases


#### PlaybackStateDidChangeListener

<code>(data: <a href="#playbackstatedidchangeresult">PlaybackStateDidChangeResult</a>): void</code>


#### PlaybackStateDidChangeResult

<code>{ state: <a href="#playbackstate">PlaybackState</a>; }</code>


#### PlaybackState

<code>keyof typeof MusicKit.PlaybackStates</code>


#### NowPlayingItemDidChangeListener

<code>(data: <a href="#nowplayingitemdidchangeresult">NowPlayingItemDidChangeResult</a>): void</code>


#### NowPlayingItemDidChangeResult

<code>{ index: number; item: MusicKit.MediaItem; }</code>


#### AuthorizationStatusDidChangeListener

<code>(data: <a href="#authorizationstatusdidchangeresult">AuthorizationStatusDidChangeResult</a>): void</code>


#### AuthorizationStatusDidChangeResult

<code>{ status: <a href="#authorizationstatus">AuthorizationStatus</a>; }</code>


#### AuthorizationStatus

<code>"unavailable" | "notDetermined" | "denied" | "restricted" | "authorized"</code>


#### RatingsResult

<code>MusicKit.Relationship&lt;MusicKit.Ratings&gt;</code>


#### AddRatingOptions

<code>{ id: string; type: MusicKit.AppleMusicAPI.RatingType; value: MusicKit.Rating; }</code>


#### DeleteRatingOptions

<code>{ id: string; type: MusicKit.AppleMusicAPI.RatingType; }</code>


#### GetLibraryAlbumsResult

<code>MusicKit.Relationship&lt;MusicKit.LibraryAlbums&gt;</code>


#### GetLibraryAlbumsOptions

<code>{ artistId?: string; catalogId?: string; musicVideoId?: string; songId?: string; } & <a href="#getmultidataoptions">GetMultiDataOptions</a></code>


#### GetLibraryArtistsResult

<code>MusicKit.Relationship&lt;MusicKit.LibraryArtists&gt;</code>


#### GetLibraryArtistsOptions

<code>{ albumId?: string; musicVideoId?: string; songId?: string; } & <a href="#getmultidataoptions">GetMultiDataOptions</a></code>


#### GetLibraryPlaylistsResult

<code>MusicKit.Relationship&lt;MusicKit.LibraryPlaylists&gt;</code>


#### GetLibraryPlaylistsOptions

<code>{ catalogId?: string; } & <a href="#getmultidataoptions">GetMultiDataOptions</a></code>


#### GetLibrarySongsResult

<code>MusicKit.Relationship&lt;MusicKit.LibrarySongs&gt;</code>


#### GetLibrarySongsOptions

<code>{ albumId?: string; catalogId?: string; playlistId?: string; } & <a href="#getmultidataoptions">GetMultiDataOptions</a></code>


#### GetRatingsOptions

<code>{ ids: string[]; type: MusicKit.AppleMusicAPI.RatingType; }</code>

</docgen-api>
