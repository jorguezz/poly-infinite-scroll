# \<poly-infinite-scroll\>


[Try a demo](http://jorguezz.github.io/poly-infinite-scroll/)

**Usage:** 

````
<poly-infinite-scroll id="infinite"
	endpoint="http://localhost:3000/posts"
	response-prop="articles"
	params="{{params}}"
	upper-limit="300"
	lower-limit="300"
	page-size="12"
	element="my-item"
	element-class="customelem">
</poly-infinite-scroll>
```