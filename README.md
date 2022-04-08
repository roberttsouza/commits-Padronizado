<h1 align="center">
<img src="https://media.giphy.com/media/W85Znx8E1E6yaz5H2C/giphy.gif" width="80"><br>commits Padronizado
</h1>


De acordo com a documentação do [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) A especificação de Commits Convencionais é uma convenção simples em cima das mensagens de confirmação. Ele fornece um conjunto fácil de regras para criar um histórico de confirmação explícito; o que torna mais fácil escrever ferramentas automatizadas em cima. Essa convenção se encaixa com o SemVer, descrevendo os recursos, correções e alterações importantes feitas nas mensagens de confirmação.

----

## 👾 Tipos de commits

- `feat` são quaisquer adições ao código. Enquanto elas podem alterar parte do código já existente, o foco dela é a implementação de features novas ao ecossistema.
- `fix` refere-se às correções de bugs. Caso seu time trabalhe com issues ou com Jira, é possível com smart commits associar seu commit a uma issue e alterar seu estado com keywords como resolve, fix, solves. Em geral, essas marcações devem vir na descrição ou no footer.
- `refactor` refere-se a quaisquer mudanças que atinjam o código, porém não alterem sua funcionalidade. Alterou o formato de como é processamento em determinada parte da sua tela, mas manteve a mesma funcionalidade? Declare como refactor.
- `style` São alterações referentes a formatações de código, semicolons, trailing spaces e lint
- `Chore` Utilizado na atualização para mudanças em ferramentas, configurações e bibliotecas. Atualizações que não ocasionam em alteração no código de produção.
- `Doc` Utilizado quando é adicionado ou atualizado alguma documentação no projeto.
- `Test` Utilizado quando feita qualquer alteração em relação aos testes do projeto.

----

## <img src="https://media.giphy.com/media/lRc0riwAfCcK3stcr2/giphy.gif" width="50px">Recomendações de uso

- No titulo resumir em 4 palavras
- Na descrição tentar deixar o mais claro possível oque foi feito no commit
- Nos links, não ultilizar encurtador ou redirecionador
- Usar o emoji corespondente ao commit

----

## <img src="https://media.giphy.com/media/ctBY5QMBfJ4QgkQkeL/giphy.gif" width="30px"> Emoji padão

<table>
  <thead>
    <tr>
      <th>Tipo de commit</th>
      <th>Emojis</th>
    </tr>
  </thead>
 <tbody>
    <tr>
      <td>Acessibilidade</td>
      <td>♿ <code>:wheelchair:</code></td>
    </tr>
    <tr>
      <td>Adicionando um teste</td>
      <td>✅ <code>:white_check_mark:</code></td>
    </tr>
    <tr>
      <td>Adicionando uma dependência</td>
      <td>➕ <code>:heavy_plus_sign:</code></td>
    </tr>
    <tr>
      <td>Alterações de revisão de código</td>
      <td>👌 <code>:ok_hand:</code></td>
    </tr>
    <tr>
      <td>Animações e transições</td>
      <td>💫 <code>:dizzy:</code></td>
    </tr>
    <tr>
      <td>Bugfix</td>
      <td>🐛 <code>:bug:</code></td>
    </tr>
    <tr>
      <td>Comentários</td>
      <td>💡 <code>:bulb:</code></td>
    </tr>
    <tr>
      <td>Commit inicial</td>
      <td>🎉 <code>:tada:</code></td>
    </tr>
    <tr>
      <td>Configuração</td>
      <td>🔧 <code>:wrench:</code></td>
    </tr>
    <tr>
      <td>Deploy</td>
      <td>🚀 <code>:rocket:</code></td>
    </tr>
    <tr>
      <td>Documentação</td>
      <td>📚 <code>:books:</code></td>
    </tr>
    <tr>
      <td>Em progresso</td>
      <td>🚧 <code>:construction:</code></td>
    </tr>
    <tr>
      <td>Estilização de interface</td>
      <td>💄 <code>:lipstick:</code></td>
    </tr>
    <tr>
      <td>Infraestrutura</td>
      <td>🧱 <code>:bricks:</code></td>
    </tr>
    <tr>
      <td>Lista de ideias (tasks)</td>
      <td>🔜 <code> :soon: </code></td>
    </tr>
    <tr>
      <td>Mover/Renomear</td>
      <td>🚚 <code>:truck:</code></td>
    </tr>
    <tr>
      <td>Novo recurso</td>
      <td>✨ <code>:sparkles:</code></td>
    </tr>
    <tr>
      <td>Package.json em JS</td>
      <td>📦 <code>:package:</code></td>
    </tr>
    <tr>
      <td>Performance</td>
      <td>⚡ <code>:zap:</code></td>
    </tr>
    <tr>
        <td>Refatoração</td>
        <td>♻️ <code>:recycle:</code></td>
    </tr>
    <tr>
      <td>Removendo um arquivo</td>
      <td>🔥 <code>:fire:</code></td>
    </tr>
    <tr>
      <td>Removendo uma dependência</td>
      <td>➖ <code>:heavy_minus_sign:</code></td>
    </tr>
    <tr>
      <td>Responsividade</td>
      <td>📱 <code>:iphone:</code></td>
    </tr>
    <tr>
      <td>Revertendo mudanças</td>
      <td>💥 <code>:boom:</code></td>
    </tr>
    <tr>
      <td>Segurança</td>
      <td>🔒️ <code>:lock:</code></td>
    </tr>
    <tr>
      <td>SEO</td>
      <td>🔍️ <code>:mag:</code></td>
    </tr>
    <tr>
      <td>Tag de versão</td>
      <td>🔖 <code>:bookmark:</code></td>
    </tr>
    <tr>
      <td>Teste de aprovação</td>
      <td>✔️ <code>:heavy_check_mark:</code></td>
    </tr>
    <tr>
      <td>Testes</td>
      <td>🧪 <code>:test_tube:</code></td>
    </tr>
    <tr>
      <td>Texto</td>
      <td>📝 <code>:pencil:</code></td>
    </tr>
    <tr>
      <td>Tipagem</td>
      <td>🏷️ <code>:label:</code></td>
    </tr>
    <tr>
      <td>Tratamento de erros</td>
      <td>🥅 <code>:goal_net:</code></td>
    </tr>
  </tbody>
</table>

----

## <img src="https://media.giphy.com/media/lRLzrbhmh5pFf4jOga/giphy.gif" width="50px"> Exemplos de ultilização dos emoji

<table>
  <thead>
    <tr>
      <th>Comando git</th>
      <th>Resultado no GitHub</th>
    </tr>
  </thead>
 <tbody>
    <tr>
      <td>
        <code>git commit -m ":tada: Commit inicial"</code>
      </td>
      <td>🎉 Commit inicial</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":books: docs: Atualizaçao do README"</code>
      </td>
      <td>📚 docs: Atualizaçao do README</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":bug: fix: Loop infinito na linha 50"</code>
      </td>
      <td>🐛 fix: Loop infinito na linha 50</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":sparkles: feat: Pagina de login"</code>
      </td>
      <td>✨ feat: Pagina de login</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":bricks: ci: Modificaçao no Dockerfile"</code>
      </td>
      <td>🧱 ci: Modificaçao no Dockerfile</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":recycle: refactor: Passando para arrow functions"</code>
      </td>
      <td>♻️ refactor: Passando para arrow functions</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":zap: perf: Melhoria no tempo de resposta"</code>
      </td>
      <td>⚡ perf: Melhoria no tempo de resposta</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":boom: fix: Revertendo mudanças ineficientes"</code>
      </td>
      <td>💥 fix: Revertendo mudanças ineficientes</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":lipstick: feat: Estilizaçao CSS do formulario"</code>
      </td>
      <td>💄 feat: Estilizaçao CSS do formulario</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":test_tube: feat: Estilizaçao CSS do formulario"</code>
      </td>
      <td>🧪 test: Criando novo teste</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":test_tube: feat: Estilizaçao CSS do formulario"</code>
      </td>
      <td>💡 docs: Comentários sobre a função LoremIpsum( )</td>
    </tr>
  </tbody>
</table>

