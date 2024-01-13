## 方法
### charAt()

charAt() 方法从一个字符串中返回指定的字符。

### charCodeAt()

charCodeAt() 方法返回 0 到 65535 之间的整数，表示给定索引处的 UTF-16 代码单元

### concat()

concat() 方法将一个或多个字符串与原字符串连接合并，形成一个新的字符串并返回。

### includes()

includes() 方法执行区分大小写的搜索，以确定是否可以在另一个字符串中找到一个字符串，并根据情况返回 true 或 false。

### endsWith()

endsWith() 方法用来判断当前字符串是否是以另外一个给定的子字符串“结尾”的，根据判断结果返回 true 或 false。

### indexOf()

indexOf() 方法，给定一个参数：要搜索的子字符串，搜索整个调用字符串，并返回指定子字符串第一次出现的索引。给定第二个参数：一个数字，该方法将返回指定子字符串在大于或等于指定数字的索引处的第一次出现。

### lastIndexOf()

lastIndexOf() 方法返回调用String 对象的指定值最后一次出现的索引，在一个字符串中的指定位置 fromIndex处从后向前搜索。如果没找到这个特定值则返回 -1。

该方法将从尾到头地检索字符串 str，看它是否含有子串 searchValue。开始检索的位置在字符串的 fromIndex 处或字符串的结尾（没有指定 fromIndex 时）。如果找到一个 searchValue，则返回 searchValue 的第一个字符在 str 中的位置。str中的字符位置是从 0 开始的。

### localeCompare()

localeCompare() 方法返回一个数字来指示一个参考字符串是否在排序顺序之前、之后或与给定字符串相同。在支持 Intl.Collator API 的实现中，该方法仅是调用了 Intl.Collator 方法。

### match()

match() 方法检索返回一个字符串匹配正则表达式的结果。