<p id="typing-text"></p>

<script>
  const text = "Hi, my name is Aarón";
  let index = 0;
  
  function typeWriter() {
    if (index < text.length) {
      document.getElementById("typing-text").innerHTML += text.charAt(index);
      index++;
      setTimeout(typeWriter, 100);
    }
  }
  
  typeWriter();
</script>

