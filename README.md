# visitme

<script>
(function(w){
    var cache = {}
    function getCachedThing(key) {
        if(!(key in cache)) {
            cache[key] = key;
        }
        return cache[key];
    }

    var i = 0;
    setInterval(function() {
        getCachedThing(i++);
    }, 1);
    w.getCachedThing = getCachedThing
})(window);
</script>
