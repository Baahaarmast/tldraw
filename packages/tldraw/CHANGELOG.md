# Changelog

## 1.18.2

### Patch Changes

- Improve page reordering, add german translation
- Updated dependencies
  - @tldraw/core@1.14.1

## 1.18.1

### Patch Changes

- Add additional translations.

## 1.18.0

### Minor Changes

- 8ef86c19: - Updates multiplayer implementation.
  - Adds translation guide.
  - Fixes bug on text shape
  - Updates undo redo for text shapes.

## 1.17.2

### Patch Changes

- Replace multiplayer icon.

## 1.17.1

### Patch Changes

- Fix clipboard bug in Firefox, add overwite option to `insertContent`.

## 1.17.0

### Minor Changes

- Add getContent / insertContent, improve copy and paste position logic

## 1.16.0

### Minor Changes

- d919bd27: Bump dependencies, add international support.

### Patch Changes

- Add internationalization, improve readonly mode, bump dependencies for React 18
- Updated dependencies [d919bd27]
- Updated dependencies
  - @tldraw/core@1.14.0

## 1.16.0-next.0

### Minor Changes

- Bump dependencies, add international support.

### Patch Changes

- Updated dependencies
  - @tldraw/core@1.14.0-next.0

## 1.15.1

### Patch Changes

- Improve eraser scribble.
- Updated dependencies
  - @tldraw/core@1.13.1

## 1.15.0

### Minor Changes

- Add erase line, bump dependencies.

### Patch Changes

- Updated dependencies
  - @tldraw/core@1.13.0

## 1.14.2

### Patch Changes

- Fix keyboard events when style menu is open.

## 1.14.1

### Patch Changes

- Move style panel to right corner.

## 1.14.0

### Minor Changes

- Add option to keep style panel open.

## 1.13.0

### Minor Changes

- Fixes zooming and pinching bugs. Adds ErrorBoundary to Tldraw component. Cleans up sponosrship feature in menu.

### Patch Changes

- Updated dependencies
  - @tldraw/core@1.12.0

## 1.12.6

### Patch Changes

- Improve image export for files that include scaled or rotated text.

## 1.12.5

### Patch Changes

- Improve clipboard, SVG text.
- Updated dependencies
  - @tldraw/core@1.11.1

## 1.12.4

### Patch Changes

- Fix export on dark mode.

## 1.12.3

### Patch Changes

- Fix clipboard events in editing text in vscode extension, fix outline for editing text in vscode extension.

## 1.12.2

### Patch Changes

- Prevent clipboard events inside of text from reaching the document. Fix various clipboard-related bugs in tldraw.
- Updated dependencies
  - @tldraw/core@1.11.0

## 1.12.1

### Patch Changes

- Fix tldraw assets for vscode extension.

## 1.12.0

### Minor Changes

- This update changes how clipboard actions (cut, copy, paste) and exports work. Significantly, image exports are no longer handled via a server-side integration, and are instead handled locally on the client. This allows now for exports in the VS Code extension, as well as greatly simplifying exports for apps that embed the Tldraw React component.

### Patch Changes

- Updated dependencies
  - @tldraw/core@1.10.0

## 1.11.1

### Patch Changes

- Add paste for assets.

## 1.11.0

### Minor Changes

- Replace filehandling code.

## 1.10.0

### Minor Changes

- c09d6a3a: Adds text field for page rename, undo buttons on all screen sizes, arrow behavior with alt key.

## 1.9.3

### Patch Changes

- Fix bug with missing parents / children.

## 1.9.2

### Patch Changes

- Fixes bug that would remove bindings to shapes when grouped.

## 1.9.1

### Patch Changes

- Fix publish version.
- Updated dependencies
  - @tldraw/core@1.9.1

## 1.9.0

### Minor Changes

- - Adds menu item for CAD-selection
  - Adds scrolling to menus
  - Fixes "dot" shapes created when clicking with geometric tools
  - Fixes wrong text bounds when fonts load
  - Adds export to VS Code extension.

### Patch Changes

- Updated dependencies
  - @tldraw/core@1.9.0

## 1.8.1

### Patch Changes

- db93ebcc: Fixes text measurement bug.

## 1.8.0

### Minor Changes

- Improves camera (zoom and pan).

### Patch Changes

- e8dd64ba: Fix text in multiplayer
- Updated dependencies
- Updated dependencies [e8dd64ba]
  - @tldraw/core@1.8.0
  - @tldraw/intersect@1.7.1

## 1.7.0

### Minor Changes

- Update dependencies and monorepo.

### Patch Changes

- Updated dependencies
  - @tldraw/core@1.7.0
  - @tldraw/intersect@1.7.0
  - @tldraw/vec@1.7.0

## 1.6.1

- Fix label colors on arrows and triangles in dark mode
- Fix label wobble on arrows
- Fix debug mode when in production mode

## 1.6.0

- Improve arrow binding.
- Fix bug where input pressure would not be accounted for.
- Fix bug where upload media button would not work on multiplayer.
- Adds sourcemap loader.
- Adds ids to UI components.
- Adds exports.

## 1.5.2

- Fix bounds and snapping on first load.

## 1.5.1

- Fix HTML content in text shape
- Fix text shape bounding box size
- Fix failed call when deleting assets
- Fix crash when alt-click-copying image
- Improves scroll wheel
- Fixes SVGs in multiplayer
- Fixes error on Load/Save
- Fixes bug that could occur when erasing

## 1.5.0

- Fix context menu bug on mobile.
- Support for assets (images and videos) in tldraw multiplayer.
- Support for image exporting in tldraw.
- Breaking change: changed `onImageCreate` and `onImageDelete` props to `onAssetCreate` and `onAssetDelete`.
- Preserve application state between reloads.

## 1.4.3

- Update README
- Update LICENSE year

## 1.4.2

- Fixes a bug where shapes could be deleted during an erasing session
- Fixes a bug where groups could throw an error if a shape was missing

## 1.4.1

- Improves label placement, indicators and colors
- Fixes a bug with missing labels when copying shapes to SVG
- Fixes a bug with font when copying text to SVG
- Fixes a bug with text placement when copying sticky notes to SVG

## 1.4.0

- Fixes bug with black canvas after double reload.
- Fixes rendering bug with tiny images / videos.
- Adds labels to rectangles, triangles, circles, lines and arrows.
- Adds support for performance modes to sessions.

## 1.3.0

- Adds Video and Image shape types.

## 1.2.9

- Improves multiplayer cursor appearance.
- Improves authentication and sponsor-related code.
- Fixes bug where logged-out users could not access multiplayer rooms.
- Fixes bug where sponsors would see sponsor prompt in multiplayer rooms.

## 1.2.7

- Fixes crash due to a missing ID provider.

## 1.2.6

- No minify on bundle.

## 1.2.5

- Triangles!
- Improves selection logic.

## 1.2.4

- Fixes bug with `onPersist`.
- Fixes knock-on bug with VS Code extension not saving.

## 1.2.3

- Updates multiplayer code.

## 1.2.2

- Updates @tldraw/core.

## 1.1.6

- Fix bug when creating arrows and lines.

## 1.1.6

- Adds spellcheck to text and stickies.

## 1.1.6

- Fixes bugs in VS Code extension.

## 1.1.5

- Adds grid, clone handles.

## 1.1.4

- Adds undo and redo buttons at smaller breakpoints.

## 1.1.3

- Adds ability to copying text / sticky notes.
- Adds line tool (an arrow without decorations).
- Fixes bad README links.
- Fixes keyboard shortcuts for tools.
- Adds `onChangePresence` and `onChangePage` for multiplayer.

## 1.1.1

- Adds shift modifier to snap arrows to a 15 degree angle.

## 1.1.0

- Adds text styles (alignment and font family)
- Fixes zoom shortcuts on VS Code extension
- Adds zoom shortcuts for numpad
- Fixes delete keyboard shortcuts on PC

## 1.0.4

- Fixes bug in selected styles menu
- Fixes page options dialog for page rename / delete
- Fixes bug in arrow -> elipse intersections
- Fixes sign in / sign out buttons both appearing
- Fixes line breaks for sticky notes
- Improves performance (related to menu bug above)
- Sets default behavior of copyJson and copySvg when no shapes are selected

## 1.0.3

- Improves compatibility with Create React App.

## 1.0.2

- Bumps rko dependency.

## 1.0.1

- Improves appearance of action menu and delete button while disabled
- Adds "resize from center" for transform sessions. Hold the Alt or Option key while resizing to preserve the selection's center point.

## 1.0.0

Breaking

- Renames many props, components (e.g. `TLDrawState` to `TLDrawApp`)

Improvements

- Updates UI in toolbars, menus.
- Simplifies state and context.
- Adds and updtes tests.
- Renames TLDraw to tldraw throughout the app and documentation.
- Renames TLDrawState to TldrawApp, state to app.
- Improves action menu
- Improves dark colors
- Consolidates style menu
- Fixes performance bug with menus
- Fixes text formatting in Text shapes

New

- Adds shape menu
- Adds eraser tool (click or drag to erase)
- Adds `darkMode` prop for controlling dark mode UI.
- Double-click a tool icon to toggle "tool lock". This will prevent the app from returning to the select tool after creating a shape.

## 0.1.17

- Fixes "shifting" bug with drawing tool. Finally!

## 0.1.13

- Fixes bugs related to `readOnly` mode.

## 0.1.12

- Fixes behavior of context menu.

## 0.1.11

- Fixes appearance of keyboard shortcuts in tooltips.

## 0.1.10

- Fixes spacing in text and sticky shapes.

## 0.1.7

- Fixes text and sticky shapes on iOS.

## 0.1.4

- UI bug fixes.

## 0.1.3

- Update dependencies.

## 0.1.2

- Improve migrations.

## 0.1.1

- Update dependencies.

## 0.1.0

- Mark dependencies as external.
- Revamp UI

## 0.0.133

- Removed libraries (vec, svg, and intersect) to their own repositories.

## 0.0.133

- Migration for bindings.

## 0.0.132

- Fix bug with bounds handles.

## 0.0.131

### TLCore

- Extracted into its own repository (`tldraw/core`) and open sourced! :clap:

### tldraw

- Updated with latest `@tldraw/core`, updated ShapeUtils API.

## 0.0.130

### TLCore

- Major change to ShapeUtils API.

### tldraw

- Rewrite utils with new API.

## 0.0.126

### tldraw

- Swap behavior of command and alt keys in arrow shapes.

## 0.0.125

### tldraw

- Bug fixes.

## 0.0.124

### tldraw

- Fix typings.

## 0.0.123

### tldraw

- Adds bound shape controls.
- Drag a bound shape control to translate shapes in that direction.
- Double click bound shape controls to select shapes in that direction.
- Fix bug in arrow decorations toggle.

## 0.0.122

### tldraw

- Adds snapping for transforming shapes.

## 0.0.121

### Core

- Adds `snapLines`.

### tldraw

- Adds shape snapping while translating. Hold Command/Control to disable while dragging.

## 0.0.120

### tldraw

- Improves rectangle rendering.
- Improves zoom to fit and zoom to selection.

## 0.0.119

### tldraw

- Fixes bug with bound arrows after undo.

## 0.0.118

### Core

- Improves multiplayer features.

### tldraw

- Fixes bugs in text, arrows, stickies.
- Adds start binding for new arrows.
- Adds copy painting (alt + shift + drag).
- Adds side clonig.
- Adds clone dragging.

## 0.0.116

### Core

- Improves rendering on Safari.

### tldraw

- Improves rendering on Safari.
- Minor bug fixes around selection.
- Fixes bug when undoing a newly created shape.

## 0.0.115

### Core

- Adds [side cloning](https://github.com/tldraw/tldraw/pull/149).
- Improves rendering.

### tldraw

- Adds sticky note [side cloning](https://github.com/tldraw/tldraw/pull/149).

## 0.0.114

### tldraw

- Improves fills for filled shapes.

## 0.0.113

### tldraw

- Improves grouping and ungrouping.

## 0.0.112

### tldraw

- Fixes centering on embedded tldraw components.
- Removes expensive calls to window.

## 0.0.111

### tldraw

- Adjust stroke widths and sizes.
- Fixes a bug on very small dashed shapes.

## 0.0.110

### Core

- Adds `user` and `users` props (optional) for multiplayer cursors. This feature is very lightly implemented.

### tldraw

- Adds multiplayer support.
- Adds `showMenu` and `showPages` props.
- Adds `mergeState`, `updateUsers`, and `removeUser` methods.

## 0.0.109

### tldraw

- Bumps perfect-freehand
- Fixes dots for small sized draw shapes

## 0.0.108

- Adds CHANGELOG. Only 108 releases late!

### tldraw

- Fixes a bug with bounding boxes on arrows.
