Hooks in Jetpac
================

Sometimes I get tired of digging around on the fly for hook options in Jetpack. This gives me a list to read. If I can get fancy enough with some regex, it might extract all the useful pieces of info about the hook at one point into an automated markdown document. For now it's a list of hooks.

### Commands I'll probably forget or could be written better by others (Help!)

* `awk 'gsub(/.*apply_filters\( '"'"'|'"'"'.*/,"")'` filters the raw list from the original `ack apply_filters(\()`
* `awk 'gsub(/.*do_action\( '"'"'|'"'"'.*/,"")'` filters the raw list from the original `ack do_action(_ref|\()`
