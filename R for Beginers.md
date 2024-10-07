# Variables

```{r}
model1<-'hello'
typeof(model1)

class(model1)

model1

# Model1 就不行 Error: object 'Model1' not found

hello_string<-'hello'
hello_string
# string 是字符串的意思

helloString<-'real hello'
helloString

# 2pairs<-100
#Error: unexpected symbol in "2pairs"
# 因为在R 语言中 数字不能作为开头

# .2pairs<-100
# Error: unexpected symbol in ".2pairs"
# 因为在R 语言中 . 之后一般跟的是字母

.pairs<-100
.pairs
# 所以说 这个就行了

# first num<-100
# Error: unexpected symbol in "first num"
# 因为在变量名中永远没有空格

first_num<-100
first_num

# 变量名称一般都是有意义的，不然会造成很多ambiguity a.模棱两可的 或者含糊不清的

bird <- 'tiger'
bird
# make no sense
animal <- 'tiger'
animal

```
