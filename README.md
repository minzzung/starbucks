# πμΉ νλ‘κ·Έλλ° - νλ‘ νΈμλ

<details>
  
<summary> HTML κ°μ </summary>
<div markdown="1">
  
##  HTML κΈ°λ³Έλ¬Έλ²
### -  μμ
  `<νκ·Έ>λ΄μ©</νκ·Έ>`    
     
##  λΆλͺ¨μ μμ κ΄κ³μ μ΄ν΄
###  
  `<νκ·Έ><νκ·Έ>λ΄μ©</νκ·Έ></νκ·Έ>` : μμ μλ νκ·Έλ μμμμ κ²μ λΆλͺ¨μμ   
####   
   λ€μ¬μ°κΈ° : `tab` , λ΄μ΄μ°κΈ° : `Shift+Tab`   
     
##  λΉ νκ·Έ
###  - λΉ νκ·Έ
  `<νκ·Έ/>`   
###  - κΈ°λ₯μ νμ₯ν νκ·Έ 
  `<νκ·Έ μμ±='κ°'>λ΄μ©</νκ·Έ>` 
#### EX)
  ```HTML
  <img scr="./cat.jpg" alt="κ³ μμ΄"/> 
  <!-- scr: κ²½λ‘ alt: μ΄λ―Έμ§μ μ΄λ¦(λμ²΄ νμ€νΈ)-->
  <input type = "text"/>
  <!--type : λ°μ΄ν°μ νμ "text" :μ¬μ©μμκ² μΌλ° νμ€νΈλ₯Ό μλ ₯λ°λλ€-->
  <input type = "checkbox">
  <!--type : λ°μ΄ν°μ νμ "text" :μ¬μ©μμκ² μ²΄ν¬μ¬λΆλ₯Ό μλ ₯λ°λλ€-->
  ```   
##  κΈμμ μμ
### μμκ° νλ©΄μ μΆλ ₯λλ νΉμ±μΌλ‘ ν¬κ² 2κ°μ§λ‘ κ΅¬λΆν  μ μλ€.   
#### - μΈλΌμΈ(inline)μμ : κΈμλ₯Ό λ§λ€κΈ° μν μμλ€.   
  `<span></span>` : μ½νμΈ  μμ­μ μ€μ νλ μ©λ(λ³Έμ§μ μΌλ‘ μλ¬΄κ²λ λνλμ§ μμ)
  
##### EX) 1 
  

  ```HTML
   <!--HTML-->
   <span>Hello</span><!--λμ΄μ°κΈ°λ‘ ν΄μ-->
   <span>World</span>
  ```    
  ```CSS
  /*CSS*/
  body {
    font-size: 100px; /*κΈμ μ¬μ΄μ¦ μ‘°μ */
  }
  ```    
##### EX) 2  
  `margin` : μμμ μΈλΆ μ¬λ°±μ μ§μ νλ cssμμ±   
  `padding`: μμμ λ΄λΆ μ¬λ°±μ μ§μ νλ cssμμ±    

  
  ```HTML
  <!--HTML-->
  <span style="margin: 20px 20px;">Hello</span>
  <span style="margin: 20px 20px;">World</span>
  
  <!--*λΆκ°λ₯ :: κΈμμμ μμ μμμμ-->
  <span><div></div></span>
  <!--*κ°λ₯ :: κΈμμμ μμ κΈμμμ-->
  <span><span></span></span>
  ```   
  
#### - λΈλ‘(block) μμ : μμ(λ μ΄μμ)λ₯Ό λ§λ€κΈ° μν μμλ€.   
  `<div></div>` : μ½νμΈ  μμ­μ μ€μ νλ μ©λ(λ³Έμ§μ μΌλ‘ μλ¬΄κ²λ λνλμ§ μμ)

##### EX) 1 

  
  ```HTML
   <!--HTML-->
   <div>Hello</div><!--λμ΄μ°κΈ°λ‘ ν΄μ-->
   <div>World</div>
  ```    
##### EX) 2  
  `width` : μμμ κ°λ‘ λλΉλ₯Ό μ§μ νλ cssμμ±     
  `height`: μμμ μλ‘ λλΉλ₯Ό μ§μ νλ cssμμ±    

     
  ```HTML
  <!--HTML-->
  <div style="width: 100px;">Hello</div>
  <div style="height: 40px;">World</div>

  <!--*κ°λ₯ :: λΈλ‘μμ μμ λΈλ‘μμ-->
  <span><div></div></span>
  <!--*κ°λ₯ :: λΈλ‘μμ μμ μΈλΌμΈ(κΈμ)μμ-->
  <span><span></span></span>
  ```       
</div>
</details>

<details>
<summary> HTML ν΅μ¬μ λ¦¬ (μμ νμ) </summary>
<div markdown="1">
  
## ν΅μ¬ μμ μ λ¦¬
###
  - `<div></div>` : (λΈλ‘ μμ μμ) νΉλ³ν μλ―Έκ° μκ³  κ΅¬λΆμ μν μμμ΄λ€
  - `<h1>μ€λμ λ μ¨</h1>` : (λΈλ‘ μμ μμ) μ λͺ©μ μλ―Ένλ μμμ΄λ€. + μ«μκ° μμμλ‘ λ μ€μν μ λͺ©
  - `<p>μ€λΆ μ§μ€νΈμ°, 12νΈ νν λΆμμ€..</p>` : (λΈλ‘ μμ μμ) λ¬Έμ₯μ μλ―Ένλ μμμ΄λ€.
  - ` <img src="img/weather.jpg" alt"12νΈ νν"/>  ` : (μΈλΌμΈ κΈμ μμ) μ΄λ―Έμ§λ₯Ό μ½μνλ μμμ΄λ€..
  <img src="https://user-images.githubusercontent.com/87464723/153823868-1e1d2d85-5019-4ae5-b97d-75a992fed8b4.png" width="200" height="150"/>   
   
  ```HTML
  <div>
    <h1>μ€λμ λ μ¨</h1>
    <img src="img/weather.jpg" alt"12νΈ νν"/>
  </div>
  ```
  
  - `<ul></ul>` : (λΈλ‘ μμ μμ) μμκ° νμμλ λͺ©λ‘μ μ§ν©μ μλ―Ένλ€.
  - `<ol></ol>` : (λΈλ‘ μμ μμ) μμκ° νμν λͺ©λ‘μ μ§ν©μ μλ―Ένλ€.  
  - `<li></li>` : (λΈλ‘ μμ μμ) λͺ©λ‘ λ΄ κ° ν­λͺ©μ μλ―Ένλ€.  
  
   <img src="https://user-images.githubusercontent.com/87464723/153824410-c6c4d6e4-e54d-42cd-9c67-a42d3d245449.png" width="120" height="120"/>   
  
   ```HTML
  <ol>
    <li>μ¬κ³Ό</li>
    <li>λΈκΈ°</li>
    <li>μλ°</li>
    <li>μ€λ μ§</li>
  </ol>
  ```
    
  - `<a href="https://www.naver.com">NAVER</a>` : (μΈλΌμΈ κΈμ μμ) λ€λ₯Έ/κ°μ νμ΄μ§λ‘ μ΄λνλ νμ΄νΌλ§ν¬λ₯Ό μ§μ νλ μμμ΄λ€     
  - `<span></span>` : (μΈλΌμΈ κΈμ μμ) νΉλ³ν μλ―Έκ° μκ³  κ΅¬λΆμ μν μμμ΄λ€   
  
  
    ![image](https://user-images.githubusercontent.com/87464723/153824848-d893903a-3050-44ce-aa88-38a84a4ac3f9.png)

  ```HTML
  <a href="https://www.naver.com">NAVER</a>
  <a href="https://www.google.com">GOOGLE</a>
  ```
  - μμ(νμ€νΈ)λ₯Ό μ΄λ€ μμλ‘ λ¬Άμ΄μ£Όλ (κ°μΈλ) νμλ₯Ό Wrapping(λν)μ΄λΌκ³  λΆλ₯Έλ€.
  
     <img src="https://user-images.githubusercontent.com/87464723/153825403-611a4d0b-6be5-4639-9044-4d9ed786a2f0.png" width="500" height="120"/>   
  ```HTML
  <!--HTML-->
  <p>
    λν΄λ¬Όκ³Ό λ°±λμ°μ΄ λ§λ₯΄κ³  λ³λλ‘
    νλλμ΄ λ³΄μ°νμ¬ <span>μ°λ¦¬λλΌ</span>λ§μΈ 
  </p>
  ```
  ```CSS
  /*CSS*/
  body {
    font-size: 100px; /*κΈμ μ¬μ΄μ¦ μ‘°μ */
  }
  span {
    color : red;
  }
  ```   
  - `</br>` : (μΈλΌμΈ κΈμ μμ) μ€λ°κΏ μμμ΄λ€
  - `<input type="text" value="νν">` : νμ€νΈκ° μλ ₯λλ λΆλΆμ "νν"κ° λ―Έλ¦¬ μλ ₯λμ΄μλ€.
  - `<input type="text" palceholder="μ΄λ¦μ μλ ₯νμμ€">` : μ¬μ©μκ° μλ ₯ν  κ°μ ννΈ
  - `<input type="text" disabled />` : μλ ₯ μμ λΉνμ±ν 
  - `<label></label>` : (μΈλΌμΈ κΈμ μμ) λΌλ²¨ κ°λ₯ μμ(input)μ μ λͺ©μ μλ―Ένλ€.
  
     <img src="https://user-images.githubusercontent.com/87464723/153827120-03ff5d11-bc26-49ca-9e66-e36f9639f69b.png" width="500" height="120"/>
  ```HTML
  <!--HTML-->
  <input type=text value=κΉλ―Όλ
   placeholder="μ΄λ¦μ μλ ₯νμΈμ" disabled/>
   <br>
  <input type="checkbox" />
  Apple
  <label>
    <input type="checkbox" />
    banana
    <input type="radio" />
    fruit
  </label>
  ```  
 ##### table   
  
 ## μ£Όμ
 ### - HTML
    <!--λ΄μ©μ½μ--> `Ctrl+/`, `Cmd+/`
 ### - CSS
    '/*λ΄μ©μ½μ*/' `Ctrl+/`, `Cmd+/`
</div>
</details>

<details>
<summary> CSS κ°μ </summary>
<div markdown="1">
  
## κΈ°λ³Έλ¬Έλ², μ£Όμ
 ### βΎ κΈ°λ³Έλ¬Έλ²   
#### 
  CSSμμ νλ μ­ν μ 
  htmlμμμ κΈ°λ³Έμ μΈ κ΅¬μ‘°λ₯Ό μ€μ λ‘ λ³΄κΈ°μ’κ² κΎΈλ©°μ£Όλ μ­ν μ νλ€. μ€νμΌμ μμνλ€.    
  `μ νμ{ μμ±:κ°; }` μ νμ : μ€νμΌ(css)μ μ μ©ν  λμ   
    ex) `div{   
           color: red;   
           margin: 20px;   
         }`
### βΎ μ£Όμ   
#### /* μ€λͺμμ± */    
   μ£Όμ μμμ '/*'λ‘ μ£Όμ λμ '*/'   
   `Ctrl+/`, `Cmd+/`    
  
## CSS μ μΈ λ°©μ
  
### βΎ λ΄μ₯ λ°©μ
  : <style></style>μ λ΄μ©μΌλ‘ μ€νμΌμ μμ±νλ λ°©μ   
  ```CSS
  <style>
  div{
    color : red;
    margin: 20px;
  }
  </style>
  ```
  
### βΎ μΈλΌμΈ λ°©μ
  :μμμ style μμ±μ μ§μ  μ€νμΌμ μμ±νλ λ°©μ
  ```HTML
  <div style="color: red; margin:20px"></div>
  ```

### βΎ λ§ν¬ λ°©μ
  : <link/>λ‘ μΈλΆ CSSλ¬Έμλ₯Ό κ°μ Έμμ μ°κ²°νλ λ°©μ  
  ```CSS
  /* main.css */
  div{
    color : red;
    margin: 20px;
  }
  ```
  ```HTML
  <!--HTML-->
  link rel="stylesheet" href="./css/main.css">
  ```  
### βΎ @import λ°©μ
  : CSSμ @importκ·μΉμΌλ‘ CSS λ¬Έμ μμμ λ λ€λ₯Έ CSS λ¬Έμλ₯Ό κ°μ Έμ μ°κ²°νλ λ°©μ
  ```HTML
  <!--HTML-->
  link rel="stylesheet" href="./css/main.css">
  ```
  ```CSS
  /* main.css */
  @import url("./box.css");
  div{
    color : red;
    margin: 20px;
  }
  ```
  ```
  /* box.css */
  div{
    background-color : red;
    padding: 20px;
  }
  ```
   
## CSS μ νμ
### βΎ κΈ°λ³Έ μ νμ
  - `*` μ μ²΄ μ νμ : λͺ¨λ  μμλ₯Ό μ ν.EX)
  ```CSS
  /*CSS*/
  *{
    color: red;
  }
  ```
  - `νκ·Έμ΄λ¦`νκ·Έ μ νμ : νκ·Έμ΄λ¦μ΄ liμΈ μμλ₯Ό μ ν.EX)
  ```HTML
  <!--HTML-->
  <li>μ¬κ³Ό</li>
  <li>μ€λ μ§</li>
  ```
  ```CSS
  /*CSS*/
  li{
    color: red;
  }
  ```   
  - `.ν΄λμ€μμ±μ κ°` ν΄λμ€ μ νμ : HTML class μμ±μ κ°μ΄ liμΈ μμλ₯Ό μ ν.EX)
  ```HTML
  <!--HTML-->
  <li class = "orange">μ€λ μ§</li>
  <span class = "orange">μ€λ μ§</span>
  ```
  ```CSS
  /*CSS*/
  .orange{
    color: red;
  }
  ``` 
  - `#idμμ±μ κ°` μμ΄λ μ νμ : HTML it μμ±μ κ°μ΄ orangeμΈ μμλ₯Ό μ ν.
  EX)
  ```HTML
  <!--HTML-->
  <li id = "orange">μ€λ μ§</li>
  <span class = "orange">μ€λ μ§</span>
  ```
  ```CSS
  /*CSS*/
  #orange{
    color: red;
  }
  ``` 
### βΎ λ³΅ν©
  - `νκ·Έ μ΄λ¦κ³Ό ν΄λμ€ μμ±μ κ°` μΌμΉ μ νμ : μ νμ spanμ orangeλ₯Ό λμμ λ§μ‘±νλ μμ μ ν.
  EX)
  ```HTML
  <!--HTML-->
  <li id = "orange">μ€λ μ§</li>
  <span class = "orange">μ€λ μ§</span>
  ```
  ```CSS
  /*CSS*/
  span.orange{
    color: red;
  }
  ``` 
  - `νκ·ΈλΆλͺ¨ >. ν΄λμ€ μμ±μ κ°` μμ μ νμ : μ νμ ulμ μμ μμ orangeλ₯Ό μ ν.
  EX)
  ```HTML
  <!--HTML-->
  <ul>
    <li id = "orange">μ€λ μ§</li>
  </ul>
  ```
  ```CSS
  /*CSS*/
  ul > .orange{
    color: red;
  }
  ``` 
  - `μ‘°μμμνκ·Έ >.νμμμν΄λμ€ μμ±μ κ°` νμ(νμ)μ νμ : μ νμ divμ νμ μμ orangeλ₯Ό μ ν.
  EX)
  ```HTML
  <!--HTML-->
  <div>
    <ul>
      <li id = "orange">μ€λ μ§</li><!--μ ν-->
    </ul>
    <div>λΉκ·Ό</div>
    <span class="orange">μ€λ μ§</span><!--μ ν-->
  </div>
  ```
  ```CSS
  /*CSS*/
  div .orange{
    color: red;
  }
  ``` 
  - `.ν΄λμ€ μμ±μ κ° + λ€μνκ·Έ` μΈμ  νμ  μ νμ : μ νμ ulμ λ€μ νμ μμ li νκ·Έ νλλ₯Ό μ ν.
  EX)
  ```HTML
  <!--HTML-->
  <ul>
    <li id = "orange">μ€λ μ§</li>
    <li>λ§κ³ </li>  <!--μ ν-->
    <li>μ¬κ³Ό</li>
  </ul>
  ```
  ```CSS
  /*CSS*/
  .orange + li {
    color: red;
  }
  ``` 
  - `.ν΄λμ€ μμ±μ κ° ~ λ€μνκ·Έ` μΌλ° νμ  μ νμ : μ νμ ulμ λ€μ νμ μμ li νκ·Έ λͺ¨λ μ ν.
  EX)
  ```HTML
  <!--HTML-->
  <ul>
    <li id = "orange">μ€λ μ§</li>
    <li>λ§κ³ </li>  <!--μ ν-->
    <li>μ¬κ³Ό</li>  <!--μ ν-->
  </ul>
  ```
  ```CSS
  /*CSS*/
  .orange ~ li {
    color: red;
  }
  ``` 
### βΎ κ°μ ν΄λμ€
  
  - `μ νμ:hover` κ°μ ν΄λμ€ μ νμ hover : μ νμμμμ λ§μ°μ€ μ»€μκ° μ¬λΌκ° μλ λμ μ ν.
  EX)  
  ![image](https://user-images.githubusercontent.com/87464723/154221384-88efd8de-20be-41e5-b7cf-9a6efd382c09.png)

  ```HTML
  <!--HTML-->
  <a href="https://www.naver.com">NAVER</a>
  ```
  ```CSS
  /*CSS*/
  a:hover {
    color: red;
  }
  ``` 
  
  - `μ νμ:active` κ°μ ν΄λμ€ μ νμ ACTIVE : μ νμ μμμ λ§μ°μ€λ₯Ό ν΄λ¦­νκ³  μλ λμ μ ν.
  EX)   
  ```HTML
  <!--HTML-->
  <a href="https://www.naver.com">NAVER</a>
  ```
  ```CSS
  /*CSS*/
  a:active {
    color: red;
  }
  ```
  
  - `μ νμ:first-child` κ°μ ν΄λμ€ μ νμ FIRST CHILD : μ νμ μμκ° νμ  μμ μ€ μ²«μ§ΈλΌλ©΄ μ ν. 
  EX) μ ν λΆκ°λ₯  

  ```HTML
  <div class="fruits">
    <span>λΈκΈ°</span>
    <span>μλ°</span>
    <div>μ€λ μ§</div>
    <p>λ§κ³ </p>
    <h3>μ¬κ³Ό</h3>
  </div>
  ```
  ```CSS
  /*CSS*/
  .fruits div:first-child {
    color: red;
  }
  ```
  
  - `μ νμ:last-child` κ°μ ν΄λμ€ μ νμ LAST CHILD : μ νμ μμκ° νμ  μμ μ€ λ§λ΄λΌλ©΄ μ ν. 
  EX) 

  ```HTML
  <div class="fruits">
    <span>λΈκΈ°</span>
    <span>μλ°</span>
    <div>μ€λ μ§</div>
    <p>λ§κ³ </p>
    <h3>μ¬κ³Ό</h3> <!--μ ν-->
  </div>
  ```
  ```CSS
  /*CSS*/
  .fruits h3:last-child {
    color: red;
  }
  ```
  
  - `μ νμ:nth-child(n)` κ°μ ν΄λμ€ μ νμ NTH CHILD : μ νμ μμκ° νμ  μμ μ€ (n)μ§ΈλΌλ©΄ μ ν. 
  EX) 

  ```HTML
  <div class="fruits">
    <span>λΈκΈ°</span>
    <span>μλ°</span><!--μ ν-->
    <div>μ€λ μ§</div>
    <p>λ§κ³ </p><!--μ ν-->
    <h3>μ¬κ³Ό</h3> 
  </div>
  ```
  ```CSS
  /*CSS*/
  .fruits *:nth-child(2n) { <!--nμ 0λΆν° μμ-->
    color: red;
  }
  ```
  
  - `μ νμ:not(μ νμ μΈμμ)` λΆμ  μ νμ NOT : μ νμ μΈμμ μλ μ νμ μμ μ ν. 
  EX) 

  ```HTML
  <div class="fruits">
    <span>λΈκΈ°</span>
    <span>μλ°</span>
    <div>μ€λ μ§</div> <!--μ ν-->
    <p>λ§κ³ </p>       <!--μ ν-->
    <h3>μ¬κ³Ό</h3>     <!--μ ν-->
  </div>
  ```
  ```CSS
  /*CSS*/
  .fruits *:not(span) { 
    color: red;
  }
  ```
  
### βΎ κ°μ μμ
  - `μ νμ::before` κ°μμμ μ νμ BEFORE : μ νμ μμμ λ΄λΆ μμ λ΄μ©μ μ½μ.  
  EX)  
![image](https://user-images.githubusercontent.com/87464723/154221516-c9abfc29-9ae2-443b-8e47-876379022207.png)

  ```HTML
  <div class="box">
      Content!
  </div>
  ```
  ```CSS
  /*CSS*/
  .box::before { 
    /*μ΄ λΆλΆμ λ΄μ© μ½μ*/
    content: "μ!";
  }
  ```
  - `μ νμ::after` κ°μμμ μ νμ AFTER : μ νμ μμμ λ΄λΆ λ€μ λ΄μ©μ μ½μ.  
  EX)  
![image](https://user-images.githubusercontent.com/87464723/154221624-98aeb4c2-7066-4daf-be25-b2e320fc11eb.png)

  ```HTML
  <div class="box">
      Content!
  </div>
  ```
  ```CSS
  /*CSS*/
  .box::after { 
    content: "λ€!";
    /*μ΄ λΆλΆμ λ΄μ© μ½μ*/
  }
  ```
    
### βΎ μμ±
 - `[μ νμ]` μμ± μ νμ ATTR : μμ± disabledλ₯Ό ν¬ν¨ν μμ μ ν.  
  EX)  

  ```HTML
  <div class="box"></div>
  <input type="text" value="Min"/>
  <input type="password" value="4665"/>
  <input type="text" value="jung" disabled/>  <!--μ ν-->
  ```
  ```CSS
  /*CSS*/
  [disabled] { 
    color: red;
  }
  ```
  - `[μ νμ]` μμ± μ νμ ATTR=VALUE : μμ± typeμ ν¬ν¨νκ³  κ°μ΄ password μμ μ ν.  
  EX)  

  ```HTML
  <div class="box"></div>
  <input type="text" value="Min"/>
  <input type="password" value="4665"/> <!--μ ν-->
  <input type="text" value="jung" disabled/> 
  ```
  ```CSS
  /*CSS*/
  [type="password"] { 
    color: red;
  }
  ```
## CSS μ€νμΌμμ  
### μ€νμΌ μμ   
  :  μ νλ ν΄λμ€ μμμ cssμ μ©μ νμλ μ μ©λ λ΄μ©μ΄ ν΄λΉνλ μμμ μμμμ, νμμμκΉμ§ μν₯μ λ―ΈμΉλ κ²
  EX)  
![image](https://user-images.githubusercontent.com/87464723/154221737-3bebdcf7-4b1d-43cf-916d-d0a201c9cf40.png) 
  ```HTML
  <div class="ecosystem">μνκ³
    <div class="animal">λλ¬Ό
        <div class="tiger">νΈλμ΄</div>
        <div class="lion">μ¬μ</div>
        <div class="elephant">μ½λΌλ¦¬</div>
    </div>
    <div class="plant">μλ¬Ό</div>
  </div>
  ```
  ```CSS
  /*CSS*/
  .animal { 
    color: red;
  }
  ```
## CSS μ νμ μ°μ μμ
#### μ°μ μμ  
  : κ°μ μμκ° μ¬λ¬ μ μΈμ λμμ΄ λ κ²½μ°, μ΄λ€ μ μΈμ cssμμ±μ μ°μ  μ μ©ν  μ§ κ²°μ νλ λ°©λ²  
  1. μ μκ° λμ μ μΈμ΄ μ°μ   
  2. μ μκ° κ°μΌλ©΄, κ°μ₯ λ§μ§λ§μ ν΄μλ μ μΈμ΄ μ°μ    
 
μ νμ | μμ | μ μ  
--|:--:|--:
μ μ²΄ μ νμ | * | 0
νκ·Έ μ νμ | div | 1
Class μ νμ| .HELLO | 10
ID μ νμ | #hello | 100   
  
 `!impoort μ νμ`: 99999999 μ    
 `μΈλΌμΈ μ νμ` : 1000μ   
 `::before κ°μμ μμ` : 1μ  (νκ·Έμ νμλ‘ λ³Ό μ μλ€.)  
 `:not() λΆμ  μ νμ`: 0μ  (κ°μν΄λμ€μ΄κΈ΄ νμ§λ§ λΆμ μ νμλΌ μ μκ³μ°X) 
  
</div>
</details>

<details>
<summary> CSS μμ± </summary>
<div markdown="1">
 
##  λ°μ€ λͺ¨λΈ  
  
### βΌ width, height   
  μμμ κ°λ‘/μΈλ‘ λλΉ  
####
   - auto(κΈ°λ³Έκ°) : λΈλΌμ°μ κ° λλΉλ₯Ό κ³μ°  
   - λ¨μ : px, em, vw
  
### βΌ max-width, max-height   
  μμκ° μ»€μ§ μ μλ μ΅λ κ°λ‘/μΈλ‘ λλΉ  
####
   - none : μ΅λ λλΉ μ ν μμ  
   - auto : λΈλΌμ°μ κ° λλΉλ₯Ό κ³μ°  
   - λ¨μ : px, em, vw λ± λ¨μλ‘ μ§μ   
  
### βΌ min-width, min-height   
  μμκ° μμμ§ μ μλ μ΅λ κ°λ‘/μΈλ‘ λλΉ  
####
   - 0 : μ΅μ λλΉ μ ν μμ
   - auto : λΈλΌμ°μ κ° λλΉλ₯Ό κ³μ°
   - λ¨μ : px, em, vw λ± λ¨μλ‘ μ§μ   
#### 
  γ° λ¨μ  
κΈ°νΈ | μ€λͺ
--|--
px| ν½μ
% | μλμ  λ°±λΆμ¨
em | μμμ κΈκΌ΄ ν¬κΈ°
rem | λ£¨νΈ μμ(html)μ κΈκΌ΄ ν¬κΈ°
vw | λ·°ν¬νΈ κ°λ‘λλΉμ λ°±λΆμ¨
vh | λ·°ν¬νΈ μΈλ‘ λλΉμ λ°±λΆμ¨

### βΌ margin   
  μΈλΆμ¬λ°±(κ³΅κ°)μ μ§μ νλ λ¨μΆ μμ± (μμ μ¬μ© κ°λ₯)
####
   - 0 : μ΅μ λλΉ μ ν μμ
   - auto : λΈλΌμ°μ κ° μ¬λ°±μ κ³μ° ( κ°μ΄λ°μ λ ¬μμ νμ© )
   - λ¨μ : px, em, vw λ± λ¨μλ‘ μ§μ   
   - % : λΆλͺ¨ μμμ κ°λ‘ λλΉμ λν λΉμ¨λ‘ μ§μ 

### βΌ padding   
  μΈλΆμ¬λ°±(κ³΅κ°)μ μ§μ νλ λ¨μΆ μμ± (μμ ν¬κΈ°κ° μ»€μ§λ€.)
####
   - 0 : λ΄λΆ μ¬λ°± μμ
   - λ¨μ : px, em, vw λ± λ¨μλ‘ μ§μ   
   - % : λΆλͺ¨ μμμ κ°λ‘ λλΉμ λν λΉμ¨λ‘ μ§μ 
  
### βΌ border-width
  μμ νλλ¦¬ μ μ λκ»
####
   - medium : μ€κ° λκ»
   - thin : μμ λκ»
   - thick : λκΊΌμ΄ λκ»
   - λ¨μ : px, em, vw λ± λ¨μλ‘ μ§μ   
  
### βΌ border-style
  μμ νλλ¦¬ μ μ μ’λ₯
####
   - none : μ μμ
   - solid : μ€μ (μΌλ° μ )
   - dashed : νμ 
   - dotted : μ μ 
   - double : λ μ€ μ 
   - groove : νμ΄ νμ¬μλ λͺ¨μ
   - ridge : μμ λͺ¨μ(grooveμ λ°λ)
   - inset : μμ μ μ²΄κ° λ€μ΄κ° λͺ¨μ
   - outset : μμ μ μ²΄κ° λμ¨ λͺ¨μ

### βΌ border-color
  μμ νλλ¦¬ μ μ μμμ μ§μ νλ λ¨μΆ μμ±
####
   - black : κ²μ μ
   - tortkd : μ μ μμ
   - transparent : ν¬λͺ
  
### βΌ border-radius
  μμ λͺ¨μλ¦¬λ₯Ό λ₯κΈκ² κΉμ
####
   - 0 : λ₯κΈκ² μμ
   - λ¨μ: px, em, vwλ± λ¨μλ‘ μ§μ 

### βΌ box-sizing
  μμ ν¬κΈ° κ³μ° κΈ°μ€μ μ§μ 
####
   - content-box : μμμ λ΄μ©(content)λ‘ ν¬κΈ° κ³μ°
   - border-box : μμμ λ΄μ© +padding + borderλ‘ ν¬κΈ° κ³μ°
  
### βΌ overflow
  μμμ ν¬κΈ° μ΄μμΌλ‘ λ΄μ©μ΄ λμ³€μ λ, λ³΄μ¬μ§μ μ μ΄νλ λ¨μΆ μμ±
####
   - visible : λμΉ λ΄μ©μ κ·Έλλ‘ λ³΄μ¬μ€
   - hiddent : λμΉ λ΄μ©μ μλΌλ
   - scroll : λμΉ λ΄μ©μ μλΌλ, μ€ν¬λ‘€λ° μμ±
   - auto : λμΉ λ΄μ©μ΄ μλ κ²½μ°μλ§ μλΌλ΄κ³  μ€ν¬λ‘€λ° μμ±
### βΌ display
  - κ° μμμ μ΄λ―Έ μ§μ λμ΄ μλ κ°
    - block : μμ(λ μ΄μμ) μμ
    - inline : κΈμ μμ
    - inline-block : κΈμ + μμ μμ
  - λ°λ‘ μ§μ ν΄μ μ¬μ©νλ κ°
    - flex : νλ μ€ λ°μ€(1μ°¨μ λ μ΄μμ)
    - grid : κ·Έλ¦¬λ (2μ°¨μ λ μ΄μμ)
    - none : λ³΄μ¬μ§ νΉμ±μμ, νλ©΄μμ μ¬λΌμ§
### βΌ opacity
  μμ ν¬λͺλ
####
   - 1 : λΆν¬λͺ
   - 0~1 : 0λΆν° 1μ¬μ΄μ μμμ  μ«μ
  
## κΈκΌ΄
### βΌ font-style
  κΈμμ κΈ°μΈκΈ°
####
   - normal : κΈ°μΈκΈ° μμ
   - italic : μ΄νλ¦­μ²΄
   - oblique : κΈ°μΈμ΄μ§ κΈμ
  
### βΌ font-weight
  κΈμμ λκ»(κ°μ€μΉ)
####
   - normal,400 : κΈ°μΈκΈ° μμ
   - bold,700 : λκ»κ²
   - boler : μμ(λΆλͺ¨) μμλ³΄λ€ λ λκ»κ²
   - lighter : μμ(λΆλͺ¨) μμλ³΄λ€ λ μκ²
   - 100~900 : 100 λ¨μμ μ«μ 9κ°, normalκ³Ό bold μ΄μΈ λκ»
### βΌ font-size
  κΈμμ ν¬κΈ°
####
   - 16px : κΈ°λ³Έ ν¬κΈ°
   - λ¨μ : px, em, rem λ± λ¨μλ‘ μ§μ 
   - % : λΆλͺ¨ μμμ ν°νΈ ν¬κΈ°μ λν λΉμ¨
   - smaller : μμ(λΆλͺ¨) μμλ³΄λ€ λ μκ²
   - large : μμ(λΆλͺ¨) μμλ³΄λ€ λ ν¬κ²
   - xx-small~xx-large : κ°μ₯ μμ ν¬κΈ° ~ κ°μ₯ ν°ν¬κΈ°κΉμ§, 7λ¨κ³μ ν¬κΈ°λ₯Ό μ§μ 
### βΌ line-height
  ν μ€μ λμ΄, νκ°κ³Ό μ μ¬
####
   - normal : λΈλΌμ°μ μ κΈ°λ³Έ μ μλ₯Ό 
   - μ«μ : μμμ κΈκΌ΄ ν¬κΈ°μ λ°°μλ‘ μ§μ 
   - λ¨μ : px, em, vw λ± λ¨μλ‘ μ§μ   
   - % : μμμ κΈκΌ΄ ν¬κΈ°μ λΉμ¨λ‘ μ§μ 
## λ¬Έμ
### βΌ color
  κΈμμ μμ
####
   - rgb(0,0,0) : κ²μ μ 
   - μμ : κΈ°ν μ§μ  κ°λ₯ν μμ 
### βΌ text-align
  λ¬Έμμ μ λ ¬ λ°©μ
####
   - left : μΌμͺ½ μ λ ¬
   - right : μ€λ₯Έμͺ½ μ λ ¬
   - center : κ°μ΄λ° μ λ ¬
   - justify : μμͺ½ μ λ ¬
### βΌ text-decoration
  λ¬Έμμ μ₯μ(μ )
####
   - none : μ₯μμμ
   - underline : λ°μ€
   - overline : μμ€
   - line-through : μ€μ μ 
### βΌ text-indent
  μ²«μ€μλ€μ¬μ°κΈ°
####
   - 0 : μ₯μμμ
   - λ¨μ : px, em, rem λ± λ¨μλ‘ μ§μ   
   - % : μμμ κ°λ‘ λλΉμ λΉμ¨λ‘ μ§μ 
  
## λ°°κ²½
  
### βΌ background-color
  μμμ λ°°κ²½ μμ
####
   - transparent : ν¬λͺν¨
   - μμ : μ§μ  κ°λ₯ν μμ
### βΌ background-image
  μμμ λ°°κ²½ μ΄λ―Έμ§ μ½μ
####
   - none : ν¬λͺν¨
   - url("κ²½λ‘") : μ΄λ―Έμ§ κ²½λ‘
### βΌ background-repeat
  μμμ λ°°κ²½ μ΄λ―Έμ§ λ°λ³΅
####
   - repeat : μ΄λ―Έμ§λ₯Ό μμ§, μν λ°λ³΅
   - repeat-x : μ΄λ―Έμ§λ₯Ό μν λ°λ³΅
   - repeat-y : μ΄λ―Έμ§λ₯Ό μμ§ λ°λ³΅
   - no-repeat : λ°λ³΅ μμ
### βΌ background-position
  μμμ λ°°κ²½ μ΄λ―Έμ§ μμΉ
####
   - 0% 0% : 0%~100%
   - λ°©ν₯ : top, bottom, left, right, center λ°©ν₯
   - λ¨μ : px, em, rem λ±μΌλ‘ λ¨μ μ§μ 
### βΌ background-size
  μμμ λ°°κ²½ μ΄λ―Έμ§ ν¬κΈ°
####
   - auto : μ΄λ―Έμ§μ μ€μ  ν¬κΈ°
   - λ¨μ : px, em, rem λ±μΌλ‘ λ¨μ μ§μ 
   - cover : λΉμ¨μ μ μ§, μμμ λ λμ λλΉμ λ§μΆ€
   - contain : λΉμ¨μ μ μ§, μμμ λ μ§§μ λλΉμ λ§μΆ€
### βΌ background-attachment
  μμμ λ°°κ²½ μ΄λ―Έμ§ μ€ν¬λ‘€ νΉμ±
####
   - scroll : μ΄λ―Έμ§κ° μμλ₯Ό λ°λΌμ κ°μ΄ μ€ν¬λ‘€
   - fixed : μ΄λ―Έμ§κ° λ·°ν¬νΈμ κ³ μ , μ€ν¬λ‘€ X
   - local : μμ λ΄ μ€ν¬λ‘€ μ μ΄λ―Έμ§κ° κ°μ΄ μ€ν¬λ‘€

## λ°°μΉ
### βΌ position
  μμμ μμΉ μ§μ  κΈ°μ€
####
   - static : κΈ°μ€ μμ
   - relative : μμ μμ μ κΈ°μ€
   - absolute : μμΉ μ λΆλͺ¨ μμλ₯Ό κΈ°μ€
   - fixed : λ·°ν¬νΈ(λΈλΌμ°μ )λ₯Ό κΈ°μ€
   - sticky : μ€ν¬λ‘€ μμ­ κΈ°μ€
### βΌ μμ μμ μμ (Stack order)
  μ΄λ€ μμκ° μ¬μ©μμ λ κ°κΉκ² μλμ§(μμ μμ΄λμ§)κ²°μ 
####
  1. μμμ position μμ±μ κ°μ΄ μλ κ²½μ° μμ μμ. (κΈ°λ³Έκ° static μ μΈ)  
  2. 1λ² μ‘°κ±΄μ΄ κ°μ κ²½μ°, z-index μμ±μ μ«μ κ°μ΄ λμ μλ‘ μμ μμ.
  3. 1λ²κ³Ό 2λ² μ‘°κ±΄κΉμ§ κ°μ κ²½μ°, HTMLμ λ€μ κ΅¬μ‘°μΌ μλ‘ μμ μμ.
### βΌ z-index
  μμμ μμ μ λλ₯Ό μ§μ 
####
  - auto : λΆλͺ¨ μμμ λμΌν μμ μ λ
  - μ«μ : μ«μκ° λμ μλ‘ μμ μμ
## νλ μ€(μ λ ¬)
### βΌ display
  Flexcontainer μ νλ©΄ μΆλ ₯(λ³΄μ¬μ§) νΉμ±
####
  - flex : λΈλ‘ μμμ κ°μ΄ flex container μ μ
  - inline-flex : μΈλΌμΈ μμμ κ°μ΄ flex container μ μ

### βΌ flex-direction
  μ£Ό μΆμ μ€μ 
####
  - row : ν μΆ(μ’=>μ°)
  - row-reverse : ν μΆ(μ°=>μ’)
  - column : μ΄ μΆ(μ=>μλ)
  - column-reverse : μ΄ μΆ (μλ=>μ)
## λ³ν
### βΌ flex-wrap
  Flex Items λ¬Άμ(μ€ λ°κΏ)μ¬λΆ
####
  - nowrap : λ¬Άμ(μ€ λ°κΏ)μμ
  - wrap : μ¬λ¬ μ€λ‘ λ¬Άμ
  - wrap-reverse : wrapμ λ°λ λ°©ν₯μΌλ‘ λ¬Άμ
### βΌ justify-content
  μ£Ό μΆμ μ λ ¬ λ°©λ²
####
  - flex-start : Flex Items μ μμμ μΌλ‘ μ λ ¬
  - flex-end : Flex Items μ λμ μΌλ‘ μ λ ¬
  - center : Flex Items μ κ°μ΄λ° μ λ ¬
  - space-between : κ° Flex Item μ¬μ΄λ₯Ό κ· λ±νκ² μ λ ¬
  - space-around : κ° Flex Itemμ μΈλΆ μ¬λ°±μ κ· λ±νκ² μ λ ¬
### βΌ align-content
  κ΅μ°¨ μΆμ μ¬λ¬ μ€ μ λ ¬ λ°©λ²
####
  - stretch : Flex Items μ μμμ μΌλ‘ μ λ ¬
  - flex-start : Flex Items μ μμμ μΌλ‘ μ λ ¬
  - flex-end : Flex Items μ λμ μΌλ‘ μ λ ¬
  - center : Flex Items μ κ°μ΄λ° μ λ ¬
  - space-between : κ° Flex Item μ¬μ΄λ₯Ό κ· λ±νκ² μ λ ¬
  - space-around : κ° Flex Itemμ μΈλΆ μ¬λ°±μ κ· λ±νκ² μ λ ¬
### βΌ align-items
  κ΅μ°¨ μΆμ ν μ€ μ λ ¬ λ°©λ²
####
  - stretch : Flex Itemsλ₯Ό κ΅μ°¨ μΆμΌλ‘ λλ¦Ό
  - flex-start : Flex Itemsλ₯Ό κ° μ€μ μμμ μΌλ‘ μ λ ¬
  - flex-end : Flex Itemsλ₯Ό κ° μ€μ λμ μΌλ‘ μ λ ¬
  - center : Flex Itemsλ₯Ό κ° μ€μ κ°μ΄λ° μ λ ¬
  - baseline : Flex Itemsλ₯Ό κ° μ€μ λ¬Έμ κΈ°μ€μ μ μ λ ¬
### βΌ order
  Flex Itemμ μμ
####
  - 0 : μμμμ
  - μ«μ : μ«μκ° μμ μλ‘ λ¨Όμ 
### βΌ flex-grow
  Flex Itemμ μ¦κ° λλΉ λΉμ¨
####
  - 0 : μ¦κ° λΉμ¨ μμ
  - μ«μ : μ¦κ° λΉμ¨
### βΌ flex-shrink
  Flex Itemμ κ°μ λλΉ λΉμ¨
####
  - 1 : Flex Container λλΉμ λ°λΌ κ°μ λΉμ¨ μ μ©
  - μ«μ : κ°μ λΉμ¨
### βΌ flex-basis
  Flex Itemμ κ³΅κ° λ°°λΆ μ  κΈ°λ³Έ λλΉ
####
  - auto : μμμ Content λλΉ
  - λ¨μ : px, em, rem λ± λ¨μλ‘ μ§μ 
## μ ν
### βΌ transisiton-property
  μ ν ν¨κ³Όλ₯Ό μ¬μ©ν  μμ± μ΄λ¦μ μ§μ 
####
  - all : λͺ¨λ  μμ±μ μ μ©
  - μμ±μ΄λ¦ : μ ν ν¨κ³Όλ₯Ό μ¬μ©ν  μμ± μ΄λ¦ λͺμ
### βΌ transisiton-duration
  μ ν ν¨κ³Όμ μ§μμκ°μ μ§μ 
####
  - 0s: μ ν ν¨κ³Ό μμ
  - μκ° : μ§μμκ°(S)μ μ§μ 
### βΌ transisiton-timing-function
  μ ν ν¨κ³Όμ νμ΄λ°ν¨μλ₯Ό μ§μ 
####
  - ease : λλ¦¬κ² - λΉ λ₯΄κ² - λλ¦¬κ²
  - linear : μΌμ νκ²
  - ease-in : λλ¦¬κ² - λΉ λ₯΄κ²
  - ease-out : λΉ λ₯΄κ² - λλ¦¬κ²
  - ease-in-out : λλ¦¬κ² - λΉ λ₯΄κ² - λλ¦¬κ²
  - cubic-bezier(n,n,n,n) : μμ λ§μ κ°μ μ μ(0~1)
  - steps(n) : nλ² λΆν λ μ λλ©μ΄μ
### βΌ transisiton-delay
  μ ν ν¨κ³Όκ° λͺ μ΄ λ€μ μμν μ§ λκΈ°μκ°μ μ§μ 
####
  - 0s: λκΈ°μκ° μμ
  - μκ° : λκΈ°μκ°(S)μ μ§μ 
## λμ
### βΌ perspective
  νμ μμλ₯Ό κ΄μ°°νλ μκ·Ό κ±°λ¦¬λ₯Ό μ§μ 
####
  - λ¨μ : pxλ± λ¨μλ‘ μ§μ 
### βΌ backface-visibility
  3Dλ³νμΌλ‘ νμ λ μμμ λ·λ©΄ μ¨κΉ μ¬λΆ
####
  - visible : λ·λ©΄ λ³΄μ
  - hidden : λ·λ©΄ μ¨κΉ
<!-- ## μ λλ©μ΄μ
## κ·Έλ¦¬λ
## λ€λ¨
## νν° -->
   
</div>
</details>

<details>
<summary> JS μ ν </summary>
<div markdown="1">
  
## νκΈ°λ²

###  β» dash - case(kebab-case)
   :  '-'λ₯Ό μ¬μ©ν΄ μ»΄ν¨ν°λ νλλ‘ μΈμνλ λ¨μ΄λ₯Ό μ¬λμ΄ λ³΄κΈ°μ μ¬λ¬ λ¨μ΄λ‘ μ½μ μ μκ² κ΅¬λΆ
####
   ex) the-quick-brown-fox-jumps-over-the-lazy-dog
###  β» snake_case              
   :  '_'λ₯Ό μ¬μ©ν΄ μΈμν  μ μλ μ¬λ¬ λ¨μ΄λ₯Ό νλλ‘ λ¬Άλλ€.
####
   ex) the_quick_brown_fox_jumps_over_the_lazy_dog
###  β» camelCase    
   :  λν νκΈ°λ²μ΄λΌκ³ λ νκ³  λλ¬Έμλ‘ μ¬λ¬ λ¨μ΄λ₯Ό νλμ λ¨μ΄λ‘ μ»΄ν¨ν°μκ² μΈμ μμΌμ€ λ μ¬μ©
####
   ex) theQuickBrownFoxJumpsOverTheLazyDog
###  β» ParcelCase 
   :  camelCaseμ λΉμ·νμ§λ§ μ²μ μ€λ λ¬Έμκ° λλ¬Έμλ‘ μ¬μ©νλ€.
####
   ex) TheQuickBrownFoxJumpsOverTheLazyDog
###  β» Zero-based Numbering
   :  νΉμν κ²½μ°λ₯Ό μ μΈνκ³  0λΆν° μ«μλ₯Ό μμνλ€.
## μ£Όμ  
  - //ν μ€ λ©λͺ¨
  - /* ν μ€ λ©λͺ¨ */
  - /**   
      *μ¬λ¬ μ€ λ©λͺ¨   
      */ (ctrl +'/')   
  
## λ°μ΄ν° μ’λ₯(μλ£ν)
  ###
  - String (λ¬Έμ λ°μ΄ν°) : λ°μ΄νλ₯Ό μ¬μ©νλ€.
 ```javascript
  let myNmae = "mindong";
  let email = 'dullini0205@gmail.com';
  let hello = 'Hello${myName}?!'
  
  console.log(myNmae); // mindong
  console.log(email);  // dullini0205@gmail.com
  console.log(hello);  // Hello  mindong?!
 ```
  - Number (μ«μ λ°μ΄ν°) : μ μ λ° λΆλ μμμ  μ«μλ₯Ό λνλλλ€.
 ```javascript
  let num = 123;
  let opaciy = 1.57;
  
  console.log(num); // 123
  console.log(opaciy);  //1.57
 ```
  - Boolean (λΆλ¦° λ°μ΄ν°) : true,false λ κ°μ§ κ°λ°μ μλ λΌλ¦¬ λ°μ΄ν°μλλ€.
 ```javascript
  let checked = true;
  let isShow = false;
  
  console.log(checked); //true
  console.log(isShow);  //false
 ```
  - Undefined : κ°μ΄ ν λΉλμ§ μμ μνλ₯Ό λνλλλ€.
 ```javascript
  let undef; // κ°μ΄ μλ μνλ₯Ό undefined λΌλ νλμ λ°μ΄ν°λ‘ λνλΈλ€.
  let obj = {abx: 123};
  console.log(undef);   //undefined
  console.log(obj.abx); //123
  console.log(obj.x);   //undefined
 ```
  - Null :  μ΄λ€ κ°μ΄ μλμ μΌλ‘ λΉμ΄μμμ μλ―Ένλ€.
 ```javascript
  let empty = null;
  console.log(empty); // null
 ```
  - Object (κ°μ²΄ λ°μ΄ν°) : μ¬λ¬ λ°μ΄ν°λ₯Ό Key:Value ννλ‘ μ μ₯ν©λλ€. {}
 ```javascript
  let user = {
    //key: Value,
    name : 'min'
    age : 85,
    isValid: true
  };
  console.log(user.name); // min
  ```
  - Array (λ°°μ΄ λ°μ΄ν°) : μ¬λ¬ λ°μ΄ν°λ₯Ό μμ°¨μ μΌλ‘ μ μ₯ν©λλ€.[]
 ```javascript
  let fruits = ['apple','banana','cherry'];
  console.log(fruits[0]); // apple
  ```  
 ## 
  - λ³μλ°μ΄ν°λ₯Ό μ μ₯νκ³  μ°Έμ‘°νλ λ°μ΄ν°μ μ΄λ¦
  - let :  κ°(λ°μ΄ν°)μ μ¬ν λΉ κ°λ₯!
  - const : κ°(λ°μ΄ν°)μ μ¬ν λΉ λΆκ°λ₯!
 ## μμ½μ΄ 
  - νΉλ³ν μλ―Έλ₯Ό κ°μ§κ³  μμ΄, λ³μλ ν¨μ μ΄λ¦λ±μΌλ‘ μ¬μ©ν  μ μλ λ¨μ΄
  - Reserved Word
 ```javascript
  let this = 'hello'; //SyntaxError
  let if = 123; //SyntaxError
 ```
 ## ν¨μ 
  - νΉμ  λμμ μννλ μΌλΆ μ½λμ μ§ν©
  - function
```javascript 
  function helloF(){ //ν¨μ μ μΈ
  //μ€ν μ½λ
  console.log(1234); //λͺλ Ήμ΄ λ€μ΄μλ€
  }
  // ν¨μ νΈμΆ
  helloF(); // 1234
```
  ### 
  - κΈ°λͺ(μ΄λ¦μ΄ μλ) ν¨μ  :: ν¨μλ₯Ό μ μΈνλ€.
  ```javascript
    function hello(){
      console.log('HEllo~');
    }
  hello();
  ```
  ### 
  - μ΅λͺ(μ΄λ¦μ΄ μλ) ν¨μ :: ν¨μλ₯Ό νννλ€.(νΈμΆλΆκ°-> λ°μ΄ν°λ λ³μμ νμ©)
   ``` JAVA 
    let world = function (){
      console.log('MEllo~');
    }
    world();
  ```
 ## μ‘°κ±΄λ¬Έ 
   μ‘°κ±΄(true,false)μ κ²°κ³Όμ λ°λΌ λ€λ₯Έ μ½λλ₯Ό μ€ννλ κ΅¬λ¬Έ  
   ```javascript
    let isShow = true;
    let checked = false;
    
    if(isShow){
      console.log('Show~~'); //Show~~
    }
    if(checked){
    console.log('checked!')//μ€νx
    }
  ```  
 ## DOM API (Document Object Model, Application Programming Interface)    
  μλ°μ€ν¬λ¦½νΈμμ HTMLμ μ μ΄ν  λ μ¬μ©νλ λͺλ Ήλ€μ΄λΌλ μλ―Έμ΄λ€.   
 ```javascript
    // HTML μμ(Element) 1κ° κ²μ/μ°ΎκΈ° (λ¨Όμ  μ°Ύμ μμ 1κ°λ§ λ°ν)
    const boxEl = document.querySelector('.box');

    //HTML μμμ μ μ©ν  μ μλ λ©μλ !
    boxEl.addEventListener();
    //μΈμμΆκ°κ°λ₯
    boxEl.addEventListener(1,2);
    //1 - μ΄λ²€νΈ (Event, μν©)
    boxEl.addEventListener('Click',2);
    //2 - νΈλ€λ¬ (Handler, μ€νν  ν¨μ)
    boxEl.addEventListener('Click',function() {
      console.log('Click~!');
    });
```   
![image](https://user-images.githubusercontent.com/87464723/151526413-64ebca0a-c99e-4e32-9dad-cd50666314ea.png)

```javascript
    // HTML μμ(Element) λͺ¨λ κ²μνκΈ°
    const boxEls = document.querySelectorAll('.box');
    console.log(boxEls);

    // μ°Ύμ μμλ€ λ°λ³΅ν΄μ ν¨μ μ€ν! (μ μ¬λ°°μ΄)
    // μ΅λͺμ ν¨μλ₯Ό μΈμλ‘ μΆκ° 
    boxEls.forEach(funcion() {});
  
    // μ²« λ²μ§Έ λ§€κ°λ³μ(boxEl) : λ°λ³΅ μ€μΈ μμ.
    // λ λ²μ§Έ λ§€κ°λ³μ(index) : λ°λ³΅ μ€μΈ λ²νΈ
    boxEls.forEach(funcion(boxEl, index) {});
  
    // μΆλ ₯!
    // λ°λ³΅νλ©΄μ μ΅λͺμ ν¨μκ° μ€νλλλ° boxEl, indexλ‘ λ΄λΆμμ λ‘μ§μ μΆκ°ν  μ μλ€.
    boxEls.forEach(funcion(boxEl, index) { // boxElμλ λ°λ³΅μ€μΈ νλμ μμκ° λ€μ΄μκ³  
      boxEl.classList.add('order-${index + 1}'); //classListμ μ΄λ€ λ¬Έμλ°μ΄ν° μμλ₯Ό μΆκ°νκ³   indexμ +1ν΄μ λ³΄κ΄
      console.log(index, boxEl); //μ½μμ°½μ index, boxEl κ° μΆλ ₯
    });
```   
  ![image](https://user-images.githubusercontent.com/87464723/151527738-3c3bf134-cca8-46ba-a1c8-38b42aa341bf.png)

```javascript
  const boxEl = document.querySelector('.box');
  
  //Getter, κ°μ μ»λ μ©λ
  console.log(boxEl.textContent); // Box!!
  
  //Setter, κ°μ μ§μ νλ μ©λ
  boxEl.textContent = 'MINZZUNG?!';
  console.log(boxEl.TextContent);
```  
 ## λ©μλ μ²΄μ΄λ  
  λ©μλκ° μ²΄μΈ νμμΌλ‘ μ°κ²°λμ΄μλ€
```javascript
  const a = 'Hello~';
  // split : λ¬Έμλ₯Ό μΈμ κΈ°μ€μΌλ‘ μͺΌκ°μ λ°°μ΄λ‘ λ°ν.
  // reverse : λ°°μ΄μ λ€μ§κΈ°.
  // join : λ°°μ΄μ μΈμ κΈ°μ€μΌλ‘ λ¬Έμλ‘ λ³ν©ν΄ λ°ν.
  const b = a.split('').reverse().join(''); //λ©μλ μ²΄μ΄λ..
  
  console.log(a); // Hello~
  console.log(b); // ~olleH
```
 
</div>
</details>

<details>
<summary> μ€νλ²μ€ μΉμ¬μ΄νΈλ§λ€κΈ° </summary>
<div markdown="1">
 
 ## BEM (Block Element Modifier)
 ### - HTML ν΄λμ€ μμ±μ 
   `μμ__μΌλΆλΆ` : Underscore(Lodash) κΈ°νΈλ‘ μμμ μΌλΆλΆμ νμ   
   `μμ--μν`   : Hyphen(Dash) κΈ°νΈλ‘ μμμ μνλ₯Ό νμ 
    
</div>
</details>
