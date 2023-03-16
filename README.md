[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/milliechapman/dlab-blog/HEAD)

# A brief introduction to cloud native approaches for big data analysis

Monitoring technologies - from satellites to smart phones - are creating vast amounts of data about our planet every day. These data hold promise to provide global insights on everything from biodiversity patterns to vegetation change at increasingly fine spatial and temporal resolution. But leveraging this information often requires us to work with data that is too big to fit in our computer's "working memory" (RAM) or even to download to our computer's hard drive. Some data - like high resolution remote sensing imagery - might be too large to download even when we have access to big  compute infrastructure. 

In this post, I will walk through some tools, terms, and examples to get started with cloud native workflows. These workflows allow us to remotely access and query large data from online resources or web services, all while skipping the download step. We'll touch on a couple common data storage and cataloging structures (Parquet files, S3) and tools to query these online data (Apache Arrow and Vsicurl). I'll focus on a tabular data example but touch on spatial data - sharing resources along the way for deeper dives on each of the topics and tools. 

Example code is provided in R and case studies focused on environmental data, but these concepts are not specific to a programming language or research domain. I hope that this post provides a starting point for anyone interested in working with big data using cloud native approaches!

[Read more!](https://github.com/milliechapman/dlab-blog/blob/main/blog-post.md)
