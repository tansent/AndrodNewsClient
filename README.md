# AndrodNewsClient


One of the most noteworthy point is that the news client has 3-layer ViewPagers stacked together. Yet they can all slide smoothly and 
correctly according to logics.

Left sliding bar is used based on "SlidingMenu"; Sharing app is based on "ShareSDK".

Three-level-cache(network,local,ram) is used for content and map. For content, Map<url,Json> is the idea to cache the content. 
