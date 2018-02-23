# VSCode-Stuff 

фичи для VS Code, сниппеты и прочее.
 
<h3>Snippets/Java.json</h3>
 
<br>
 <pre>VSCode -> F1 -> User Snippets -> java.json <br></pre>
<br>
  
Эти сниппеты позволяют кратко описывать Java-структуры на манер Emmet и получать их мгновенную генерацию. Планируется внедрить скрипты на TypeScript. Например:

| Сниппет | Результат |
| :---: | --- |
| +:  | <pre>public 'type' 'name'</pre> |
| /:  | <pre>protected 'type' 'name'</pre> |
| -$: | <pre>private static 'type' 'name'</pre> |
| -$!: | <pre>private static final 'type' 'NAME' = 'value' |
| +() | <pre>public 'void' 'funcName' ('params') { } </pre> |
| -$() | <pre>private static 'void' 'funcName' ('params') { } </pre> |
| /?() | <pre>protected abstract 'void' 'funcName' ('params'); </pre> |


Семантическое значение модификаторов:

| Модификаторы | Значение |
| :---: | --- |
| + | <b>public</b> |
| / | <b>protected</b> |
| - | <b>private</b> |
| $ | <b>static</b> |
| ! | <b>final</b> |
| ? | <b>abstract</b> | 

Семантическое значение структур:

| Объект | Значение |
| :---: | :---: |
| : | поле |
| () | метод |

