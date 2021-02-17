# force modeler
generate JSON data schema in a fully keyboard operated webUI

## UI
webui in single html file.

## JSON output
generate JSON from your data model.

## fully keyboard friendly
there is a keyboard way for any thing that this webui can do.

### hotkeys
- Enter: select & make
- Space: make & edit
- Tab Shift+Tab: auto complete
- Del: remove & reset
- Esc: quit
- Left Right Up Down: move
- F2: rename

### changing hotkeys
keys are checked in an `keyup` event handler with `if`s. replace your key name.

## use in your app
you can change and reimplement `saveModel` and `loadModel` functions to integrate this into your app.