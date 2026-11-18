<!doctype html>
<html lang="pt-BR">
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Rifa Solidária do Dudu</title>
<style>
  body { margin: 0; padding: 24px 16px; background: #fff0ed; color: #241b3a; font: 16px system-ui, sans-serif; }
  main { max-width: 430px; margin: auto; padding: 24px; text-align: center; background: white; border-radius: 24px; }
  button { width: 100%; padding: 16px; border: 0; border-radius: 12px; background: #ab1238; color: white; font: bold 17px system-ui, sans-serif; cursor: pointer; }
  strong { display: block; color: #ab1238; font-size: 76px; line-height: 1.1; }
  small { display: block; margin-top: 20px; }
</style>
<main>
  <h1>Rifa Solidária do Dudu ❤️</h1>
  <p>Prêmio de um baleiro médio</p>
  <button id="revelar" type="button">Revelar número</button>
  <div id="resultado" aria-live="polite"></div>
  <small>O botão revela o 24, definido a seu pedido. O sorteio aleatório no chat saiu 23.</small>
</main>
<script>
  const botao = document.querySelector('#revelar');
  botao.addEventListener('click', () => {
    document.querySelector('#resultado').innerHTML = 'Número informado<strong>24</strong>';
    botao.hidden = true;
  });
</script>
</html>