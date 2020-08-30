## 需求说明

### 完成下列选择题，请将答案写到每题后面括号里

1.在下列选择器中，哪一个代表 section class 里面的所有 title class? (A)

A <lable>.section .title {}</lable>  
B <lable>.section.title {}</lable>  
C <lable>.section, .title {}</lable>  
D <lable>.section > .title {}</lable>  


2.在下列选择器中，哪一个代表 section class 内部紧邻的 title class? (D)

A <lable>.section .title {}</lable>  
B <lable>.section.title {}</lable>   
C <lable>.section, .title {}</lable>   
D <lable>.section > .title {}</lable>  


3.在下列选择器中，哪一个代表同一个元素同时拥有 section 和 title 两个class? (B)

A <lable>.section .title {}</lable>  
B <lable>.section.title {}</lable>   
C <lable>.section, .title {}</lable>   
D <lable>.section > .title {}</lable>   



4.在下列选择器中，哪一个代表 section 和 title 两个class 设置相同样式? (C)

A <lable>.section .title {}</lable>  
B <lable>.section.title {}</lable>   
C <lable>.section, .title {}</lable>   
D <lable>.section > .title {}</lable>   



5.在下列CSS选择器中，优先级从高到低是：(2)
```
<div class="section">
    <h1 id="title" class="title">title</div>
</div>

A)  .section .title { color:red; }
B)  #title { color:green; }
C)  .title { color:yellow !important; }
D)  .section > h1 { color:blue; }
```
1)  <lable> B > C > D > A </lable>   
2)  <lable> C > B > A > D </lable>    
3)  <lable> D > B > A > C</lable>  
4)  <lable> 以上都不对 </lable>  

  
  
## 本练习知识点

- CSS can change the look of HTML elements. In order to do this, CSS must select HTML elements, then apply styles to them.
- CSS can select HTML elements by tag, class, or ID.
- Multiple CSS classes can be applied to one HTML element.
- Classes can be reusable, while IDs can only be used once.
- IDs are more specific than classes, and classes are more specific than tags. That means IDs will override any styles from a class, and classes will override any styles from a tag selector.
- Multiple selectors can be chained together to select an element. This raises the specificity, but can be necessary.
- Nested elements can be selected by separating selectors with a space.
- The `!important` flag will override any style, however it should almost never be used, as it is extremely difficult to override.
- Multiple unrelated selectors can receive the same styles by separating the selector names with commas.

