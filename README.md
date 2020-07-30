(unmaintained, not thoroughly tested)

# JS regex for matching emojis and symbols

A regex to match emojis and symbols like ♘♬☾☤♪♇☛☌☧★ which aren't technically emojis. It's based on @mathiasbynens/emoji-regex.

It doesn't count un-emoji-ish symbols like # as emojis (even though they they are technically emojis with a default textual representation according to the spec - read more here: https://github.com/mathiasbynens/emoji-regex/issues/33).

Thanks to @gilmoreorless, it also fixed this issue: https://github.com/mathiasbynens/emoji-regex/issues/28
