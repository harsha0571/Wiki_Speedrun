# Wiki Speedrun

A fun side project to see if I can automate the popular wiki speedrun game where you use links on a wiki page to reach an target wiki page. 

Inspired by [Green Code](https://www.youtube.com/@Green-Code) from his video : https://www.youtube.com/watch?v=JvoUHe1OR68

This is simple version which leverages the GloVe embeddings to find out the most promising link from the list of links on the current page and navigates till it reaches the target page.

Current version is not very optimal , need to filter the list of links on the page to only check from viable links.
