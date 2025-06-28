# minha-plataforma
<!DOCTYPE html>
<html lang="pt-br" class="h-full bg-gray-100">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Minha Plataforma Completa</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="h-full flex">
  <nav class="fixed top-0 left-0 h-full w-64 bg-white border-r shadow flex flex-col">
    <div class="px-6 py-4 border-b text-xl font-bold text-blue-600 text-center">
      Minha Plataforma
    </div>
    <ul class="flex-1 overflow-y-auto py-4 space-y-1">
      <li><button onclick="showSection('dashboard')" class="w-full text-left block px-6 py-3 hover:bg-blue-100 hover:text-blue-700 transition rounded">Dashboard</button></li>
<li><button onclick="showSection('checkout')" class="w-full text-left block px-6 py-3 hover:bg-blue-100 hover:text-blue-700 transition rounded">Checkout</button></li>
<li><button onclick="showSection('perfil')" class="w-full text-left block px-6 py-3 hover:bg-blue-100 hover:text-blue-700 transition rounded">Perfil</button></li>
<li><button onclick="showSection('area-membros')" class="w-full text-left block px-6 py-3 hover:bg-blue-100 hover:text-blue-700 transition rounded">Area membros</button></li>
<li><button onclick="showSection('mensagens')" class="w-full text-left block px-6 py-3 hover:bg-blue-100 hover:text-blue-700 transition rounded">Mensagens</button></li>
<li><button onclick="showSection('assinaturas')" class="w-full text-left block px-6 py-3 hover:bg-blue-100 hover:text-blue-700 transition rounded">Assinaturas</button></li>
<li><button onclick="showSection('relatorios')" class="w-full text-left block px-6 py-3 hover:bg-blue-100 hover:text-blue-700 transition rounded">Relatorios</button></li>
<li><button onclick="showSection('estatisticas')" class="w-full text-left block px-6 py-3 hover:bg-blue-100 hover:text-blue-700 transition rounded">Estatisticas</button></li>
<li><button onclick="showSection('notificacoes')" class="w-full text-left block px-6 py-3 hover:bg-blue-100 hover:text-blue-700 transition rounded">Notificacoes</button></li>
<li><button onclick="showSection('avaliacoes')" class="w-full text-left block px-6 py-3 hover:bg-blue-100 hover:text-blue-700 transition rounded">Avaliacoes</button></li>
<li><button onclick="showSection('editor-pagina')" class="w-full text-left block px-6 py-3 hover:bg-blue-100 hover:text-blue-700 transition rounded">Editor pagina</button></li>
<li><button onclick="showSection('integracoes')" class="w-full text-left block px-6 py-3 hover:bg-blue-100 hover:text-blue-700 transition rounded">Integracoes</button></li>
<li><button onclick="showSection('produtos')" class="w-full text-left block px-6 py-3 hover:bg-blue-100 hover:text-blue-700 transition rounded">Produtos</button></li>
<li><button onclick="showSection('meus-produtos')" class="w-full text-left block px-6 py-3 hover:bg-blue-100 hover:text-blue-700 transition rounded">Meus produtos</button></li>
<li><button onclick="showSection('cadastro-produto')" class="w-full text-left block px-6 py-3 hover:bg-blue-100 hover:text-blue-700 transition rounded">Cadastro produto</button></li>
<li><button onclick="showSection('usuarios')" class="w-full text-left block px-6 py-3 hover:bg-blue-100 hover:text-blue-700 transition rounded">Usuarios</button></li>
<li><button onclick="showSection('cadastro-usuario')" class="w-full text-left block px-6 py-3 hover:bg-blue-100 hover:text-blue-700 transition rounded">Cadastro usuario</button></li>
<li><button onclick="showSection('pagamentos')" class="w-full text-left block px-6 py-3 hover:bg-blue-100 hover:text-blue-700 transition rounded">Pagamentos</button></li>
<li><button onclick="showSection('cupons')" class="w-full text-left block px-6 py-3 hover:bg-blue-100 hover:text-blue-700 transition rounded">Cupons</button></li>
<li><button onclick="showSection('tickets')" class="w-full text-left block px-6 py-3 hover:bg-blue-100 hover:text-blue-700 transition rounded">Tickets</button></li>
<li><button onclick="showSection('afiliados')" class="w-full text-left block px-6 py-3 hover:bg-blue-100 hover:text-blue-700 transition rounded">Afiliados</button></li>
<li><button onclick="showSection('blog')" class="w-full text-left block px-6 py-3 hover:bg-blue-100 hover:text-blue-700 transition rounded">Blog</button></li>
<li><button onclick="showSection('categorias')" class="w-full text-left block px-6 py-3 hover:bg-blue-100 hover:text-blue-700 transition rounded">Categorias</button></li>
<li><button onclick="showSection('comentarios')" class="w-full text-left block px-6 py-3 hover:bg-blue-100 hover:text-blue-700 transition rounded">Comentarios</button></li>
<li><button onclick="showSection('configuracoes')" class="w-full text-left block px-6 py-3 hover:bg-blue-100 hover:text-blue-700 transition rounded">Configuracoes</button></li>
<li><button onclick="showSection('meu-plano')" class="w-full text-left block px-6 py-3 hover:bg-blue-100 hover:text-blue-700 transition rounded">Meu plano</button></li>
<li><button onclick="showSection('transacoes')" class="w-full text-left block px-6 py-3 hover:bg-blue-100 hover:text-blue-700 transition rounded">Transacoes</button></li>
<li><button onclick="showSection('graficos')" class="w-full text-left block px-6 py-3 hover:bg-blue-100 hover:text-blue-700 transition rounded">Graficos</button></li>
<li><button onclick="showSection('feedbacks')" class="w-full text-left block px-6 py-3 hover:bg-blue-100 hover:text-blue-700 transition rounded">Feedbacks</button></li>
<li><button onclick="showSection('midia')" class="w-full text-left block px-6 py-3 hover:bg-blue-100 hover:text-blue-700 transition rounded">Midia</button></li>
<li><button onclick="showSection('seo')" class="w-full text-left block px-6 py-3 hover:bg-blue-100 hover:text-blue-700 transition rounded">Seo</button></li>
<li><button onclick="showSection('vendas')" class="w-full text-left block px-6 py-3 hover:bg-blue-100 hover:text-blue-700 transition rounded">Vendas</button></li>
<li><button onclick="showSection('faturas')" class="w-full text-left block px-6 py-3 hover:bg-blue-100 hover:text-blue-700 transition rounded">Faturas</button></li>
<li><button onclick="showSection('faq')" class="w-full text-left block px-6 py-3 hover:bg-blue-100 hover:text-blue-700 transition rounded">Faq</button></li>
<li><button onclick="showSection('ajuda')" class="w-full text-left block px-6 py-3 hover:bg-blue-100 hover:text-blue-700 transition rounded">Ajuda</button></li>
    </ul>
    <div class="px-6 py-4 border-t text-sm text-center text-gray-500">
      © 2025 Plataforma Digital
    </div>
  </nav>

  <main class="flex-1 ml-64 p-6 overflow-auto max-h-screen space-y-8">
    <section id='dashboard' style='display:none;'><h1 class='text-2xl font-bold mb-4'>Dashboard</h1><div><p>Conteúdo real da seção <strong>dashboard</strong>.</p></div></section>
<section id='checkout' style='display:none;'><h1 class='text-2xl font-bold mb-4'>Checkout</h1><div><p>Conteúdo real da seção <strong>checkout</strong>.</p></div></section>
<section id='perfil' style='display:none;'><h1 class='text-2xl font-bold mb-4'>Perfil</h1><div><p>Conteúdo real da seção <strong>perfil</strong>.</p></div></section>
<section id='area-membros' style='display:none;'><h1 class='text-2xl font-bold mb-4'>Area membros</h1><div><p>Conteúdo real da seção <strong>area-membros</strong>.</p></div></section>
<section id='mensagens' style='display:none;'><h1 class='text-2xl font-bold mb-4'>Mensagens</h1><div><p>Conteúdo real da seção <strong>mensagens</strong>.</p></div></section>
<section id='assinaturas' style='display:none;'><h1 class='text-2xl font-bold mb-4'>Assinaturas</h1><div><p>Conteúdo real da seção <strong>assinaturas</strong>.</p></div></section>
<section id='relatorios' style='display:none;'><h1 class='text-2xl font-bold mb-4'>Relatorios</h1><div><p>Conteúdo real da seção <strong>relatorios</strong>.</p></div></section>
<section id='estatisticas' style='display:none;'><h1 class='text-2xl font-bold mb-4'>Estatisticas</h1><div><p>Conteúdo real da seção <strong>estatisticas</strong>.</p></div></section>
<section id='notificacoes' style='display:none;'><h1 class='text-2xl font-bold mb-4'>Notificacoes</h1><div><p>Conteúdo real da seção <strong>notificacoes</strong>.</p></div></section>
<section id='avaliacoes' style='display:none;'><h1 class='text-2xl font-bold mb-4'>Avaliacoes</h1><div><p>Conteúdo real da seção <strong>avaliacoes</strong>.</p></div></section>
<section id='editor-pagina' style='display:none;'><h1 class='text-2xl font-bold mb-4'>Editor pagina</h1><div><p>Conteúdo real da seção <strong>editor-pagina</strong>.</p></div></section>
<section id='integracoes' style='display:none;'><h1 class='text-2xl font-bold mb-4'>Integracoes</h1><div><p>Conteúdo real da seção <strong>integracoes</strong>.</p></div></section>
<section id='produtos' style='display:none;'><h1 class='text-2xl font-bold mb-4'>Produtos</h1><div><p>Conteúdo real da seção <strong>produtos</strong>.</p></div></section>
<section id='meus-produtos' style='display:none;'><h1 class='text-2xl font-bold mb-4'>Meus produtos</h1><div><p>Conteúdo real da seção <strong>meus-produtos</strong>.</p></div></section>
<section id='cadastro-produto' style='display:none;'><h1 class='text-2xl font-bold mb-4'>Cadastro produto</h1><div><p>Conteúdo real da seção <strong>cadastro-produto</strong>.</p></div></section>
<section id='usuarios' style='display:none;'><h1 class='text-2xl font-bold mb-4'>Usuarios</h1><div><p>Conteúdo real da seção <strong>usuarios</strong>.</p></div></section>
<section id='cadastro-usuario' style='display:none;'><h1 class='text-2xl font-bold mb-4'>Cadastro usuario</h1><div><p>Conteúdo real da seção <strong>cadastro-usuario</strong>.</p></div></section>
<section id='pagamentos' style='display:none;'><h1 class='text-2xl font-bold mb-4'>Pagamentos</h1><div><p>Conteúdo real da seção <strong>pagamentos</strong>.</p></div></section>
<section id='cupons' style='display:none;'><h1 class='text-2xl font-bold mb-4'>Cupons</h1><div><p>Conteúdo real da seção <strong>cupons</strong>.</p></div></section>
<section id='tickets' style='display:none;'><h1 class='text-2xl font-bold mb-4'>Tickets</h1><div><p>Conteúdo real da seção <strong>tickets</strong>.</p></div></section>
<section id='afiliados' style='display:none;'><h1 class='text-2xl font-bold mb-4'>Afiliados</h1><div><p>Conteúdo real da seção <strong>afiliados</strong>.</p></div></section>
<section id='blog' style='display:none;'><h1 class='text-2xl font-bold mb-4'>Blog</h1><div><p>Conteúdo real da seção <strong>blog</strong>.</p></div></section>
<section id='categorias' style='display:none;'><h1 class='text-2xl font-bold mb-4'>Categorias</h1><div><p>Conteúdo real da seção <strong>categorias</strong>.</p></div></section>
<section id='comentarios' style='display:none;'><h1 class='text-2xl font-bold mb-4'>Comentarios</h1><div><p>Conteúdo real da seção <strong>comentarios</strong>.</p></div></section>
<section id='configuracoes' style='display:none;'><h1 class='text-2xl font-bold mb-4'>Configuracoes</h1><div><p>Conteúdo real da seção <strong>configuracoes</strong>.</p></div></section>
<section id='meu-plano' style='display:none;'><h1 class='text-2xl font-bold mb-4'>Meu plano</h1><div><p>Conteúdo real da seção <strong>meu-plano</strong>.</p></div></section>
<section id='transacoes' style='display:none;'><h1 class='text-2xl font-bold mb-4'>Transacoes</h1><div><p>Conteúdo real da seção <strong>transacoes</strong>.</p></div></section>
<section id='graficos' style='display:none;'><h1 class='text-2xl font-bold mb-4'>Graficos</h1><div><p>Conteúdo real da seção <strong>graficos</strong>.</p></div></section>
<section id='feedbacks' style='display:none;'><h1 class='text-2xl font-bold mb-4'>Feedbacks</h1><div><p>Conteúdo real da seção <strong>feedbacks</strong>.</p></div></section>
<section id='midia' style='display:none;'><h1 class='text-2xl font-bold mb-4'>Midia</h1><div><p>Conteúdo real da seção <strong>midia</strong>.</p></div></section>
<section id='seo' style='display:none;'><h1 class='text-2xl font-bold mb-4'>Seo</h1><div><p>Conteúdo real da seção <strong>seo</strong>.</p></div></section>
<section id='vendas' style='display:none;'><h1 class='text-2xl font-bold mb-4'>Vendas</h1><div><p>Conteúdo real da seção <strong>vendas</strong>.</p></div></section>
<section id='faturas' style='display:none;'><h1 class='text-2xl font-bold mb-4'>Faturas</h1><div><p>Conteúdo real da seção <strong>faturas</strong>.</p></div></section>
<section id='faq' style='display:none;'><h1 class='text-2xl font-bold mb-4'>Faq</h1><div><p>Conteúdo real da seção <strong>faq</strong>.</p></div></section>
<section id='ajuda' style='display:none;'><h1 class='text-2xl font-bold mb-4'>Ajuda</h1><div><p>Conteúdo real da seção <strong>ajuda</strong>.</p></div></section>
  </main>

  <script>
    function showSection(id) {
      const sections = document.querySelectorAll('main section');
      sections.forEach(sec => sec.style.display = 'none');
      const target = document.getElementById(id);
      if (target) target.style.display = 'block';
    }
    document.addEventListener("DOMContentLoaded", () => showSection("dashboard"));
  </script>
</body>
</html>
