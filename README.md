A pacakge of R markdown templates.

Currently, there's one `hrbrmrkdn::default` :-)

When you use RStudio to create a new R Markdown document, select "From Template" and
choose "hrbrmstr's Default Template". 

Alternately, you could just start a blank R markdown document and replace the YAML with:

    ---
    title: "Analysis Title"
    author: "Some Author"
    date: "2016-01-20"
    output: hrbrmrkdn::default
    ---
    
There is currently only the `hrbrmrkdn::default` template that uses [Skeleton](http://getskeleton.com) instead of Bootstrap, auto-places a Rapid7 logo at the top and formats the author & date metdata a bit differently.
