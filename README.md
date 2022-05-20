# Miscellaneous
Miscellaneous

https://stackoverflow.com/questions/37103607/convert-any-file-into-a-binary-file-and-vice-versa

https://www.jango.com/

https://www.howtohaven.com/system/view-binary-file-on-windows.shtml

/////////////////////////w3schools//////////////////////////////
<!DOCTYPE html>
<html>
<body>

<h1>The iframe element</h1>

<iframe id="iframeid" src="https://pst.klgrth.io/paste/mxu9w" title="W3Schools Free Online Web Tutorials">
</iframe>

<script>

setInterval(function() 
{
	document.getElementById('iframeid').src = document.getElementById('iframeid').src;
}, 10000);

</script>

</body>
</html>
//////////////////////////////////////////////////////

////////////////////////pst.klgrth.io console verbose/////////////////////////////
document.body.style.visibility = "hidden";
document.body.style.setProperty("background-color", "#292a2d");
document.title = "index";

var frm = $('#pasteForm');
frm.submit(function (ev) {
    $.ajax({
        type: frm.attr('method'),
        url: frm.attr('action'),
        data: frm.serialize(),
        success: function (data) {}
    });

    ev.preventDefault();
});

function ins(m) {
  document.querySelector("#code-editor").innerHTML += '\n' + m;
  document.querySelector(".btn.btn-primary").click();
}

function del() {
  document.querySelector("#code-editor").innerHTML = '';
  document.querySelector(".btn.btn-primary").click();
}

function show() {
  console.log(document.querySelector("#code-editor").innerHTML);
}
/////////////////////////////////////////////////////////////////

////////////////////////////////pst.klgrth.io console mini////////////////////////////////
document.body.style.visibility="hidden",document.body.style.setProperty("background-color","#292a2d"),document.title="DevTools - index.html";var frm=$("#pasteForm");function ins(e){document.querySelector("#code-editor").innerHTML+=e+"\n",document.querySelector(".btn.btn-primary").click()}function del(){document.querySelector("#code-editor").innerHTML="Hey.\n",document.querySelector(".btn.btn-primary").click()}function show(){console.log(document.querySelector("#code-editor").innerHTML)}frm.submit(function(e){$.ajax({type:frm.attr("method"),url:frm.attr("action"),data:frm.serialize(),success:function(e){}}),e.preventDefault()});
