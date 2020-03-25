# test-js
To test reading file content for README.md  
<textarea style="width:500px;height: 400px" id="output"></textarea>
<script>
  var output = document.getElementById("output");
  fetch('file.txt')
  .then(text => output.textContent)
</script>
