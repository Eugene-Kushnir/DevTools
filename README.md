# DevTools

DevTools adblocker is the easiest way to block ads on the website https://sd.ua/.

Implementation idea

After researching https://sd.ua/ it is assumed that advertising
are links to third party resources and are expressed by the IMG.
Therefore, extraneous links with IMG inside the tag were selected
and is hidden.

Optimization

1. I cut url by the name of the site, because not everywhere in https links,
   which led to hiding the necessary links.
2. After hiding the link, there is an empty div left on the page,
   hence the deletion was done on the parent node.
