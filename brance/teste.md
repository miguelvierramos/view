<style>
  body {
    font-family: Arial, sans-serif;
    background-color: #f2f2f2;
    color: #333;
    padding: 2rem;
    max-width: 900px;
    margin: auto;
  }
  h1 {
    color: #0056b3;
    font-size: 3rem;
    border-bottom: 2px solid #0056b3;
    padding-bottom: 0.3rem;
  }
  h2 {
    color: #007acc;
    font-size: 2rem;
    margin-top: 2rem;
  }
  p {
    font-size: 1.1rem;
    line-height: 1.6;
  }
  code {
    background: #e4e4e4;
    padding: 2px 5px;
    border-radius: 4px;
  }
  pre {
    background: #1e1e1e;
    color: #dcdcdc;
    padding: 1rem;
    border-radius: 5px;
    overflow-x: auto;
  }
</style>

<h1>Git e GitHub</h1>

<p><strong>Git</strong> é um sistema de controle de versão distribuído. Ele permite acompanhar mudanças no código, voltar no tempo, trabalhar em equipe e evitar conflitos durante o desenvolvimento.</p>

<h2>Principais comandos do Git</h2>

<pre><code>git init          # Inicia um repositório local
git status        # Mostra o estado atual dos arquivos
git add .         # Adiciona arquivos para serem commitados
git commit -m ""  # Cria um ponto de salvamento
git push          # Envia alterações para o GitHub
git pull          # Baixa alterações do GitHub
</code></pre>

<h2>O que é GitHub?</h2>

<p><strong>GitHub</strong> é uma plataforma de hospedagem de código que usa o Git. Ele permite que desenvolvedores publiquem seus projetos na internet, colaborem com outras pessoas e acompanhem versões do código.</p>

<h2>Diferenças entre Git e GitHub</h2>

<ul>
  <li><strong>Git</strong> é a ferramenta de controle de versão local.</li>
  <li><strong>GitHub</strong> é uma plataforma online que hospeda repositórios Git.</li>
</ul>

<h2>Fluxo básico de trabalho</h2>

<ol>
  <li>Crie um projeto e inicie o Git: <code>git init</code></li>
  <li>Adicione arquivos: <code>git add .</code></li>
  <li>Comite as mudanças: <code>git commit -m "mensagem"</code></li>
  <li>Crie um repositório no GitHub</li>
  <li>Conecte ao repositório remoto: <code>git remote add origin URL</code></li>
  <li>Envie o código: <code>git push -u origin master</code></li>
</ol>

<p>Esse é um exemplo básico de como documentar seu projeto em Markdown com HTML e CSS para uma visualização mais bonita.</p>
