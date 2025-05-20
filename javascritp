 <script>
  
    const links = document.querySelectorAll("a.destacar");
    links.forEach(link => {
      link.addEventListener("click", function () {
        link.classList.add("animado");
        setTimeout(() => {
          link.classList.remove("animado");
        }, 500);
        alert("Você está sendo redirecionado para: " + link.textContent);
      });
    });

    function enviarContato() {
      const nome = document.getElementById("nomeContato").value.trim();
      const telefone = document.getElementById("telefoneContato").value.trim();
      const mensagem = document.getElementById("mensagemConfirmacao");

      if (nome && telefone) {
        mensagem.textContent = "✅ Mensagem enviada! Entrarei em contato com você.";
        mensagem.style.color = "green";

        // limpa os campos
        document.getElementById("nomeContato").value = "";
        document.getElementById("telefoneContato").value = "";
      } else {
        mensagem.textContent = "⚠️ Por favor, preencha todos os campos.";
        mensagem.style.color = "red";
      }
    }
  </script>
