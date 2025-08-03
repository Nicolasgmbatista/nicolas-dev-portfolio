<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Transformação Fitness</title>
  <link rel="stylesheet" href="style.css" />
  <meta name="description" content="Descubra o método simples para perder gordura sem academia cara. Guia grátis + oferta exclusiva." />
</head>
<body>
  <header class="hero">
    <div class="container">
      <h1>Perder Gordura Sem Complicação</h1>
      <p class="sub">Transforme seu corpo em 30 dias com o método que funciona mesmo sem academia. Sem enrolação, sem aparecer.</p>
      <a href="tripwire.html" class="btn-primary">Comece por R$27</a>
      <p class="small">+ Receba o mini-guia grátis: “3 erros que travam seu emagrecimento”</p>
    </div>
  </header>

  <section class="features">
    <div class="container">
      <h2>O que você vai conseguir</h2>
      <div class="cards">
        <div class="card">
          <h3>Sem academia</h3>
          <p>Rotinas simples que você faz em casa. Nenhum equipamento caro necessário.</p>
        </div>
        <div class="card">
          <h3>Resultados rápidos</h3>
          <p>Foco em hábitos que entregam progresso visível em semanas, não em meses.</p>
        </div>
        <div class="card">
          <h3>Passo a passo</h3>
          <p>Você recebe um plano claro, sem enrolação, seguido por quem já obteve resultado.</p>
        </div>
      </div>
    </div>
  </section>

  <section class="testimonials">
    <div class="container">
      <h2>O que outras pessoas dizem</h2>
      <div class="test-grid">
        <div class="test-card">
          <p class="quote">"Perdi 5kg em 3 semanas sem sair de casa. Simples e direto."</p>
          <p class="author">— João, 27 anos</p>
        </div>
        <div class="test-card">
          <p class="quote">"O checklist mudou minha rotina. Tô mais confiante e mais magro."</p>
          <p class="author">— Maria, 33 anos</p>
        </div>
        <div class="test-card">
          <p class="quote">"Achei que era impossível sem academia. Me enganei — valeu cada segundo."</p>
          <p class="author">— Lucas, 21 anos</p>
        </div>
      </div>
    </div>
  </section>

  <section id="oferta" class="offer">
    <div class="container">
      <div class="offer-box">
        <div class="badge">Oferta Limitada</div>
        <h2>Plano Completo de Transformação</h2>
        <p class="lead">Acesso ao método testado + bônus exclusivo. Comece hoje com o guia e ganhe um plano rápido de 30 dias.</p>
        <ul>
          <li>Checklist de erros que sabotam emagrecimento</li>
          <li>Rotinas fáceis de fazer em casa</li>
          <li>Mini-plano alimentar sem dietas malucas</li>
          <li>Bônus: dica secreta para manter consistência</li>
        </ul>
        <p class="price">Preço especial: <strong>R$ 197</strong></p>
        <a href="https://SEU_LINK_DE_AFILIADO_HIGH_TICKET" class="btn-secondary" target="_blank" rel="noopener">Quero o método completo</a>
        <p class="urgency">Últimas vagas com bônus — expira em <span id="countdown">03d 12h</span></p>
      </div>

      <div class="lead-capture">
        <h3>Receba o mini-guia grátis</h3>
        <p>3 erros que travam sua perda de gordura e o plano rápido para corrigir.</p>
        <form id="lead-form">
          <input type="email" placeholder="Seu melhor e-mail" required />
          <button type="submit">Quero o guia</button>
        </form>
        <p class="disclaimer">Você será redirecionado e receberá e-mail com o material. Sem spam.</p>
      </div>
    </div>
  </section>

  <footer class="footer">
    <div class="container">
      <p>🔗 Este site usa links de afiliado. Se você comprar através do link, posso receber uma comissão sem custo extra pra você. Obrigado pelo apoio.</p>
      <p>&copy; 2025 Transformação Fitness. Todos os direitos reservados.</p>
    </div>
  </footer>

  <script>
    const countdownEl = document.getElementById('countdown');
    let days = 3, hours = 12;
    setInterval(() => {
      if (hours === 0) {
        if (days > 0) { days--; hours = 23; }
      } else {
        hours--;
      }
      countdownEl.textContent = `${String(days).padStart(2,'0')}d ${String(hours).padStart(2,'0')}h`;
    }, 3600000);

    document.getElementById('lead-form').addEventListener('submit', e => {
      e.preventDefault();
      alert('Obrigado! Verifique seu e-mail para o mini-guia.'); // substituir por integração real
    });
  </script>
</body>
</html>
