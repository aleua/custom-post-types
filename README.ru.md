<h1>Создание пользовательских таксономий и типов записей в WordPress</h1>
<h2>Описание</h2>
<p>Пользовательские таксономии и типы записи позволяют создавать на WordPress достаточно сложные проекты. На простом примере показана их реализация в своей теме.</p>
<p>Подробное описание в <a href="https://webmikorn.ru/articles/sozdanie-taksonomii-i-polzovatelskogo-tipa-zapisi-wordpress/">статье</a>.</p>
<h2>Используемые файлы и папки</h2>
<p>template-parts &mdash; папка, содержащая файлы с контентной частью для страниц, постов и таксономий.</p>
<p>custom-types.php &mdash; файл регистрации таксономии и пользовательского типа записей. Для включения в тему необходимо добавить в файл functions.php активной темы:</p>
<pre>
// Custom taxonomies and post types:
require get_template_directory() . '/custom-types.php';
</pre>
<p>single-news.php &mdash; файл вывода одной новости.</p>
<p>content-news.php &mdash; файл контентной части новости в папке template-parts. Подгружается в файл single-news.php.</p>
<p>taxonomy-taxnews.php &mdash; файл вывода таксономии с ярлыком taxnews.</p>
<p>content-taxnews.php &mdash; файл контентной части таксономии в папке template-parts. Подгружается в файл taxonomy-taxnews.php.</p>
