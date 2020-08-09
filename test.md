<script src='https://meet.jit.si/external_api.js'></script>
# Test.md

I will use this page to try out markdown.

## test of raw HTML
### simple inline HTML

Can I use <i>raw HTML source code</i> in my markdown?

**Result:**  ✔️		

### advanced HTML
Can I use more advanced HTML source code in my markdown?

<iframe src="index.html"></iframe>

**Result:**  ✔️		

### jitsi meet

Can I embed a Jitsi Meet meeting?

<script type="text/javascript">
  console.log( ({
    domain : 'meet.jit.si',
    options : {
      width: 640,
     height: 480
    },
    main : function () {
      return new JitsiMeetExternalAPI(this.domain, this.options);
    }
  }).main() );
</script>
