---
layout: post
title: Linux Command Part 1
date: 2017-03-15  01-45-39
tags:
  - linux
  - what is linux
  - linux command
  - important linux command
category: Linux
published: true
---

<img src="{{ site.url }}/assets/img/linux-terminal/linux_terminal_tw.png" alt="">

## چگونه terminal را باز کنیم 

### کلید های میانبر

{% highlight javascript %}

	Ctrl + Alt + t

{% endhighlight %}

<center>
		<b></b>
		<br>
		<div class="video">
			<div id="14920177592009820"><script type="text/JavaScript" src="https://www.aparat.com/embed/p2XTf?data[rnddiv]=14920177592009820&data[responsive]=yes"></script></div>
		</div>
		<br><br>

</center>

## مدیریت فایل ها و فولدر ها

<center>
		<b></b>
		<br>
		<div class="video">
			<div id="14920175432778242"><script type="text/JavaScript" src="https://www.aparat.com/embed/XpeDg?data[rnddiv]=14920175432778242&data[responsive]=yes"></script></div>
		</div>
		<br><br>
</center>



## اطلاعات سیستم

<p>
 <strong>date</strong><br>
 <strong>cal</strong><br>
 <strong>uptime</strong><br>
 <strong>w</strong> <br>
 <strong>whoami</strong><br>
 <strong>finger <em>user</em></strong><em><strong></strong></em><br>
 <strong>uname -a</strong><br>
 <strong>cat /proc/cpuinfo</strong><br>
 <strong>cat /proc/meminfo</strong><br>
 <strong>df</strong> <strong>-h</strong><br>
 <strong>du</strong><br>
 <strong>free</strong>e</p>

<center>
		<b></b>
		<br>
		<video onclick="this.paused ? this.play() : this.pause();" controls width="50%" poster="../assets/img/static/videoposter.jpg" height="50%" src="../assets/img/linux-terminal/How-to-check-Linux-System-Info-43.mp4">
			Video Tag Not Support
		</video>

</center>

## کلید های ترکیبی

<p>
 <strong>Enter</strong> → Run the command<br>
 <strong>Up Arrow</strong> → Show the previous command<br>
 <strong>Ctrl + R</strong> → Allows you to type a part of the command you're looking for and finds it</p>


## دستورات راهنما

<p>
 <strong>apropos</strong><em><strong> subject</strong></em><strong><em></em></strong><br>
 <strong>man -k <em>keyword</em></strong><em><strong></strong></em><br>
 <strong>man <em>command</em></strong><strong><em></em></strong><br>
 <strong>man -t <em>man</em> | ps2pdf - &gt; <em>man.pdf</em></strong>&nbsp;<br>
 <strong>which </strong><em><strong>command</strong></em><strong><em></em></strong><br>
 <strong>time <em>command</em></strong><strong><em></em></strong></p>

 <p>
 <strong>whereis <em>app</em></strong><em><strong></strong></em><br>
 <strong>which <em>app</em></strong><em><strong></strong></em></p>

## جست و جو

<p>
 <strong>grep <em>pattern</em> <em>files</em></strong><em><strong></strong></em><em><strong></strong></em><br>
 <strong>grep -r <em>pattern</em> <em>dir</em></strong><strong><em></em></strong><em><strong></strong></em><br>
 <em><strong>command | </strong></em><strong>grep</strong><em><strong> pattern</strong></em><em><strong></strong></em> <em><strong></strong></em><br>
 <strong>locate <em>file</em></strong> <em><strong></strong></em><br>
 <strong>find / -name <em>filename</em></strong><em><strong></strong></em><br>
 <strong>find / -name ”*<em>filename</em>*”</strong> <em><strong></strong></em><br>
 <strong>locate <em>filename</em></strong><em><strong></strong></em><br>
 <strong>updatedb</strong><br>
 <strong>which <em>filename</em></strong></strong></em><br>
 <strong>grep <em>TextStringToFind</em> /<em>dir</em></strong><em><strong></strong></em><em><strong></strong></em></p>

<center>
		<b></b>
		<br>
		<div class="video">
			<div id="14920178899577480"><script type="text/JavaScript" src="https://www.aparat.com/embed/rx2bk?data[rnddiv]=14920178899577480&data[responsive]=yes"></script></div>
		</div>
		<br><br>

</center>


## مجوز های فایل

<p>
 <strong>chmod <em>octal</em> <em>file</em></strong><em><strong></strong></em> <em><strong></strong></em>, 4 → read (r), 2 → write (w), 1 → execute (x)<br>
 <br>
 <strong>chmod 777</strong> → read, write, execute for all<br>
 <strong>chmod 755</strong> → rwx for owner, rx for group and world<br>
 برای اطلاعات بیشتر <strong>man chmod</strong>.</p>

<center>
		<b></b>
		<br>
		<div class="video">
			<div id="1492017983546790"><script type="text/JavaScript" src="https://www.aparat.com/embed/E9cLS?data[rnddiv]=1492017983546790&data[responsive]=yes"></script></div>
		</div>
		<br><br>

</center>


## فشرده سازی

<p>
 <strong>tar cf <em>file.tar files</em></strong><em> </em><em><strong>file.tar</strong></em><em><strong></strong></em><br>
 <em><strong>tar xf file.tar</strong></em><em><strong></strong></em></p>
<br>	
 <p>
  <strong>tar czf <em>file.tar.gz files</em></strong><br>
 <strong>tar xzf <em>file.tar.gz</em> </strong></p>
<br>
<p>
 <em><strong>tar cjf file.tar.bz2</strong></em><br>
 <strong>tar xjf <em>file.tar.bz2</em></strong></p>
 <br>
 <p>
 <strong>gzip <em>file</em></strong><strong><em></em></strong><strong><em></em></strong><br>
 <strong>gzip -d <em>file.gz</em></strong><strong><em></em></strong><strong><em></em></strong></p>

<center>
		<b></b>
		<br>
		<video onclick="this.paused ? this.play() : this.pause();" controls width="50%" poster="../assets/img/static/videoposter.jpg" height="50%" src="../assets/img/linux-terminal/Linux-Commands-6-File-CompressionDecom-pression-zip-unzip-tar-43.mp4">
			Video Tag Not Support
		</video>

</center>



## نمایش 

<p>
 <strong>/etc/rc.d/init.d/lpd start</strong><br>
 <strong>/etc/rc.d/init.d/lpd stop</strong><br>
 <strong>/etc/rc.d/init.d/lpd status</strong><br>
 <strong>lpq</strong><br>
 <strong>lprm</strong><br>
 <strong>lpr</strong><br>
 <strong>lpc</strong><br>
 <strong>man <em>subject</em> | lpr</strong><strong><em></em></strong><br>
 <strong>man -t <em>subject</em> | lpr</strong><strong><em></em></strong><br>
 <strong>printtool</strong></p>

<center>
		<b></b>
		<br>
		<div class="video">
			<div id="14920141622173599"><script type="text/JavaScript" src="https://www.aparat.com/embed/vAGDH?data[rnddiv]=14920141622173599&data[responsive]=yes"></script></div>
		</div>
		<br><br>
</center>



## شبکه

<p>
 <strong>ifconfig</strong><br>
 <strong>iwconfig</strong><br>
 <strong>iwlist</strong><strong>iwconfig</strong><br>
 <strong>ping</strong><em><strong> host</strong></em><strong><em>host</em></strong><br>
 <strong>whois <em>domain</em></strong><em><strong></strong></em><br>
 <strong>dig <em>domain</em></strong><em><strong></strong></em><br>
 <strong>dig -x</strong><em><strong> host</strong></em><em><strong></strong></em><br>
 <strong>wget <em>file</em></strong><em><strong></strong></em><br>
 <strong>wget -c</strong><em><strong> file</strong></em></p>

<center>
		<b></b>
		<br>
		<div class="video">
			<div id="14920177136846397"><script type="text/JavaScript" src="https://www.aparat.com/embed/F2PIh?data[rnddiv]=14920177136846397&data[responsive]=yes"></script></div>
		</div>
		<br><br>
</center>


## SSH

<p class="">
 <strong>ssh <em>user</em>@<em>host</em></strong><strong><em></em></strong><em><strong></strong></em><br>
 <strong>ssh -p <em>port user</em>@<em>host</em></strong><em><strong></strong></em><em><strong>port</strong></em> as <em><strong>user</strong></em><br>
 <strong>ssh-copy-id <em>user</em>@<em>host</em></strong><em><strong></strong></em><em><strong></strong></em></p>


<center>
		<b></b>
		<br>
		<div class="video">
			<div id="14920179289918513"><script type="text/JavaScript" src="https://www.aparat.com/embed/mGSxL?data[rnddiv]=14920179289918513&data[responsive]=yes"></script></div>
		</div>
		<br><br>

</center>


## مدیریت کاربران


<p>
 <strong>adduser </strong><em><strong>accountname</strong></em><em><strong></strong></em><br>
 <strong>passwd <em>accountname</em></strong><em><strong></strong></em><br>
 <strong>su</strong><br>
 <strong>exit</strong></p>

<center>
		<b></b>
		<br>
		<div class="video">
			<div id="14920545979830099"><script type="text/JavaScript" src="https://www.aparat.com/embed/uWlMz?data[rnddiv]=14920545979830099&data[responsive]=yes"></script></div>
		</div>
		<br><br>

</center>


## مدیریت فرآیند ها


<p>
 <strong>ps</strong><br>
 <strong>top</strong><br>
 <strong>kill <em>pid</em></strong><em><strong></strong></em><br>
 <strong>killall <em>proc</em></strong><em><strong></strong></em><br>
 <strong>bg</strong><br>
 <strong>fg</strong><br>
 <strong>fg</strong><em><strong> n</strong></em><em><strong></strong></em></p>

<center>
		<b></b>
		<br>
		<div class="video">
			<div id="14920183169022237"><script type="text/JavaScript" src="https://www.aparat.com/embed/jrHWR?data[rnddiv]=14920183169022237&data[responsive]=yes"></script></div>
		</div>
		<br><br>

</center>


## نصب نرم افزار:


### 1:

<p>
 <strong>sudo apt-get update</strong>&nbsp;&nbsp;&nbsp; (to get the latest version)</p>
<p>
 <strong>sudo apt-get install software-package-name</strong></p>

### 2:

<p>
 <strong>sudo add-apt-repository ppa:.....whatever_it_is</strong></p>
<p>
 3. then run this command (must)</p>
<p>
 <strong>sudo apt-get update</strong></p>


## 3:

<p>
 <strong>./configure</strong><br>
 <strong>make</strong><br>
 <strong>make install</strong><br></p>
<p>
 <strong>chmod +x configure</strong></p>
<p>
 <strong>dpkg -i</strong><em><strong> pkg.deb</strong></em><br>
 <strong>rpm -Uvh <em>pkg.rpm</em></strong></p>


### 4:

 <strong>chmod +x filename.sh&nbsp; </strong></p>
<p>
 <strong>./filename.sh </strong>or<strong> <strong>sudo ./filename.sh</strong> </strong></p>



### 5:

 <strong>chmod +x filename.run</strong></p>
<p>
 <strong>./filename.run </strong>or<strong> <strong>sudo ./filename.run</strong> </strong></p>


<center>
		<b></b>
		<br>
		<div class="video">
			<div id="1492018029143582"><script type="text/JavaScript" src="https://www.aparat.com/embed/BvIpg?data[rnddiv]=1492018029143582&data[responsive]=yes"></script></div>
		</div>
		<br><br>

</center>


## خاموش و روشن

<p>
 <strong>shutdown -h now</strong><br>
 <strong>halt</strong><br>
 <strong>shutdown -r 5</strong><br>
 <strong>shutdown -r now</strong><br>
 <strong>reboot</strong><br>
 <strong>startx</strong></p><br>

<center>
		<b></b>
		<br>
		<video onclick="this.paused ? this.play() : this.pause();" controls width="50%" poster="../assets/img/static/videoposter.jpg" height="50%" src="../assets/img/linux-terminal/Commands-to-shutdown-restart-in-linux-18.mp4">
			Video Tag Not Support
		</video>

</center>



<h3> پیشنهاد هایی برای مطالعه</h3>

<br>❝<a target="_blank" href="https://en.wikipedia.org/wiki/Cheat_sheet
">Cheat sheet</a> is very fast way learning❞

<b><p>Cvak iranian linux was from isfehan and lpic1 cheatsheet<a href="/assets/img/linux-commands/c_lpic1.zip">&nbsp;sample</a></p></b><br>

<p>
<a target="_blank" href="http://www.cheat-sheets.org/#Linux">Cheat-Sheets.org</a> → All cheat sheets, round-ups, quick reference cards, quick reference guides and quick reference sheets in one page. The only one you need. <br>

<a target="_blank" href="http://www.linuxtutorialblog.com/post/tutorial-the-best-tips-tricks-for-bash">Tutorial: The best tips & tricks for bash, explained</a> → Linux Tutorial Blog / Quality Linux tutorials without clutter <br>

<a target="_blank" href="http://linuxcommand.org/">LinuxCommand.org</a> → Learning the shell, Writing shell scripts, Script library, SuperMan pages, Who, What, Where, Why <br>

<a target="_blank" href="http://linuxmanpages.com/">LinuxManPages.com</a> → General commands, System calls, Subroutines, Special files, File formats, Games, Macros and conventions, Maintenence commands, Most Popular Man Pages <br>

<a target="_blank" href="http://linux.die.net/man/">Linux Man Pages from die.net</a> → Man pages are grouped into sections, to see the full list of Linux man pages for a section, pick one. Or you can browse Linux man pages by name; choose the first letter of the name of the Linux command, function, or file you are interested in. <br>

<a target="_blank" href="http://www.unixguide.net/linux/linuxshortcuts.shtml">Linux Newbie Guide: Shorcuts and Commands</a> → Linux essential shortcuts and sanity commands; Common Linux commands - system info; Basic operations, network apps, file (de)compression; Process control; Basic administration commands, accessing drives/partitions; Network administration tools, music-related commands, graphics-related commands. <br>

<a target="_blank" href="http://www.gratisoft.us/sudo/man.html">Sudo Manual Pages</a> → Sudo (su "do") allows a system administrator to delegate authority to give certain users (or groups of users) the ability to run some (or all) commands as root or another user while providing an audit trail of the commands and their arguments. For more information, see the introduction to Sudo. Sudo is free software, distributed under an ISC-style license. <br>

<a target="_blank" href="http://linoxide.com/linux-command/linux-commands-cheat-sheet/">LinOxide.com</a> → Linux Commands Cheat Sheet in Black & White <br>




{% include content_option.html %}

<center>♥♥♥♥♥♥♥♥♥♥
<br><b>Please Gaming and give point for end of document your uderstand top linux command</b><br>
</center>
<hr>
<span>Draw back an arrow and launch it(center give point till 3 success launche)!</span>

<!---
{% highlight javascript %}
use admin
db.createUser{
	user: "bonitao",
	pwd: "2016bonitao",
	roles: [{role: "userAdminAnyDatabase", db: "admin"}]
}
{% endhighlight %}
-->

{% include game_include.html %}
