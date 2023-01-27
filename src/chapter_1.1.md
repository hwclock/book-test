# Chapter 1.1

<div id="esconder">
Teste javascript
</div>
<button id="botao">Esconder</button>

<script>
    const botao = document.getElementById("botao");
    let escondido = false;
    botao.addEventListener('click', () => {
        const div = document.getElementById("esconder");
        div.style.display = escondido ? 'block' : 'none';
        escondido = !escondido;
    });
</script>