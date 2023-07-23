---
layout: default
title: ABD’ye açılan kapınız.
featured-img: sleek
---

<script>
  // Get the user's browser language
  const userLanguage = navigator.language || navigator.userLanguage;

  // Check if the user's language is Turkish ("tr")
  if (userLanguage.startsWith("tr")) {
    // Redirect to the Turkish site (https://investilogiusa.com/tr)
    window.location.replace("https://investilogiusa.com/tr");
  } else {
    // Redirect to the English site (https://investilogiusa.com)
    window.location.replace("https://investilogiusa.com");
  }
</script>

#
# You don't need to edit this file, it's empty on purpose.
# Edit sleeks's default layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
#
