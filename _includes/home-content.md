I am a second-year PhD student in *Computer Science* at the 
[University of Rome Tor Vergata](http://web.uniroma2.it), in Italy.

My research interests span the area of Distributed Systems with emphasis on performance optimization.
I am currently investigating decentralized solutions 
self-adaptive Big Data processing systems in geographically distributed environments.


<a name ="contact"></a>
## Contact information
Dipartimento di Ingegneria Civile e Ingegneria Informatica<br/>
Università di Roma "Tor Vergata"<br/>
Via del Politecnico 1, 00133 Roma, Italy<br/>
![]({{ site.baseurl }}/assets/images/email_addr.png)

## Latest publications
{% for y in site.data.publications limit: 1 %}
  {% for paper in y.papers limit: 3 %}
{{ paper.authors }}<br/>
**{{paper.title}}**&nbsp;{% if paper.link %}\[[{{ paper.link_title }}]({{ paper.link }})\]{% endif %}{% if paper.pdf %}&nbsp;[\[pdf]({{ paper.pdf }})\]{% endif %}<br/>
<span class="publications-info">{{paper.info}}</span>
  {% endfor %}
{% endfor %}

You can find [here]({{ site.baseurl }}/publications.html) a list of all my publications.
{: .notice--info}


