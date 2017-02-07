<h1>Создание таксономии и пользовательского типа записи WordPress</h1>
<h2>Используемые файлы и папки</h2>
<p>template-parts - папка с контентной частью для страниц, постов и таксономий.</p>
<p>custom-types.php - файл регистрации таксономии и пользовательского типа записей. Для включения в тему необходимо добавить в файл functions.php активной темы:</p>
<pre>
// Taxonomies and custom post types:
require get_template_directory() . '/custom-types.php';
</pre>
<p>single-news.php - файл вывода одной новости.</p>
<p>content-news.php - файл контентной части новости в папке template-parts. Подгружается в файл single-news.php.</p>
<p>taxonomy-taxnews.php - файл вывода таксономии с ярлыком taxnews.</p>
<p>content-taxnews.php - файл контентной части таксономии в папке template-parts. Подгружается в файл taxonomy-taxnews.php.</p>
<h2>Описание</h2>
<p>Подробное описание в <a href="https://webmikorn.ru/articles/sozdanie-taksonomii-i-polzovatelskogo-tipa-zapisi-wordpress/">статье</a></p>