[android-components](../../index.md) / [mozilla.components.browser.engine.system](../index.md) / [SystemEngineSession](./index.md)

# SystemEngineSession

`class SystemEngineSession : `[`EngineSession`](../../mozilla.components.concept.engine/-engine-session/index.md) [(source)](https://github.com/mozilla-mobile/android-components/blob/master/components/browser/engine-system/src/main/java/mozilla/components/browser/engine/system/SystemEngineSession.kt#L41)

WebView-based EngineSession implementation.

### Types

| Name | Summary |
|---|---|
| [WebSetting](-web-setting/index.md) | `class WebSetting<T>` |

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `SystemEngineSession(context: `[`Context`](https://developer.android.com/reference/android/content/Context.html)`, defaultSettings: `[`Settings`](../../mozilla.components.concept.engine/-settings/index.md)`? = null)`<br>WebView-based EngineSession implementation. |

### Properties

| Name | Summary |
|---|---|
| [settings](settings.md) | `val settings: `[`Settings`](../../mozilla.components.concept.engine/-settings/index.md)<br>See [EngineSession.settings](../../mozilla.components.concept.engine/-engine-session/settings.md) |
| [webView](web-view.md) | `var webView: `[`WebView`](https://developer.android.com/reference/android/webkit/WebView.html) |

### Functions

| Name | Summary |
|---|---|
| [captureThumbnail](capture-thumbnail.md) | `fun captureThumbnail(): `[`Bitmap`](https://developer.android.com/reference/android/graphics/Bitmap.html)`?`<br>Takes a screenshot of the actual tab |
| [clearData](clear-data.md) | `fun clearData(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>See [EngineSession.clearData](../../mozilla.components.concept.engine/-engine-session/clear-data.md) |
| [clearFindMatches](clear-find-matches.md) | `fun clearFindMatches(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>See [EngineSession.clearFindMatches](../../mozilla.components.concept.engine/-engine-session/clear-find-matches.md) |
| [close](close.md) | `fun close(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>See [EngineSession.close](../../mozilla.components.concept.engine/-engine-session/close.md) |
| [disableTrackingProtection](disable-tracking-protection.md) | `fun disableTrackingProtection(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>See [EngineSession.disableTrackingProtection](../../mozilla.components.concept.engine/-engine-session/disable-tracking-protection.md) |
| [enableTrackingProtection](enable-tracking-protection.md) | `fun enableTrackingProtection(policy: `[`TrackingProtectionPolicy`](../../mozilla.components.concept.engine/-engine-session/-tracking-protection-policy/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>See [EngineSession.enableTrackingProtection](../../mozilla.components.concept.engine/-engine-session/enable-tracking-protection.md) |
| [exitFullScreenMode](exit-full-screen-mode.md) | `fun exitFullScreenMode(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>See [EngineSession.exitFullScreenMode](../../mozilla.components.concept.engine/-engine-session/exit-full-screen-mode.md) |
| [findAll](find-all.md) | `fun findAll(text: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>See [EngineSession.findAll](../../mozilla.components.concept.engine/-engine-session/find-all.md) |
| [findNext](find-next.md) | `fun findNext(forward: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>See [EngineSession.findNext](../../mozilla.components.concept.engine/-engine-session/find-next.md) |
| [goBack](go-back.md) | `fun goBack(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>See [EngineSession.goBack](../../mozilla.components.concept.engine/-engine-session/go-back.md) |
| [goForward](go-forward.md) | `fun goForward(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>See [EngineSession.goForward](../../mozilla.components.concept.engine/-engine-session/go-forward.md) |
| [loadData](load-data.md) | `fun loadData(data: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, mimeType: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, encoding: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>See [EngineSession.loadData](../../mozilla.components.concept.engine/-engine-session/load-data.md) |
| [loadUrl](load-url.md) | `fun loadUrl(url: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>See [EngineSession.loadUrl](../../mozilla.components.concept.engine/-engine-session/load-url.md) |
| [reload](reload.md) | `fun reload(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>See [EngineSession.reload](../../mozilla.components.concept.engine/-engine-session/reload.md) |
| [restoreState](restore-state.md) | `fun restoreState(state: `[`EngineSessionState`](../../mozilla.components.concept.engine/-engine-session-state/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>See [EngineSession.restoreState](../../mozilla.components.concept.engine/-engine-session/restore-state.md) |
| [saveState](save-state.md) | `fun saveState(): `[`EngineSessionState`](../../mozilla.components.concept.engine/-engine-session-state/index.md)<br>See [EngineSession.saveState](../../mozilla.components.concept.engine/-engine-session/save-state.md) |
| [stopLoading](stop-loading.md) | `fun stopLoading(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>See [EngineSession.stopLoading](../../mozilla.components.concept.engine/-engine-session/stop-loading.md) |
| [toggleDesktopMode](toggle-desktop-mode.md) | `fun toggleDesktopMode(enable: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`, reload: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>See [EngineSession.toggleDesktopMode](../../mozilla.components.concept.engine/-engine-session/toggle-desktop-mode.md) |
