---
class: ShadedOverlay
total_properties: 165
generated_at: '2026-10-12 14:10:10'
gma3_version: '2.4.2.2'
---

# UI Class: `ShadedOverlay`
**Total Properties:** 165

### Legend
* **`[W]`** = Writable (User can modify via script)
* **`[R]`** = Read-Only (Engine locked, auto-calculated, or strict Enum)
* **`[R-Event]`** = Event Signal / Callback Hook
* **`[R-Object]`** = Handle / Reference Object
* **`[R-Fragile]`** = Modal Editor property (Skipped write tests to prevent UI collapse)
* **`[W-Destructive]`** = Writable, but modifying destroyed the object instance
* **`[?]`** = Untested / Unreadable

| Status       | ID    | Property Name                         | Default Value                | Type       |
| :----------: | :---- | :------------------------------------ | :--------------------------- | :--------- |
| `[R-System]` | `00`  | **IGNORENETWORK**                     | `true`                       | `boolean`  |
| `[R]`        | `01`  | **STRUCTURELOCKED**                   | `false`                      | `boolean`  |
| `[R]`        | `02`  | **SYSTEMLOCKED**                      | `false`                      | `boolean`  |
| `[R]`        | `03`  | **LOCK**                              | `""`                         | `string`   |
| `[R]`        | `04`  | **INDEX**                             | `3`                          | `number`   |
| `[R]`        | `05`  | **COUNT**                             | `4`                          | `number`   |
| `[R]`        | `06`  | **NO**                                | `3`                          | `number`   |
| `[W]`        | `07`  | **NAME**                              | `ShadedOverlay 3`            | `string`   |
| `[R]`        | `08`  | **NOTE**                              | `""`                         | `string`   |
| `[W]`        | `09`  | **USEREXPANDED**                      | `false`                      | `boolean`  |
| `[R]`        | `10`  | **FADERENABLED**                      | `false`                      | `boolean`  |
| `[R]`        | `11`  | **OWNED**                             | `false`                      | `boolean`  |
| `[W]`        | `12`  | **HIDDEN**                            | `false`                      | `boolean`  |
| `[R]`        | `13`  | **DEPENDENCYEXPORT**                  | `""`                         | `string`   |
| `[R]`        | `14`  | **MEMORYFOOTPRINT**                   | `0`                          | `number`   |
| `[W]`        | `15`  | **X**                                 | `0`                          | `string`   |
| `[W]`        | `16`  | **Y**                                 | `0`                          | `string`   |
| `[W]`        | `17`  | **W**                                 | ` 100.0000000000%(0)`        | `string`   |
| `[W]`        | `18`  | **H**                                 | ` 100.0000000000%(0)`        | `string`   |
| `[R-Object]` | `19`  | **ABSRECT**                           | `(table) table`              | `table`    |
| `[R-Object]` | `20`  | **ABSCLIENTRECT**                     | `(table) table`              | `table`    |
| `[R-Object]` | `21`  | **TEXTURE**                           | `(userdata) Root 19.2.1.267` | `userdata` |
| `[R-Object]` | `22`  | **FONT**                              | `(userdata) Root 19.2.2.16`  | `userdata` |
| `[R-Object]` | `23`  | **LOWDPIFONT**                        | `(userdata) Root 19.2.2.18`  | `userdata` |
| `[W]`        | `24`  | **TEXT**                              | `""`                         | `string`   |
| `[W]`        | `25`  | **TOOLTIP**                           | `""`                         | `string`   |
| `[W]`        | `26`  | **HELPTOPIC**                         | `""`                         | `string`   |
| `[R-Object]` | `27`  | **BACKCOLOR**                         | `(userdata) Color 16.1`      | `userdata` |
| `[R-Object]` | `28`  | **TEXTCOLOR**                         | `(userdata) Color 17.2`      | `userdata` |
| `[R-Object]` | `29`  | **TEXTSHADOWCOLOR**                   | `(userdata) Color 17.3`      | `userdata` |
| `[W]`        | `30`  | **MIXINBACKCOLOR**                    | `nil`                        | `unknown`  |
| `[R-Object]` | `31`  | **HIGHLIGHTEDCOLOR**                  | `(userdata) Color 1.7`       | `userdata` |
| `[W]`        | `32`  | **TEXTVERTICAL**                      | `false`                      | `boolean`  |
| `[W]`        | `33`  | **TEXTAUTOADJUST**                    | `false`                      | `boolean`  |
| `[W]`        | `34`  | **TEXTUNIFORM**                       | `true`                       | `boolean`  |
| `[W]`        | `35`  | **FRAMEWIDTH**                        | `0`                          | `number`   |
| `[R-Object]` | `36`  | **PADDING**                           | `(table) table`              | `table`    |
| `[W]`        | `37`  | **FOCUS**                             | `Never`                      | `string`   |
| `[W]`        | `38`  | **USERRIGHTS**                        | `None`                       | `string`   |
| `[W]`        | `39`  | **VISIBLE**                           | `true`                       | `boolean`  |
| `[W]`        | `40`  | **CANCOEXISTWITHMODAL**               | `false`                      | `boolean`  |
| `[W]`        | `41`  | **USERVISIBLE**                       | `true`                       | `boolean`  |
| `[W]`        | `42`  | **ENABLED**                           | `true`                       | `boolean`  |
| `[W]`        | `43`  | **INTERACTIVE**                       | `true`                       | `boolean`  |
| `[W]`        | `44`  | **TRANSPARENT**                       | `false`                      | `boolean`  |
| `[W]`        | `45`  | **BLOCKCLICKTHRU**                    | `false`                      | `boolean`  |
| `[R]`        | `46`  | **USERINTERACTED**                    | `false`                      | `boolean`  |
| `[W]`        | `47`  | **HASHOVER**                          | `false`                      | `boolean`  |
| `[W]`        | `48`  | **SEPARATOR**                         | `false`                      | `boolean`  |
| `[W]`        | `49`  | **HASPRESSEDANIMATION**               | `true`                       | `boolean`  |
| `[W]`        | `50`  | **CONTENTDRIVEN**                     | `true`                       | `boolean`  |
| `[W]`        | `51`  | **CONTENTWIDTH**                      | `true`                       | `boolean`  |
| `[W]`        | `52`  | **CONTENTHEIGHT**                     | `true`                       | `boolean`  |
| `[W]`        | `53`  | **FORCECONTENTMIN**                   | `false`                      | `boolean`  |
| `[W]`        | `54`  | **WANTSNUMERICREDIRECT**              | `false`                      | `boolean`  |
| `[W]`        | `55`  | **CLOSEACTION**                       | `None`                       | `string`   |
| `[W]`        | `56`  | **AUTOCLOSEVALUE**                    | `0`                          | `number`   |
| `[W]`        | `57`  | **UIGROUPID**                         | `0`                          | `number`   |
| `[W]`        | `58`  | **LABELLINKHANDLE**                   | `nil`                        | `unknown`  |
| `[W]`        | `59`  | **IGNOREBACKDROPPADDING**             | `false`                      | `boolean`  |
| `[W]`        | `60`  | **MIXINBACKCOLORFROMPARENT**          | `false`                      | `boolean`  |
| `[W]`        | `61`  | **MIXINBACKCOLORFROMPARENTRECURSIVE** | `false`                      | `boolean`  |
| `[W]`        | `62`  | **FOCUSSEARCHPOLICY**                 | `Force`                      | `string`   |
| `[W]`        | `63`  | **IGNOREREQUESTEDSIZE**               | `false`                      | `boolean`  |
| `[W]`        | `64`  | **FORCEENCODERBAR**                   | `false`                      | `boolean`  |
| `[W]`        | `65`  | **SUPPRESSOVERLAYAUTOCLOSE**          | `false`                      | `boolean`  |
| `[R]`        | `66`  | **ISCLOSING**                         | `false`                      | `boolean`  |
| `[W]`        | `67`  | **TEXTSHADOW**                        | `false`                      | `boolean`  |
| `[W]`        | `68`  | **BLOCKAUTOTARGET**                   | `false`                      | `boolean`  |
| `[W]`        | `69`  | **MINSIZE**                           | `200,100`                    | `string`   |
| `[W]`        | `70`  | **MAXSIZE**                           | `0,0`                        | `string`   |
| `[R-Object]` | `71`  | **ANCHORS**                           | `(table) table`              | `table`    |
| `[W]`        | `72`  | **SIGNALVALUE**                       | `""`                         | `string`   |
| `[W]`        | `73`  | **SIGNALVALUEHOLD**                   | `""`                         | `string`   |
| `[W]`        | `74`  | **ALIGNMENTH**                        | `Left`                       | `string`   |
| `[W]`        | `75`  | **ALIGNMENTV**                        | `Top`                        | `string`   |
| `[W]`        | `76`  | **TEXTALIGNMENTH**                    | `Center`                     | `string`   |
| `[W]`        | `77`  | **TEXTALIGNMENTV**                    | `Center`                     | `string`   |
| `[R-Object]` | `78`  | **MARGIN**                            | `(table) table`              | `table`    |
| `[R-Object]` | `79`  | **INTERACTIVEAREAEXTENSION**          | `(table) table`              | `table`    |
| `[W]`        | `80`  | **SCROLLEVENTVERTICALSCROLLENTITY**   | `0`                          | `number`   |
| `[W]`        | `81`  | **SCROLLEVENTVERTICALFACTOR**         | `1.0`                        | `number`   |
| `[R-Object]` | `82`  | **PLUGINCOMPONENT**                   | `(userdata) Menu 575.2`      | `userdata` |
| `[R]`        | `83`  | **HASFOCUS**                          | `false`                      | `boolean`  |
| `[W]`        | `84`  | **HIDEFOCUSFRAME**                    | `false`                      | `boolean`  |
| `[W]`        | `85`  | **APPEARANCESOURCECLASSNAME**         | `""`                         | `string`   |
| `[W]`        | `86`  | **VISIBLEONLYINALPHA**                | `false`                      | `boolean`  |
| `[W]`        | `87`  | **VISIBLEONLYINBETA**                 | `false`                      | `boolean`  |
| `[W]`        | `88`  | **VISIBLEONLYINRELEASE**              | `false`                      | `boolean`  |
| `[W]`        | `89`  | **VISIBLEONLYINDEBUG**                | `false`                      | `boolean`  |
| `[W]`        | `90`  | **CLICKNEAREST**                      | `false`                      | `boolean`  |
| `[W]`        | `91`  | **VISIBLEINALPHA**                    | `true`                       | `boolean`  |
| `[W]`        | `92`  | **VISIBLEINBETA**                     | `true`                       | `boolean`  |
| `[W]`        | `93`  | **VISIBLEINRELEASE**                  | `true`                       | `boolean`  |
| `[R-Event]`  | `94`  | **CLICKED**                           | `(table) PropertyInvokeMeta` | `table`    |
| `[R-Event]`  | `95`  | **CLICKEDLEFT**                       | `(table) PropertyInvokeMeta` | `table`    |
| `[R-Event]`  | `96`  | **CLICKEDRIGHT**                      | `(table) PropertyInvokeMeta` | `table`    |
| `[R-Event]`  | `97`  | **DOUBLECLICKED**                     | `(table) PropertyInvokeMeta` | `table`    |
| `[R-Event]`  | `98`  | **MOUSEENTER**                        | `(table) PropertyInvokeMeta` | `table`    |
| `[R-Event]`  | `99`  | **MOUSELEAVE**                        | `(table) PropertyInvokeMeta` | `table`    |
| `[R-Event]`  | `100` | **MOUSEOVERHOLD**                     | `(table) PropertyInvokeMeta` | `table`    |
| `[R-Event]`  | `101` | **MOUSEUP**                           | `(table) PropertyInvokeMeta` | `table`    |
| `[R-Event]`  | `102` | **MOUSEUPLEFT**                       | `(table) PropertyInvokeMeta` | `table`    |
| `[R-Event]`  | `103` | **MOUSEUPRIGHT**                      | `(table) PropertyInvokeMeta` | `table`    |
| `[R-Event]`  | `104` | **MOUSEDOWN**                         | `(table) PropertyInvokeMeta` | `table`    |
| `[R-Event]`  | `105` | **MOUSEDOWNLEFT**                     | `(table) PropertyInvokeMeta` | `table`    |
| `[R-Event]`  | `106` | **MOUSEDOWNRIGHT**                    | `(table) PropertyInvokeMeta` | `table`    |
| `[R-Event]`  | `107` | **MOUSEDOWNHOLD**                     | `(table) PropertyInvokeMeta` | `table`    |
| `[R-Event]`  | `108` | **KEYDOWN**                           | `(table) PropertyInvokeMeta` | `table`    |
| `[R-Event]`  | `109` | **KEYUP**                             | `(table) PropertyInvokeMeta` | `table`    |
| `[R-Event]`  | `110` | **CHARINPUT**                         | `(table) PropertyInvokeMeta` | `table`    |
| `[R-Event]`  | `111` | **TOUCHSTART**                        | `(table) PropertyInvokeMeta` | `table`    |
| `[R-Event]`  | `112` | **TOUCHUPDATE**                       | `(table) PropertyInvokeMeta` | `table`    |
| `[R-Event]`  | `113` | **TOUCHEND**                          | `(table) PropertyInvokeMeta` | `table`    |
| `[R-Event]`  | `114` | **ONLOAD**                            | `(table) PropertyInvokeMeta` | `table`    |
| `[R-Event]`  | `115` | **ONVISIBLE**                         | `(table) PropertyInvokeMeta` | `table`    |
| `[R-Event]`  | `116` | **DESCRIPTIONCHANGED**                | `(table) PropertyInvokeMeta` | `table`    |
| `[R-Event]`  | `117` | **FOCUSGET**                          | `(table) PropertyInvokeMeta` | `table`    |
| `[R-Event]`  | `118` | **FOCUSLOST**                         | `(table) PropertyInvokeMeta` | `table`    |
| `[W]`        | `119` | **FORCEINTENSITY**                    | `0`                          | `number`   |
| `[W]`        | `120` | **DEFAULTMARGIN**                     | `0`                          | `number`   |
| `[W]`        | `121` | **COLUMNS**                           | `1`                          | `number`   |
| `[W]`        | `122` | **ROWS**                              | `2`                          | `number`   |
| `[W]`        | `123` | **CELLWIDTH**                         | `0`                          | `number`   |
| `[W]`        | `124` | **CELLHEIGHT**                        | `0`                          | `number`   |
| `[W]`        | `125` | **BLOCKWIDTH**                        | `0`                          | `number`   |
| `[W]`        | `126` | **BLOCKHEIGHT**                       | `0`                          | `number`   |
| `[W]`        | `127` | **EXPANDCONTENT**                     | `false`                      | `boolean`  |
| `[W]`        | `128` | **DEFAULTMARGINONBORDERS**            | `false`                      | `boolean`  |
| `[W]`        | `129` | **ENCODERUSEDISPLAY**                 | `false`                      | `boolean`  |
| `[W]`        | `130` | **ROWREDUCTIONPOLICY**                | `None`                       | `string`   |
| `[W]`        | `131` | **COLREDUCTIONPOLICY**                | `PreferLast`                 | `string`   |
| `[R-Event]`  | `132` | **SETROW**                            | `(table) PropertyInvokeMeta` | `table`    |
| `[R-Event]`  | `133` | **CLOSE**                             | `(table) PropertyInvokeMeta` | `table`    |
| `[R-Event]`  | `134` | **CLOSECONFIRM**                      | `(table) PropertyInvokeMeta` | `table`    |
| `[R-Event]`  | `135` | **CLOSECANCEL**                       | `(table) PropertyInvokeMeta` | `table`    |
| `[W]`        | `136` | **WANTSMODAL**                        | `false`                      | `boolean`  |
| `[W]`        | `137` | **AUTOCLOSE**                         | `true`                       | `boolean`  |
| `[W]`        | `138` | **AUTOCLOSEONOVERLAY**                | `false`                      | `boolean`  |
| `[W]`        | `139` | **CLOSEONESCAPE**                     | `true`                       | `boolean`  |
| `[R-Event]`  | `140` | **MOVE**                              | `(table) PropertyInvokeMeta` | `table`    |
| `[R-Event]`  | `141` | **MOVESTART**                         | `(table) PropertyInvokeMeta` | `table`    |
| `[R-Event]`  | `142` | **RESIZESTART**                       | `(table) PropertyInvokeMeta` | `table`    |
| `[R-Event]`  | `143` | **RESIZE**                            | `(table) PropertyInvokeMeta` | `table`    |
| `[R-Event]`  | `144` | **RESIZEEND**                         | `(table) PropertyInvokeMeta` | `table`    |
| `[W]`        | `145` | **ESCMODALRESULT**                    | `Confirm`                    | `string`   |
| `[W]`        | `146` | **STAYALWAYSVISIBLE**                 | `true`                       | `boolean`  |
| `[W]`        | `147` | **RELATIVETODISPLAY**                 | `false`                      | `boolean`  |
| `[W]`        | `148` | **EDITENCODERBAR**                    | `""`                         | `string`   |
| `[W]`        | `149` | **CONTROLENCODERBAR**                 | `""`                         | `string`   |
| `[W]`        | `150` | **ADJUSTINITIALPOSITION**             | `false`                      | `boolean`  |
| `[R]`        | `151` | **BUDDYGROUPID**                      | `""`                         | `string`   |
| `[R]`        | `152` | **ISMAINBUDDY**                       | `true`                       | `boolean`  |
| `[R-Object]` | `153` | **MAINBUDDY**                         | `(userdata) Display 1.11.3`  | `userdata` |
| `[R-Object]` | `154` | **DEPENDENTBUDDIES**                  | `(table) table`              | `table`    |
| `[W]`        | `155` | **USESIMPLIFIEDRESIZE**               | `false`                      | `boolean`  |
| `[R]`        | `156` | **WORKINGDESTINATION**                | `nil`                        | `unknown`  |
| `[W]`        | `157` | **DRIVERESET**                        | `false`                      | `boolean`  |
| `[W]`        | `158` | **OVERRIDEKEYBSC**                    | `false`                      | `boolean`  |
| `[W]`        | `159` | **FOLLOWPREVIEW**                     | `false`                      | `boolean`  |
| `[W]`        | `160` | **REACTTOEDIT**                       | `false`                      | `boolean`  |
| `[R-Object]` | `161` | **PREVIEWMIXINCOLOR**                 | `(userdata) Color 16.4`      | `userdata` |
| `[R-Object]` | `162` | **EDITMIXINCOLOR**                    | `(userdata) Color 16.5`      | `userdata` |
| `[R-Object]` | `163` | **EDITMIXINNOTOWNERCOLOR**            | `(userdata) Color 16.6`      | `userdata` |
| `[W]`        | `164` | **RETURNDESTINATION**                 | `nil`                        | `unknown`  |
