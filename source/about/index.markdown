---
layout: page
title: "about me"
comments: false 
sharing: true
footer: true
---
{% codeblock biography.scala lang:scala %}
  def bio(what: String): String = what match {
    case "Name" => "Fabrice CROISEAUX"
    case "Employer" => "InTech S.A. Luxembourg"
    case "email" => "fcroiseaux@gmail.com"
  }
{% endcodeblock %}
