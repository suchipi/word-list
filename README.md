# word-list

List of valid English words as a UMD module.

Available as an array of strings (`dist/array.js`) or an Object with words as keys and `true` as values for each key (`dist/object.js`).

All words are lowercase.

In non-CommonJS/AMD environments, loads as global `WordListArray` or `WordListObject`.

## Development

Code is generated from `list.txt` by running `./build`.

## Contributing

Add lowercase words to `list.txt` that are missing, run `./build`, then make a pull request.
