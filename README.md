<div align="center"><img src="image/logo.png" width=100px height=100px></div>
<h1 align="center">gale for Firefox</h1>
<p align="center">My CSS files to use with Firefox and Sidebery</p>

<hr>

My goal with these settings was to create a minimalistic yet functional setup
with Sidebery tuned to match Firefox Default Dark Theme and optimise the
workspace. If you find any odd behaviour feel free to send a pull request.

<hr>

<div align="center"><img src="image/thumbnail.png"></div>

<hr>

I took a break from Firefox and was experimenting with MS Edge. It was lovely
while I was on Windows, but since I decided to move to Linux full-time now (best
decision of my life, by the way), Edge is just not a great choice anymore. I
don't personally care too much about privacy on my browser, and that's not the
reason why I'm back to Firefox but I won't lie to you: it feels great to have
high levels of control over it. Edge feels "artificial" on Linux, it has
different issues depending on the distro and Firefox is just a huge linux
champion in my opinion. So that's it, my affair with Edge is over and I'm back
to maintaining this theme actively.

<hr>

### How to install?

<ol>
<li> In Firefox, go to <code>about:config</code> and set <code>toolkit.legacyUserProfileCustomizations.stylesheets</code> to <code>True</code></li>
<li> Make sure you have the <a href="https://www.userchrome.org/how-create-userchrome-css.html">chrome folder</a> within your firefox profile</li>
<li> Get <a href="https://github.com/mbnuqw/sidebery/">Sidebery</a> if you don't have it already installed</li>
<li> Copy <code>userChrome.css</code>, <code>darkTheme.css</code> and <code>privTheme.css</code> to the chrome folder</li>
<li> Go to Sidebery settings and paste the content of my <code>sidebery.css</code> file into <i>Styles editor > Sidebar</i> </li>
<li> Enjoy your new setup!</li>
</ol>
<hr>

### Known bugs

<ul>
<li>In Sidebery beta, autoshrink triggers when you're moving a tab even though the mouse is still hovering the panel. I decided to disable that characteristic until I find a workaround.</li>
<li><span style="text-decoration: line-through;">When moving a tab, the tab position indicator doesn't follow the <code>margin-top</code> CSS rule for tabs; if it bothers you a lot, identify <code>.Tab {margin-top: 5px;</code> and remove it.</span><b><i>&nbsp;&nbsp;Fixed!</i></b></li>
</ul>
<hr>

### Credits

<ul>
<li>to <a href="https://github.com/MrOtherGuy">@MrOtherGuy</a> for his <a href="https://github.com/MrOtherGuy/firefox-csshacks">Firefox CSS Hacks</a></li>
<li>to <a href="https://www.reddit.com/user/captainkaba/">u/captainkaba</a> for his <a href="https://www.reddit.com/r/FirefoxCSS/comments/rqo5z6/some_people_asked_for_the_css_so_here_is_my_setup/">Denkfabrik</a> theme (which I used as a base for legacy)</li>
<li>to Reddit user <a href="https://www.reddit.com/user/It_Was_The_Other_Guy/">u/It_Was_The_Other_Guy</a> for his <a href="https://www.reddit.com/r/FirefoxCSS/comments/vzcqzn/comment/ig8a8ba/">tip</a> which was very useful in legacy</li>
<li>to Reddit user <a href="https://www.reddit.com/user/GainghisKhan/">u/GainghisKhan</a> for <a href="https://www.reddit.com/r/FirefoxCSS/comments/wcc9fc/comment/j2aoa8r/">finding a bug and providing a solution idea for it</a> in legacy</li>
</ul>
