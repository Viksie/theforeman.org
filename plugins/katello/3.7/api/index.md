---
layout: plugins/katello/documentation_no_menu
title: Documentation
version: 3.7
---

<div id="wrap">
        <div id="content">
                <iframe src="plugins/katello/{{page.version}}/api/apidoc.html" frameborder="0" width="100%" height="1000px" onload='resizeIframe(this);'></iframe>
        </div>
</div>

<script language="javascript" type="text/javascript">
function resizeIframe(obj) {
  obj.style.height = obj.contentWindow.document.getElementById('container').scrollHeight + 150 + 'px';
}
</script>
