<h1>Creating custom taxonomies and post types in WordPress</h1>
<h2>Description</h2>
<p>Custom taxonomies and post types allow to create on WordPress fairly complex projects. On simple example to show their implementation in theme.</p>
<p>Detailed description in <a href="https://webmikorn.ru/articles/sozdanie-taksonomii-i-polzovatelskogo-tipa-zapisi-wordpress/">article</a> (russian language).</p>
<h2>Used files and folders</h2>
<p>template-parts &mdash; folder with content files for pages, posts and taxonomies.</p>
<p>custom-types.php &mdash; file of registration for custom taxonomies and post types. To include in theme that file, need write in file functions.php:</p>
<pre>
// Custom taxonomies and post types:
require get_template_directory() . '/custom-types.php';
</pre>
<p>single-news.php &mdash; file of output single news.</p>
<p>content-news.php &mdash; file with content of single news in folder template-parts. Include in file single-news.php.</p>
<p>taxonomy-taxnews.php &mdash; file of output taxonomy with slug &laquo;taxnews&raquo;.</p>
<p>content-taxnews.php &mdash; file with content of taxonomy in folder template-parts. Include in file taxonomy-taxnews.php.</p>
