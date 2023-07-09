INSTALLED_APPS = [
    'django.contrib.admin',
    'django.contrib.auth',
    'django.contrib.contenttypes',
    'django.contrib.sessions',
    'django.contrib.messages',
    'django.contrib.staticfiles',
]


<form action="">
    <label for="field1">Просто текст</label>
    <input id="field1" type="text" placeholder="что-то"/>

    <label for="field2">Чек-бокс</label>
    <input id="field2" type="checkbox"/>

    <label for="field3">Пароль</label>
    <input id="field3" type="password"/>

    <input type="button" value="Просто кнопка" />

    <textarea name="Text1" cols="40" rows="5"></textarea>
<nav class="nav">
  <a class="nav-link active" href="https://www.google.ru/search?newwindow=1&sxsrf=AB5stBgLPlh6U4d8uBL1jxrB2WzQ4XpLZw:1688636823193&q=коты&tbm=isch&sa=X&ved=2ahUKEwjI34Cw5vn_AhXJGxAIHdLcC-8Q0pQJegQIBxAB&biw=1920&bih=956&dpr=1">Active</a>
  <a class="nav-link" href="https://www.google.ru/search?newwindow=1&sxsrf=AB5stBgLPlh6U4d8uBL1jxrB2WzQ4XpLZw:1688636823193&q=коты&tbm=isch&sa=X&ved=2ahUKEwjI34Cw5vn_AhXJGxAIHdLcC-8Q0pQJegQIBxAB&biw=1920&bih=956&dpr=1">Link</a>
        each $state, $value in $theme-colors {
          $alert-background: shift-color($value, $alert-bg-scale);
          $alert-border: shift-color($value, $alert-border-scale);
          $alert-color: shift-color($value, $alert-color-scale);
          if (contrast-ratio($alert-background, $alert-color) < $min-contrast-ratio) {
            $alert-color: mix($value, color-contrast($alert-background), abs($alert-color-scale));
          }
          .alert-#{$state} {
            include alert-variant($alert-background, $alert-border, $alert-color);
          }
        }
</nav>

