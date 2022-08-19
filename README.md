# Задачі
Дані для задач:
<pre>
const numbers =  [1, -2, 3, 0, 4, -5, 6, -11];

const pupils = [
  {name: 'John', score: 2},
  {name: 'Pete', score: 10},
  {name: 'Mary', score: 8},
  {name: 'Max', score: 12}
];

const students = [
   {
      'id': 001,
      'f_name': 'Alex',
      'l_name': 'B',
      'gender': 'M',
      'married': false,
      'age': 22,
      'paid': 250,  
      'courses': ['JavaScript', 'React']
   },
   {
      'id': 002,
      'f_name': 'Pete',
      'l_name': 'M',
      'gender': 'M',
      'married': true,
      'age': 32,
      'paid': 150,  
      'courses': ['JavaScript', 'PWA']
   },
   {
      'id': 003,
      'f_name': 'Rubi',
      'l_name': 'S',
      'gender': 'F',
      'married': false,
      'age': 24,
      'paid': 350,  
      'courses': ['Blogging', 'React', 'UX']
   },
   {
      'id': 004,
      'f_name': 'Zack',
      'l_name': 'F',
      'gender': 'M',
      'married': true,
      'age': 45,
      'paid': 250,  
      'courses': ['Git', 'React', 'Branding']
   } 
];

const user =  {
      'id': 004,
      'f_name': 'Zack',
      'l_name': 'F',
      'gender': 'M',
      'married': true,
      'age': 45,
      'paid': 250,  
      'courses': ['Git', 'React', 'Branding']
   }
</pre>
<ol>
<li>
  Даний масив numbers. <br>
  Залишити в ньому тільки додатні числа, а потім кожен елемент масиву піднести до квадрату.<br>
  Записати файл як js_abs.js</br>
  </li>

<li>Задано об'єкт pupils, що показує учнів та їх рівень успішності. <br>
  Створити масиви, що будуть мати назву рівні знань. (Низький, Середній, Достатній, викокий). <br>
  Ці масиви мають містити імена дітей, згідно з їх рівнем знань.<br>
  Записати файл як js_score.js<br>
</li>
  <li>
  Є масив студентів students. 
  Треба вивести в окремий масив імена тих студентів, що вивчають курс 'React'. <br>
  Порахувати, скільки всі студенти заплатили всього грошей за свое навчення. <br>
  Створити новий масив, який буде містити імена разом з прізвищами студентів. <br>
  Якщо студент старше 25 років, то додати до його існуючих предментів ще 'Algoritms'.<br>
  Перевірити, якщо у студента буде більше, ніж 3 предмета - то видалили предмет 'Branding'.<br>
  Додати до учня нову властивість 'score' Порівняти імена у об'єкті pupils та масиві students. Якщо є однакове ім'я в цих двох масивах - взяти значення властивосты 'score' та додати її до студента. Якщо нема такого імені і в pupils і в students - написати в 'score' 0.<br>
  Додати до об'єкта <i>user</i> новий метод, який буде називатись mySelf. Цей метод буде виводити в консоль повідомлення про кожного учня. <br>
  Приклад:
  <i> Hello! I am <b> Alex B </b> ! I have <b> 22 </b> years old. And I love JavaScript! </i>. <br>
  Цей метод повинен містити у собі 'f_name', 'l_name', 'age'. Як на прикладі. <br>
  Записати файл як js_students.js<br>
    </li>
    
</ol>

<h3>DOM, BOM</h3>
<p>У замовника є на ступні дані:</p> 
<pre>
const devices = ['mobile', 'tablet', 'desktop'];

const colourDevices = [{'tablet' : 'red'}, {'mobile' : 'green'}, {'desktop' : 'blue'}];

const linksDevices =  [{'tablet' : 'https://en.wikipedia.org/wiki/Tablet_computer'},
{'mobile' : 'https://en.wikipedia.org/wiki/Mobile_device'},
{'desktop' : 'https://en.wikipedia.org/wiki/Laptop'}];

const browsers = ['Opera', 'Chrome', 'Safari', 'Firefox', 'other'];

@media screen and (max-width: 991px) {
/* start of desktop styles */
}

@media screen and (max-width: 767px) {
/* start of medium tablet styles */
}

@media screen and (max-width: 479px) {
/* start of phone styles */
}
</pre>
Замовник хоче, аби після запуска сторінки відображалась:<br>
інформація про браузер (змінна browsers. Знайти свій браузер треба через navigator.userAgent),<br>
формат девайсу (змінна devices, свій девайс треба знайти самому за допомогою інформації з медіа-запитів вище та об'єкту screen ), <br>
формат орієнтаціі девайсу (треба знайти. Вона може бути portrait/landscape. Object = screen). <br>
Інформація про колір сторінки для конкретного девайсу знаходиться у змінній colourDevices. <br>
Після запуска сторінки у новій вкладці потрібно щоб запускались посилання для конкретних девайсів (змінна linksDevices).<br><br>

Інформація має бути записана таким чином:<br>
<i>Hello user! Your device is mobile. Your device orientation is portrait. Browser is Chrome. </i><br>
Замовник захотів додати ще одну умову, якщо юзер відкриє браузер Chrome через свій мобільний пристрій через альбомну орієнтацію - фарбувати сторінку кольором 'aqua' <br>
Записати та зберегти файл як js_bom.js<br>
