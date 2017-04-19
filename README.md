# goit_team1
### Задача:
Сверстать страницу согласно макету template/template.png
Цель:
1. Определить текуший уровень знания html/css .
2. Teamwork.
3. Practise.

В качестве руководства, ниже приведен небольшой список паттернов, которые можно использовать в работе.


### Паттерн для блоков:
```
<div class="counts_module"></div>`
```
### Паттерн для хедеров блоков (Как, пример - "Общие друзья: 3"):
```
<a href="#">
   <h3 class="header_top">
     <span class="header_label">Common friends</span>
     <span class="header_count">3</span>
   </h3>
</a>
```
### Паттерн для тела блоков:
```
<div class="module_body"></div>
```
### Паттерн для блока таблички с друзьями:
```
<div class="people_table>
    <div class="people_row">
        <div class="people_cell">
        </div>
    </div>
</div>
```
### Паттерн для элемента таблички с друзьями:
```
<div class="people_cell">
  <a class="people_cell_ava" href="#">
    <img class="people_cell_img" src="source/to/avatar.img" alt="John Doe">
  </a>
  <div class="people_cell_name">
    <a href="#">
      John Doe
    </a>
  </div>
</div>
```
### Паттерн для елемента счетчика:
```
<a class="page_counter" href="#">
  <div class="count">3</div>
  <div class="label">Common friends</div>
</a>
```
### Паттерн для кнопок "Написать сообщение", "Добавить в друзья":
```
<div class="profile_actions">
  <div class="profile_action_btn">
  <div class="clear_fix">
    <a href="/write244544385" class="button_link">
        <button class="flat_button profile_btn">Написать сообщение</button>
    </a>
    <a href="#" class="button_link">
        <button class="flat_button">
            <i class="profile_gift_icon"></i>
            <span class="profile_gift_text">Send gift</span>
        </button>
    </a>
  </div>
</div>
```

### Basic styles:
1. Font colors:
 - inactive font color: "#828282"
 - active font color: "#2a588d"
 - headers color: #000000"

2. Background colors:
 - "#5e81a8"
 - "#ffffff"
 - "#e5ebf1

3. Base font styles:
 - font-size: 13px;
 - font-weight: 400;
 - For social counters:
       font-size: 19px;