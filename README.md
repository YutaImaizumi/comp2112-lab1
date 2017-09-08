# Comp 2112 - Lab1
## Showing how console.table works

I tried to show console.table result by the array data of Japanese highest mountains as an example.

```js
const jpMountains = [
	{'jpMountain' : 'Fuji', 'prefecture' : 'Shizuoka', 'height(m)': 3776},
	{'jpMountain' : 'Kitadake', 'prefecture' : 'Yamanashi', 'height(m)': 3193},
	{'jpMountain' : 'Okuhotakadake', 'prefecture' : 'Nagano', 'height(m)': 3190},
	{'jpMountain' : 'Ainodake', 'prefecture' : 'Yamanashi', 'height(m)': 3189},
	{'jpMountain' : 'Yarigatake', 'prefecture' : 'Nagano', 'height(m)': 3180}
];

console.table(jpMountains);
```

The result table was like below:
![screenshot of console.table](http://yurizm.work/comp2112-lab1.png)
