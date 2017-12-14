
![](https://avatars2.githubusercontent.com/u/33355442?s=400&v=4)


```python
    %%html
    <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3316.015206499877!2d-84.39725578479195!3d33.78610548067919!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x88f5045f48e36997%3A0x2bcb18d7444a9f39!2s250+14th+St+NW%2C+Atlanta%2C+GA+30318!5e0!3m2!1sen!2sus!4v1513224672287" width="600" height="300" frameborder="0" style="border:0" allowfullscreen></iframe>
```


<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3316.015206499877!2d-84.39725578479195!3d33.78610548067919!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x88f5045f48e36997%3A0x2bcb18d7444a9f39!2s250+14th+St+NW%2C+Atlanta%2C+GA+30318!5e0!3m2!1sen!2sus!4v1513224672287" width="600" height="300" frameborder="0" style="border:0" allowfullscreen></iframe>



```python
    %reload_ext literacy
    from composites import *
    import style
```


<style>
body.rise-hack-active div.reveal .code_cell .input,
body.rise-hack-active div.reveal .output_stderr {
    display: none;
}
button.rise-hack:hover {
    opacity: 0.7;
}
button.rise-hack {
    font-weight: bold;
}
body.rise-hack-active button.rise-hack {
    text-decoration: line-through;
}
body.rise-hack-active .reveal .rendered_html table {
    font-size: 16px;
}
body.rise-hack-active .reveal .prompt {
    display: none;
}
</style>



    <IPython.core.display.Javascript object>



```python
    
    ---
    ref:
        gitter: https://gitter.im/atl-jugheads/Lobby
        coc: 
        cocform: 
        notifications: https://gitter.zendesk.com/hc/en-us/articles/210265505-Notifications
        logo: https://avatars2.githubusercontent.com/u/33355442?s=400&v=4
        moz: https://wiki.mozilla.org/MOSS/Foundational_Technology/Projects_We_Use
        jimmy: https://github.com/jrs2
        np: https://github.com/numpy/numpy/blob/master/doc/neps/dropping-python2.7-proposal.rst
        jonathan: 
            
    coc_local: CODE_OF_CONDUCT.md
    panel:
        - tonyfast
        - slstarnes
```


```javascript
    %%javascript
    Reveal.configure({
        autoSlide: 10000,
        loop: true,
    });
```


    %%javascript
    Reveal.configure({
        autoSlide: 10000,
        loop: true,
    });



    <IPython.core.display.Javascript object>



```python
![]({{ref['logo']}})

# Jupyter User Group Meeting TWO

* Welcome
* Code of Conduct
* Gitter
* News
* Panel
* Talks
* Trapper Keeper

```


![](https://avatars2.githubusercontent.com/u/33355442?s=400&v=4)

# Jupyter User Group Meeting TWO

* Welcome
* Code of Conduct
* Gitter
* News
* Panel
* Talks
* Trapper Keeper



```python
# `C\`ode `o\`f `C\`onduct

    = cache(the.Path(coc_local).Path.read_text()) * the.str.split('## ') / ('## ' + x) * list 
```


# `C\`ode `o\`f `C\`onduct

    = cache(the.Path(coc_local).Path.read_text()) * the.str.split('## ') / ('## ' + x) * list 



```python
{{the[CoC][x[3]]()}}
```


## 3. Expected Behavior

The following behaviors are expected and requested of all community members:

*   Participate in an authentic and active way. In doing so, you contribute to the health and longevity of this community.
*   Exercise consideration and respect in your speech and actions.
*   Attempt collaboration before conflict.
*   Refrain from demeaning, discriminatory, or harassing behavior and speech.
*   Be mindful of your surroundings and of your fellow participants. Alert community leaders if you notice a dangerous situation, someone in distress, or violations of this Code of Conduct, even if they seem inconsequential.
*   Remember that community event venues may be shared with members of the public; please be respectful to all patrons of these locations.





```python
{{the[CoC][x[4]]()}}
```


## 4. Unacceptable Behavior

The following behaviors are considered harassment and are unacceptable within our community:

*   Violence, threats of violence or violent language directed against another person.
*   Sexist, racist, homophobic, transphobic, ableist or otherwise discriminatory jokes and language.
*   Posting or displaying sexually explicit or violent material.
*   Posting or threatening to post other people’s personally identifying information ("doxing").
*   Personal insults, particularly those related to gender, sexual orientation, race, religion, or disability.
*   Inappropriate photography or recording.
*   Inappropriate physical contact. You should have someone’s consent before touching them.
*   Unwelcome sexual attention. This includes, sexualized comments or jokes; inappropriate touching, groping, and unwelcomed sexual advances.
*   Deliberate intimidation, stalking or following (online or in person).
*   Advocating for, or encouraging, any of the above behavior.
*   Sustained disruption of community events, including talks and presentations.




# Talks 

1. Analysis of Cryptocurrency and Traditional Financial Markets
2. Reusability and Reproduciblity
3. Strava Data Analytics


```python
# Analysis of Cryptocurrency and Traditional Financial Markets

[_Jonathan Lamberts_]({{ref['jonathan']}})

I'm currently exploring the relevance of traditional financial indicators when predicting the performance of several cryptocurrencies.  I'm also comparing, in general, the performance of traditional securities with that of crypto.  I'm almost exclusively using Jupyter notebooks for this analysis.  The talk would be more focused on the application of the notebook as an exploratory tool than on specific features of the notebook itself.

```


# Analysis of Cryptocurrency and Traditional Financial Markets

[_Jonathan Lamberts_](None)

I'm currently exploring the relevance of traditional financial indicators when predicting the performance of several cryptocurrencies.  I'm also comparing, in general, the performance of traditional securities with that of crypto.  I'm almost exclusively using Jupyter notebooks for this analysis.  The talk would be more focused on the application of the notebook as an exploratory tool than on specific features of the notebook itself.



```python
# Reusability and Reproduciblity

[_Tony Fast_]({{ref['tony']}})

Get more out of your notebooks by creating _Run All-able_ notebooks and deriving reusable documents with 
__nbconvert__.  This presentation will be a classroom style discussion will explore the various lifecycles of 
a notebook from it's highly interactive initial state to the document at rest years later.
```


# Reusability and Reproduciblity

[_Tony Fast_]()

Get more out of your notebooks by creating _Run All-able_ notebooks and deriving reusable documents with 
__nbconvert__.  This presentation will be a classroom style discussion will explore the various lifecycles of 
a notebook from it's highly interactive initial state to the document at rest years later.



```python
# Strava Data Analytics

[_Jimmy Simmons_]({{ref['jimmy']}})

Training for triathlons requires discipline in three areas. It is a lot like Role Playing Games except the character is you. Sometimes it's hard to know other than "feel" how the character is doing. Strava is a social network for athletes and stores large amounts of user data. If the user trains with a GPS watch and other sensors all that data is cached. This data is explored using the Python API and Jupyter to look for relationships, improvement, and trends within the data. Bokeh, Holoviews, and Geoviews are all used to this end.
```


# Strava Data Analytics

[_Jimmy Simmons_](https://github.com/jrs2)

Training for triathlons requires discipline in three areas. It is a lot like Role Playing Games except the character is you. Sometimes it's hard to know other than "feel" how the character is doing. Strava is a social network for athletes and stores large amounts of user data. If the user trains with a GPS watch and other sensors all that data is cached. This data is explored using the Python API and Jupyter to look for relationships, improvement, and trends within the data. Bokeh, Holoviews, and Geoviews are all used to this end.



```python
# Communicating on [Gitter]({{ref.gitter}})

> Gitter will be used during the event to ask questions and share links.  We will ask the presenters 
to [turn on notifications]({{ref['notifications']}}) during their presentations for interactive feedback.

Gitter will allow us to aggregate our collective discussion into a report.
```


# Communicating on [Gitter](https://gitter.im/atl-jugheads/Lobby)

> Gitter will be used during the event to ask questions and share links.  We will ask the presenters 
to [turn on notifications](https://gitter.zendesk.com/hc/en-us/articles/210265505-Notifications) during their presentations for interactive feedback.

Gitter will allow us to aggregate our collective discussion into a report.



```python
{{ref['gitter']}}
```



        <iframe
            width="600"
            height="400"
            src="https://gitter.im/atl-jugheads/Lobby"
            frameborder="0"
            allowfullscreen
        ></iframe>
        



```python
# Upcoming Events 
### [Propose a talk](https://docs.google.com/forms/d/1NL0DJlfl5fnCMGT_fDnSi25aMF4yAAD77-Xp_2P1x24/edit) for future dates

> ### December 16, 2017 | January 27, 2018  | Something in February | Jupyter day on March 31, 2018
```


# Upcoming Events 
### [Propose a talk](https://docs.google.com/forms/d/1NL0DJlfl5fnCMGT_fDnSi25aMF4yAAD77-Xp_2P1x24/edit) for future dates

> ### December 16, 2017 | January 27, 2018  | Something in February | Jupyter day on March 31, 2018



```python
# News

> Recent news in open source.
```


# News

> Recent news in open source.


<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Binder 2.0, a Tech Guide, from  <a href="https://twitter.com/mybinderteam?ref_src=twsrc%5Etfw">@mybinderteam</a> <a href="https://t.co/b1U8PnREBH">https://t.co/b1U8PnREBH</a></p>&mdash; Project Jupyter (@ProjectJupyter) <a href="https://twitter.com/ProjectJupyter/status/936265849366892545?ref_src=twsrc%5Etfw">November 30, 2017</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>



```python
http://www.i-programmer.info/news/216-python/11362-pypi-granted-170000.html
```



        <iframe
            width="600"
            height="400"
            src="http://www.i-programmer.info/news/216-python/11362-pypi-granted-170000.html"
            frameborder="0"
            allowfullscreen
        ></iframe>
        



```python
# [Foundational Mozilla Technologies.]({{ref.moz}})

    moz = __import__('pandas').read_html(ref['moz'])[0].pipe(
        lambda df: df.rename(columns=dict(enumerate(df.iloc[0]))).iloc[1:].set_index('Project'))
    moz
```


# [Foundational Mozilla Technologies.](https://wiki.mozilla.org/MOSS/Foundational_Technology/Projects_We_Use)

    moz = __import__('pandas').read_html(ref['moz'])[0].pipe(
        lambda df: df.rename(columns=dict(enumerate(df.iloc[0]))).iloc[1:].set_index('Project'))
    moz





<div>
<style>
    .dataframe thead tr:only-child th {
        text-align: right;
    }

    .dataframe thead th {
        text-align: left;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Description and Use</th>
      <th>Contact within Mozilla</th>
    </tr>
    <tr>
      <th>Project</th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>Adjust</th>
      <td>Mobile app analytics; used to track installs o...</td>
      <td>Android &amp; iOS teams</td>
    </tr>
    <tr>
      <th>Airflow</th>
      <td>Airflow is a platform to programmatically auth...</td>
      <td>Roberto Agostino Vitillo</td>
    </tr>
    <tr>
      <th>American Fuzzy Lop</th>
      <td>A security-oriented fuzzer.</td>
      <td>Unknown</td>
    </tr>
    <tr>
      <th>ANGLE</th>
      <td>A conformant OpenGL ES implementation for Wind...</td>
      <td>Platform Graphics Team</td>
    </tr>
    <tr>
      <th>angular.js</th>
      <td>Used by A-Team for web apps (eg Treeherder)</td>
      <td>Member of Jonathan Griffin's team</td>
    </tr>
    <tr>
      <th>Apache Server</th>
      <td>Used by A-Team for web apps</td>
      <td>Member of Jonathan Griffin's team</td>
    </tr>
    <tr>
      <th>Ansible</th>
      <td>Used by IT (netops) and A-Team to manage deplo...</td>
      <td>jbarnell , Webops, GPS?</td>
    </tr>
    <tr>
      <th>AreWeFastYet</th>
      <td>Compare JS performance across JS engines and p...</td>
      <td>Hannes Verschore</td>
    </tr>
    <tr>
      <th>Argon</th>
      <td>Used as the foundation for mobile AR web brows...</td>
      <td>Blair MacIntyre</td>
    </tr>
    <tr>
      <th>Atom</th>
      <td>Used (either vanilla or e.g. as [1] ) by vario...</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>BabelJS</th>
      <td>JavaScript compiler, Used by Gaia, TaskCluster...</td>
      <td>Selena Deckelmann</td>
    </tr>
    <tr>
      <th>BIND</th>
      <td>DNS Server</td>
      <td>Brian Hourigan</td>
    </tr>
    <tr>
      <th>Bleach</th>
      <td>HTML sanitizing library that escapes or strips...</td>
      <td>Will Kahn-Greene</td>
    </tr>
    <tr>
      <th>Blessings</th>
      <td>Terminal formatting lib used by mozilla-centra...</td>
      <td>Erik Rose</td>
    </tr>
    <tr>
      <th>Blink Web Audio</th>
      <td>Web audio implementation from Blink</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>Bootstrap</th>
      <td>HTML/CSS/JS framework, used by many of Mozilla...</td>
      <td>Webdev</td>
    </tr>
    <tr>
      <th>bro</th>
      <td>The Bro Network Security Monitor</td>
      <td>Michal Purzynski</td>
    </tr>
    <tr>
      <th>brotli</th>
      <td>Compression library</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>Browserify</th>
      <td>Build JS dependencies for the browser</td>
      <td>mozilla-services (kinto.js)</td>
    </tr>
    <tr>
      <th>BuildBot</th>
      <td>The base system currently in use for release</td>
      <td>Dustin J. Mitchell</td>
    </tr>
    <tr>
      <th>Bugzilla (upstream)</th>
      <td>The base Bugzilla on that we customize for Moz...</td>
      <td>Mark Côté</td>
    </tr>
    <tr>
      <th>Cairo</th>
      <td>Vector graphics-based, device independent API;...</td>
      <td>Jeff Muizelaar</td>
    </tr>
    <tr>
      <th>ccache</th>
      <td>A compiler cache; used by Servo and Gecko builds</td>
      <td>Ted Mielczarek</td>
    </tr>
    <tr>
      <th>Celery</th>
      <td>Distributed task queue. Used by Treeherder and...</td>
      <td>Member of Jonathan Griffin's team</td>
    </tr>
    <tr>
      <th>certlint</th>
      <td>Certificate checking tool, used by the Root St...</td>
      <td>Kathleen Wilson</td>
    </tr>
    <tr>
      <th>cffi</th>
      <td>C Foreign Function Interface for Python.</td>
      <td>Cloud Services Team</td>
    </tr>
    <tr>
      <th>CKEditor</th>
      <td>WYSIWYG editor on MDN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>CLDR</th>
      <td>Common Locale Data Repository - Unicode data</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>CMake</th>
      <td>cross-platform family of tools designed to bui...</td>
      <td>Mike Trinkala</td>
    </tr>
    <tr>
      <th>Chai</th>
      <td>JavaScript test and assertion library</td>
      <td>Cloud Services, Tarek Ziade's team (kinto.js),...</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>Subversion</th>
      <td>https://svn.mozilla.org (Planning to decommiss...</td>
      <td>Unknown</td>
    </tr>
    <tr>
      <th>suricata</th>
      <td>IDS / IPS / NSM engine</td>
      <td>Michal Purzynski</td>
    </tr>
    <tr>
      <th>TernJS</th>
      <td>Code analysis engine for JS</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>three.js</th>
      <td>3D JS library; used by A-Frame</td>
      <td>Lars Bergstrom</td>
    </tr>
    <tr>
      <th>Tox</th>
      <td>Test automation</td>
      <td>Dave Hunt</td>
    </tr>
    <tr>
      <th>Travis</th>
      <td>Continuous integration system used by several ...</td>
      <td>Jonathan Griffin's team and Lars Bergstrom</td>
    </tr>
    <tr>
      <th>twemoji</th>
      <td>Upstream Emoji artwork used in the Firefox bui...</td>
      <td>Tim Chien (See emojione-colr)</td>
    </tr>
    <tr>
      <th>The Unicode Consortium</th>
      <td>Their work underpins most of what we do</td>
      <td>Richard Soderberg</td>
    </tr>
    <tr>
      <th>UWSGI</th>
      <td>Full hosting stack used in MozDef</td>
      <td>MozDef Team in EIS</td>
    </tr>
    <tr>
      <th>Vagrant</th>
      <td>Build and distribute dev envs, used by Treeher...</td>
      <td>Member of Jonathan Griffin's team</td>
    </tr>
    <tr>
      <th>Valgrind</th>
      <td>Memory error detection and profiling of C and ...</td>
      <td>jseward, njn</td>
    </tr>
    <tr>
      <th>VideoLAN</th>
      <td>Free software for multimedia</td>
      <td>Timothy B. Terriberry</td>
    </tr>
    <tr>
      <th>vscode</th>
      <td>Code editor</td>
      <td>unknown</td>
    </tr>
    <tr>
      <th>vim</th>
      <td>editor used by many developers</td>
      <td>—</td>
    </tr>
    <tr>
      <th>waffle.io</th>
      <td>github project management used by various teams</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>web-platform-tests</th>
      <td>Testcases and tooling for cross-browser testin...</td>
      <td>jgraham</td>
    </tr>
    <tr>
      <th>WebPack</th>
      <td>A bundler for javascript and friends</td>
      <td>Nicolas Perriault</td>
    </tr>
    <tr>
      <th>WebRTC.org</th>
      <td>Components to support real-time communication ...</td>
      <td>Randell Jesup</td>
    </tr>
    <tr>
      <th>woff2</th>
      <td>Reference library for WOFF font format</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>WordPress</th>
      <td>Powers our blogs, blog.mozilla.org</td>
      <td>Craig Cook</td>
    </tr>
    <tr>
      <th>Wt</th>
      <td>C++ library for developing web applications, h...</td>
      <td>Mike Trinkala</td>
    </tr>
    <tr>
      <th>x509lint</th>
      <td>Certificate checking tool, used by the Root St...</td>
      <td>Kathleen Wilson</td>
    </tr>
    <tr>
      <th>Xiph.Org</th>
      <td>Media codecs ship in Firefox, encoding tools; ...</td>
      <td>Ralph Giles</td>
    </tr>
    <tr>
      <th>xxHash</th>
      <td>Extremely fast non-cryptographic hash algorith...</td>
      <td>Mike Trinkala</td>
    </tr>
    <tr>
      <th>XZ Embedded</th>
      <td>Decompressor for the XZ format</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>yasm</th>
      <td>Assembler used by the build system.</td>
      <td>unknown</td>
    </tr>
    <tr>
      <th>YouCompleteMe</th>
      <td>Code completion engine for vim editors</td>
      <td>Ehsan Akhgari</td>
    </tr>
    <tr>
      <th>zlib</th>
      <td>Streaming compression and decompression for HT...</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>Zappa Serverless Framework</th>
      <td>Framework for porting Flask, Djangon, other py...</td>
      <td>Andrew Krug</td>
    </tr>
    <tr>
      <th>ZooKeeper</th>
      <td>Distributed synchronization, use by hg.mozilla...</td>
      <td>gps</td>
    </tr>
  </tbody>
</table>
<p>240 rows × 2 columns</p>
</div>




```python
    %%html
    <blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr"><a href="https://twitter.com/hashtag/Gensim?src=hash&amp;ref_src=twsrc%5Etfw">#Gensim</a> 3.2.0 just released, code name Christmas Come Early! New <a href="https://twitter.com/hashtag/Poincare?src=hash&amp;ref_src=twsrc%5Etfw">#Poincare</a> embeddings, crazy speedup of <a href="https://twitter.com/hashtag/FastText?src=hash&amp;ref_src=twsrc%5Etfw">#FastText</a>, pretrained data/models for download, Linux/Windows/MacOS wheels and other improvements. <a href="https://t.co/mCYvhGIycP">https://t.co/mCYvhGIycP</a> <a href="https://t.co/VR3amLJl80">pic.twitter.com/VR3amLJl80</a></p>&mdash; Gensim (@gensim_py) <a href="https://twitter.com/gensim_py/status/939722396688371713?ref_src=twsrc%5Etfw">December 10, 2017</a></blockquote>
    <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
```


    %%html
    <blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr"><a href="https://twitter.com/hashtag/Gensim?src=hash&amp;ref_src=twsrc%5Etfw">#Gensim</a> 3.2.0 just released, code name Christmas Come Early! New <a href="https://twitter.com/hashtag/Poincare?src=hash&amp;ref_src=twsrc%5Etfw">#Poincare</a> embeddings, crazy speedup of <a href="https://twitter.com/hashtag/FastText?src=hash&amp;ref_src=twsrc%5Etfw">#FastText</a>, pretrained data/models for download, Linux/Windows/MacOS wheels and other improvements. <a href="https://t.co/mCYvhGIycP">https://t.co/mCYvhGIycP</a> <a href="https://t.co/VR3amLJl80">pic.twitter.com/VR3amLJl80</a></p>&mdash; Gensim (@gensim_py) <a href="https://twitter.com/gensim_py/status/939722396688371713?ref_src=twsrc%5Etfw">December 10, 2017</a></blockquote>
    <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>



<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr"><a href="https://twitter.com/hashtag/Gensim?src=hash&amp;ref_src=twsrc%5Etfw">#Gensim</a> 3.2.0 just released, code name Christmas Come Early! New <a href="https://twitter.com/hashtag/Poincare?src=hash&amp;ref_src=twsrc%5Etfw">#Poincare</a> embeddings, crazy speedup of <a href="https://twitter.com/hashtag/FastText?src=hash&amp;ref_src=twsrc%5Etfw">#FastText</a>, pretrained data/models for download, Linux/Windows/MacOS wheels and other improvements. <a href="https://t.co/mCYvhGIycP">https://t.co/mCYvhGIycP</a> <a href="https://t.co/VR3amLJl80">pic.twitter.com/VR3amLJl80</a></p>&mdash; Gensim (@gensim_py) <a href="https://twitter.com/gensim_py/status/939722396688371713?ref_src=twsrc%5Etfw">December 10, 2017</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>



```python
# [`import numpy` Plan for dropping Python 2.7 support]({{ref['np']}})
 
```


# [`import numpy` Plan for dropping Python 2.7 support](https://github.com/numpy/numpy/blob/master/doc/neps/dropping-python2.7-proposal.rst)
 



```python
# Trapper Keeper 

[![](https://user-images.githubusercontent.com/4236275/33974126-b8b16198-e054-11e7-86bd-b333f9cde3ba.png)](https://github.com/atl-jugheads/trapper-keeper)
```


# Trapper Keeper 

[![](https://user-images.githubusercontent.com/4236275/33974126-b8b16198-e054-11e7-86bd-b333f9cde3ba.png)](https://github.com/atl-jugheads/trapper-keeper)



```python
    if __name__ == '__main__':
        !jupyter nbconvert --to markdown readme.ipynb
```


    if __name__ == '__main__':
        !jupyter nbconvert --to markdown readme.ipynb

