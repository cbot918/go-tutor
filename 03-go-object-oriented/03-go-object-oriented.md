## Go Basic
Golang 在學習時, 主要掌握
1. error handle
2. struct 
3. composite object orient
4. json處理
就可以以一個比較容易的方式快速上手
但以下會從基礎開始介紹



## Golang一些常用特性
1. 類型推導
2. 變數及函式名稱開頭大寫表示public, 小寫private


## 標準輸出print
```go
// 印一行
fmt.Println("hello world")

// format print %s是指字串 \n是換行
a := "hello"
b := "world"
fmt.Printf("%s %s\n", a, b)
```


自己常用到 
struct
```go
type struct Persion{
  Name string
  Job string
}

person1 := Person{
  Name: "yale",
  Job: "student",
}

fmt.Println(person1)

```

array