# Swift in one page

### Language Guide

#### 基础部分(The Basic)
  - Int Double Float Bool String
  - Array Set Dictionary
  - let / var
  - Int() / Double()
  - ? / nil
  - (one, two)
  - assert

#### 基础运算符(Basic Operators)
  - = + - * / %
  - += -= *= /= ++ --
  - == != > < >= <=
  - ?-: ??
  - ... ..<
  - ! && ||

#### 字符串和字符(Strings and Characters)
  - ""/String()
  - char: Character = "!"
  - isEmpty
  - append
  - "\\(str) is a string"
  - characters / characters.count / characters.indices
  - startIndex / endIndex successor / predecessor / advanced
  - insert / insertContentsOf / removeAtIndex / removeRange
  - hasPrefix / hasSuffix

#### 集合类型(Collection Types)
  - 数组(Arrays)
    - Array<Int>() / \[Int\]() / \[3\] / \[Double\](count: 3, repeatedValue: 0.0)
    - count
    - append
    - isEmpty
    - \[1\] + \[2, 3\]
    - \[1, 2, 3, 4\]\[0\] / \[1...3\]
    - insert / removeAtIndex / removeLast
    - for-in / enumerate
  
  - 集合(Sets)
    - strs = Set<String>() / : Set = \["Rock", "Classical", "Hip Hop"\]
    - count
    - isEmpty
    - insert / remove / contains
    - sort
    - for-in
    - intersect / exclusiveOr / union / subtract
    - isSubsetOf / isStrictSubsetOf / isSupersetOf / isStrictSupersetOf / isDisjointWith
  
  - 字典(Dictionaries)
    - dict = \[String: String\]() / \["YYZ": "Toronto Pearson", "DUB": "Dublin"\]
    - count
    - isEmpty
    - \["YYZ": "Toronto Pearson", "DUB": "Dublin"\]\["YYZ"\]
    - updateValue / removeValueForKey
    - for-in
    - keys / values
    - (keys/values).sort
    - \[String\](dict.keys)
    
#### 控制流(Control Flow)
  - for / for-in
  - while / repeat-while
  - if / guard
  - switch / where
  - continue / break / fallthrough / return / throw
  - label
  
#### 函数(Funtions)
  - func sayHello(person: String) -> String {}
  - (to person: String, and anotherPerson: String)
  - (numbers: Double...)
  - (var string: String)
  - (inout a: Int, inout _ b: Int)
  
#### 闭包(Closures )
  - 闭包表达式语法(Closure Expression Syntax)
    - \{ (s1: String, s2: String) -> Bool in return s1 > s2 \}
    - \{ s1, s2 in s1 > s2 \}
    - \{ $0 > $1 \}
    - >
  - 尾随闭包(Trailing Closures)
  - 捕获值(Capturing Values)
  - 非逃逸闭包(Nonescaping Closures)
  - 自动闭包(Autoclosures)
#### 枚举(Enumerations)
  - enum / case
  - rawValue
  - indirect
  
#### 类和结构体(Classes and Structures)
  - class / struct
  - === / !==
  - 结构体和枚举是值类型，类是引用类型
  - String，Array和Dictionary类型均以结构体的形式实现
  
#### 属性(Properties)
  - 存储属性，lazy
  - 计算属性，static / get / set
  - willSet / didSet / newValue / oldValue
  - static
  
#### 方法(Methods)
  - Instance Methods
  - self
  - mutating
  - Type Methods, static
  
#### 下标(Subscripts)
  - subscript / get / set