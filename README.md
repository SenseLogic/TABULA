![](https://github.com/senselogic/THALIX/blob/master/LOGO/thalix.png)

# Thalix

Tabulated data mixer.

## Output expression

### Line expression

```
<column expression> <column expression>
```

### Column expression

```
<A|B><column index>
<A|B><first column index>:<last column index>
```

The column index starts at one.

If it is negative, it's counted backwards from the last column.

### Sample

```
A2 A-3:-1 B4 B-1
```

Outputs lines made of :
- the second column of the first table;
- the last three columns of the first table;
- the fourth column of the second table;
- the last column of the second table.

## Version

1.0

## Author

Eric Pelzer (ecstatic.coder@gmail.com).

## License

This project is licensed under the GNU General Public License version 3.

See the [LICENSE.md](LICENSE.md) file for details.
