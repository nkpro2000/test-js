# test-js
To test reading file content for README.md  

<script>
function httpGet(theUrl)
{
    var xmlHttp = new XMLHttpRequest();
    xmlHttp.open( "GET", theUrl, false ); // false for synchronous request
    xmlHttp.send( null );
    return xmlHttp.responseText;
}
var content = httpGet("https://raw.githubusercontent.com/nkpro2000/test-js/master/multipy");
document.write(content.replace(/\n/g,"<br>"));
</script>

End
