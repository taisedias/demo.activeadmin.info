<h1>Pré-requistos</h1>
<ol>
  <li>Instalar <a target="_BLANK" href="https://github.com/sstephenson/rbenv">Rbenv</a> ou <a target="_BLANK" href="http://rvm.io/rvm/install">RVM</a></li>
  <li>Ruby
    <ul>
      <li><a target="_BLANK" href="http://rubyinstaller.org/">windows installer</a></li>
      <li><a target="_BLANK" href="https://github.com/sstephenson/rbenv#installing-ruby-versions">unix</a></li>
    </ul>
  </li>
  <li>Sqlite</li>
  <li>Instalar o <a target="_BLANK" href="http://bundler.io/">bundler</a></li>
</ol>

<h1>Rodando a aplicação</h1>
<ol>
  <li>Baixar o repostitório</li>
  <li>Executar "bundle install" no root do projeto para instalar todas as dependências definidas no Gemfile</li>
  <li>Executar "rake db:migrate" para criar todas as tabelas do banco</li>
  <li>Executar "rake db:seed" para criar vários dados (produtos e usuários)</li>
  <li>Executar "rails s" para subir a aplicação.</li>
  <li>No browser, acessar o seguinte endereço: "http://localhost:3000"</li>
</ol>

