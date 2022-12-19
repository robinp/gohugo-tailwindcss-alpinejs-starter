This is some MD with HTML:
<html>

<b>Blaa</b>
<div>
{{<ping>}}
<div>
Hello? <i>Yeah</i>
</div>
<span>foo</span>
{{</ping>}}
</div>
<div>
  {{< foo wat="baz" >}}
</div>
<div x-data="{ open: false }">
  <button class="bg-pink-500 btn" @click="open = true">Expand</button>

  <span x-cloak x-show="open" x-transition.duration.500ms>
    Content...
  </span>
</div>

</html>
