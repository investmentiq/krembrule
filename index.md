---
layout: default
title: ABD’ye açılan kapınız.
featured-img: sleek
---

<!-- Language switcher links -->
<p>Choose your language:</p>
<ul id="language-switcher">
  <li><a href="https://investilogiusa.com" hreflang="tr" onclick="hideLinks(event)">Türkçe</a></li>
  <li><a href="https://en.investilogiusa.com" hreflang="en" onclick="hideLinks(event)">English</a></li>
</ul>

<!-- JavaScript to hide links when Turkish is selected -->
<script>
  function hideLinks(event) {
    event.preventDefault(); // Prevent the link from navigating to the href URL
    var languageSwitcher = document.getElementById("language-switcher");
    languageSwitcher.style.display = "none";
  }
</script>
