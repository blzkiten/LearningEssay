#PHP Note

## 語法

### `array_unique()`
同index的重複value只保留一個   

		$a = [1,2,2,3];   
		$b = [
			['neo'] => [4,5,5,6,7,7]
		];
		$a1 = array_unique($a);
		$b1 = array_unique($b);
		// $a1 = [1,2,3]
		// $b1 = [
		//    ['neo'] => [4,5,6,7]
		// ]

