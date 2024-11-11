<h2 class="code-line" data-line-start=0 data-line-end=1 ><a id="___0"></a>Первое занятие. Конспект.</h2>
<p class="has-line-data" data-line-start="2" data-line-end="3"><strong><em>Правила дедлайнов для домашек:</em></strong></p>
<pre><code class="has-line-data" data-line-start="5" data-line-end="9">- Если сдаешь до первого дедлайна то можешь получить все баллы
- Если сдаешь в резервный срок, то уже таких гарантий не будет.
- Если не успеваешь в резервный срок, то баллы сразу режутся пополам
</code></pre>
<h4 class="code-line" data-line-start=10 data-line-end=11 ><a id="____no_classic_Hello_Wordl_10"></a>Что нужно для создания no classic “Hello Wordl!”</h4>
<p class="has-line-data" data-line-start="11" data-line-end="12"><strong><em>Для этого нам потребуется:</em></strong></p>
<pre><code class="has-line-data" data-line-start="13" data-line-end="19">Консоль, powershell, терминал (если Linux).
Создать решение
Создать проект
Собрать проект в сборку и запустить сборку
Profit
</code></pre>
<p class="has-line-data" data-line-start="20" data-line-end="24"><em>Решение (solution)</em> – это большой контейнер для ваших проектов, в C# является файлом с расширением <em>“.sln”</em>.<br>
<em>Проект</em> – одна программная единица, которая может работать (или быть использована другими проектами) автономно или вместе с другими проектами.<br>
<em>Сборка (assembly)</em> – это готовый к “употреблению” проект. Сам по себе проект не работает, его нужно <em>“собрать”</em>.<br>
Решение содержит информацию о всех проектах, а у каждого проекта есть своя сборка.</p>
<h3 class="code-line" data-line-start=25 data-line-end=26 ><a id="____git__25"></a>Начало рыботы с <em>git</em></h3>
<p class="has-line-data" data-line-start="27" data-line-end="28">Для начала стоит внести в <strong><em>git config</em></strong> свое имя и почту, потому что каждый коммит в git содержит эту информацию и она не может быть изменена пойже.</p>
<pre><code class="has-line-data" data-line-start="30" data-line-end="37">git clone - клонирует удаленный репозиторий
git add - добавляет изменения которые попадут в следующий коммит
git commit -m 'text'  - создает новый коммит с некоторым сообщением
git push - передает изменения из локального репозитория в удаленный
git pull - подтягивает актуальную версию ветки из репозитория
git fetch загружает содержимое из удаленого репозитория в локальный
</code></pre>