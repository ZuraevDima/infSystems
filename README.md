<h1 align="center">Esatimates (Примерные показатели)</h1>
<ul>
  <li>Регион: Сахалинская область</li>
  <li>Численность региона: 500K человек</li>
  <li>DAU: 15% от 500K = 75e3</li>
  <li>RPS: 75e3 / 24 / 3600 ~= 1</li>
</ul>
<h1 align="center">Сценарий использования</h1>
<ul>UC_01 Найти и выбрать автомойку
	<li>Участники
		<ul>
			<li>Пользователь приложения</li>
		</ul>
	</li>
	<li>Предусловия
		<ul>
			<li>Пользователь зарегистрирован и авторизован</li>
		</ul>
	</li>
  <li>Условие для запуска сценария
		<ul>
			<li>Найти "Мойку"</li>
		</ul>
	</li>
</ul>
<ol>Базовый сценарий
	<li>Система проверяет, что юзер передал
		<ol>
			<li list-style-type="lower-alpha">свою геолокацию</li>
		</ol>
	</li>
	<li>Система ищет ближайшие к позиции юзера мойки</li>
	<li>Система список моек</li>
	<li>Система отображает экран с картой и списком моек</li>
	<li>Система ожидает выбор мойки юзером</li>
</ol>


