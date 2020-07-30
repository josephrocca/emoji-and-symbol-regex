# JS regex for matching emojis and symbols

A regex to match emojis and symbols like ♘♬☾☤♪♇☛☌☧★ which aren't technically emojis. It's based on @mathiasbynens/emoji-regex.

It doesn't include symbols like # as emojis, because that's a bit silly (apparently they are technically emojis with a default tectual representation according to the spec - read more here: https://github.com/mathiasbynens/emoji-regex/issues/33).

Thanks to @gilmoreorless, it also fixed this issue: https://github.com/mathiasbynens/emoji-regex/issues/28
