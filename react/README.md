# React.js

## Problem

`Franc` is a library which guesses at the language of a phrase. For
instance, `franc.all('O Brasil caiu 26 posições');` will return an array
that looks like this:

```
/*
 * [
 *  [ 'por', 1 ],
 *  [ 'src', 0.8948665297741273 ],
 *  [ 'glg', 0.8862422997946612 ],
 *  [ 'snn', 0.8804928131416838 ],
 *  [ 'bos', 0.8394250513347022 ],
 *  [ 'hrv', 0.8336755646817249 ],
 *  [ 'lav', 0.833264887063655 ],
 *  [ 'cat', 0.8303901437371664 ],
 *  [ 'spa', 0.8242299794661191 ],
 *  [ 'bam', 0.8242299794661191 ],
 *  [ 'sco', 0.8069815195071869 ],
 *  [ 'rmy', 0.7839835728952772 ],
 *   ...
 * ]
 */
 ```

(`[ 'spa', 0.8242299794661191 ]` means 'spanish' with 82% confidence)
 
For this problem, build a page with a single input for the user to
enter phrases, and a single table which displays the results that Franc
returns.
