<h1>
	<a href="https://github.com/myrrlyn/teslore/blob/master/README.md">
		README on GitHub
	</a>
</h1>
<p>
	This repository holds the project for /r/teslore&#39;s CSS work. It includes scripting support to automatically parse SASS and upload CSS to reddit.
</p>
<h2>
	Getting Started
</h2>
<p>
	Clone this repository and copy <code>config/reddit.yml.example</code> to <code>config/reddit.yml</code>. This file is ignored by Git. Fill in your reddit username and password, and specify the default subreddit, stylesheet, and SASS method &#40;options are provided&#41;. There <strong>must</strong> be a <code>stylesheet.css</code> next to a <code>stylesheet</code> directory in the root of this repository.
</p>
<h2>
	Installing
</h2>
<p>
	This repository requires the <code>gcc</code>, <code>libxml2</code>, <code>libcrypt</code>, <code>libxml2-dev</code>, and <code>Ruby</code> packages on Ubunto or Cygwin. Once these are installed, run <code>gem install bundler</code> and then <code>bundle install</code>. A common point of failure is the <code>Nogokiri</code> package; error reports may be submitted on the <a href="http://github.com/myrrlyn/teslore">GitHub page</a> if support is needed.
</p>
<h2>
	RAKE tasks
</h2>
<p>
	All tasks take the form of <code>bundle exec rake reddit:COMMAND</code>, where COMMAND is one of the following.
</p>
	<ul>
		<li>
			refresh - refresh pulls down the current stylesheet and performs Ruby processing on it, then pushing the modified sheet back to the subreddit. No other code modification takes place. Use this for automation of a calendar display.
		</li>
		<li>
			compile - compile builds a stylesheet off of your local files and stores it in <code>build/STYLESHEET.css</code> where STYLESHEET is the name of your sheet. It does not get pushed to reddit.
		</li>
		<li>
			push - push builds the stylesheet out of local files and then pushes it to the subreddit of your choice.
		</li>
	</ul>
<p>
	You may also use inline instructions to override lines in <code>config/reddit.yml</code> or to bypass it entirely. Add FIELD=VALUE words to the end of your command, such as <code>subreddit=teslore</code>, <code>style=compressed</code>, or <code>stylesheet=almsivi</code>. We have set <code>config/reddit.yml</code> to build to the testing subreddit by default, and require an explicit command to build to /r/teslore proper, in order to keep from accidentally pushing unstable or testing builds to the main subreddit.
</p>
		$('').click
		(
			function()
			{
				$('div#file-info').html
				(
					''
				);
			}
		);
