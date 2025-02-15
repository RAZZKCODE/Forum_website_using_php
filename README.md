<h1>E-idea - Forum Web Application</h1>
<h2 id="installation">Overview</h2>
<p>E-idea is a simple and interactive forum-based web application where users can engage in discussions by posting and replying to threads. The platform provides a structured environment for sharing ideas and opinions on various topics.</p>
<h2 id="usage">Features</h2>
<ul>
<li><strong>User Authentication:</strong> Login system with session management.</li>
<li><strong>Thread Management:</strong> Users can create, view, and reply to discussion threads.</li>
<li><strong>Responsive UI:</strong> Built with Bootstrap for mobile-friendly design.</li>
<li><strong>Database Connectivity:</strong> Uses MySQL for storing user details and forum posts.</li>
<li><strong>Image Support:</strong> Supports images within discussions.</li>
</ul>
<h2 id="contributing">Installation</h2>
<h3>Prerequisites</h3>
<ul>
<li>A web server with PHP support (e.g., XAMPP, WAMP, LAMP)</li>
<li>MySQL database</li>
<li>A browser to access the application</li>
</ul>
<h3>Steps</h3>
<ol>
<li><strong>Clone or Download the Repository:</strong>
<pre><div style="display: block; overflow-x: auto; background: rgb(43, 43, 43); color: rgb(248, 248, 242); padding: 0.5em;"><code class="language-text" style="white-space: pre;"><span>git clone https://github.com/your-repo/E-idea.git
</span></code></div></pre>
</li>
<li><strong>Move the Files to Your Web Server Directory:</strong>
<ul>
<li>For XAMPP: Copy the files to <code>htdocs/</code></li>
<li>For WAMP: Copy the files to <code>www/</code></li>
</ul>
</li>
<li><strong>Setup the Database:</strong>
<ul>
<li>Import the provided <code>database.sql</code> file into MySQL.</li>
<li>Update <code>db_connect.php</code> with your database credentials.</li>
</ul>
</li>
<li><strong>Run the Application:</strong>
<ul>
<li>Start your server and navigate to <code>http://localhost/E-idea/</code> in your browser.</li>
</ul>
</li>
</ol>
<h2 id="license">File Structure</h2>
<pre><code>E-idea/
│-- aboutus.php
│-- Index.php
│-- login.php
│-- Threads.php
│-- Threadlist.php
│-- ViewThreads.php
│-- Part/ (contains reusable components like navbar, database connection)
│-- Images/ (contains UI assets)
</code></pre>
<h2>Security Considerations</h2>
<ul>
<li>Use password hashing instead of storing passwords in plain text.</li>
<li>Implement proper input validation to prevent SQL injection.</li>
</ul>
<h2>Future Enhancements</h2>
<ul>
<li>User registration system.</li>
<li>Admin panel for managing users and threads.</li>
<li>Email verification during signup.</li>
</ul>
<h2>Author</h2>
<p>Rajveer</p>
<h2>License</h2>
<p>This project is open-source. Modify and use as needed!</p></div></div>
