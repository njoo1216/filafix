# SMT Z3 Fil-a-Pix SOLVER

Fill-a-Pix is to figure out whether the color of each cell of a N×M grid is White or Black, based on given clues. This program wil give you a solution of this puzzle.

## How To Use

### 1.Input
You can change the input file name, but input file should be followed this form:
- Every cells should be sperated by a space character(' '). 
- Unknwon cells which has no assigned value should be filled with question mark('?').
- Pre-assigned cells should be filled with the assigned number.

```bash
? ? ? ? ?
? 9 ? ? ?
? 8 8 ? ?
? ? ? ? 4
4 ? 5 ? 2
```

### 2.Output/Result
If there is a solution that is satisfiable with input, 
then it will show output on linux terminal as following:
- Cells assigned as Black is represented as '1'.
- Cells assigned as White is represented as '0'.

```bash
1 1 1 0 0
1 1 1 1 0
1 1 1 1 1
1 1 0 1 0
1 1 1 1 0

1 1 1 1 0
1 1 1 1 0
1 1 1 1 1
1 1 0 1 0
1 1 1 1 0

.
.
.
```
- If there is no solution, it will print out "No solution".
- If there are mutiple solutions, it will print out solutions up to 5.

### 3.Command



## Usage

```python
import foobar

foobar.pluralize('word') # returns 'words'
foobar.pluralize('goose') # returns 'geese'
foobar.singularize('phenomena') # returns 'phenomenon'
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)-
