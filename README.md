<h1>Desafio de Assinatura de Commits com GPG</h1>
    <p>Este repositório contém um exemplo de como realizar e verificar commits assinados utilizando GPG (GNU Privacy Guard) no GitHub. A assinatura de commits é uma prática importante para aumentar a segurança e garantir que os commits foram realmente realizados por um desenvolvedor autenticado.</p>

    <h2>Como Realizar um Commit Assinado</h2>
    <ol>
        <li><strong>Configurar a Chave GPG:</strong> Certifique-se de que você tenha uma chave GPG configurada em sua máquina. Você pode gerar uma nova chave GPG ou usar uma existente.</li>
        <li><strong>Configurar o Git:</strong> Configure o Git para usar a sua chave GPG. Você pode fazer isso executando o seguinte comando e escolhendo a chave correta:
            <pre><code>git config --global user.signingkey SUA_CHAVE_GPG</code></pre>
        </li>
        <li><strong>Realizar um Commit Assinado:</strong> Ao realizar um commit, utilize a opção <code>-S</code> ou <code>--gpg-sign</code> para assinar o commit com a sua chave GPG. Por exemplo:
            <pre><code>git commit -S -m "Sua mensagem de commit aqui"</code></pre>
        </li>
        <li><strong>Push para o GitHub:</strong> Após realizar o commit assinado, faça o push das suas alterações para o GitHub. O commit assinado será exibido com um ícone de cadeado no GitHub, indicando que ele está assinado digitalmente.</li>
    </ol>

    <h2>Como Verificar um Commit Assinado</h2>
    <p>Para verificar a assinatura de um commit no GitHub:</p>
    <ol>
        <li>Acesse o commit no GitHub.</li>
        <li>Clique no link "Verificado" ao lado do nome do autor do commit.</li>
        <li>Você verá informações sobre a assinatura GPG, incluindo a chave usada e se a assinatura é válida.</li>
    </ol>

    <h2>Exemplo</h2>
    <p>Neste repositório, você encontrará um commit de exemplo que foi assinado com uma chave GPG. Sinta-se à vontade para examiná-lo para ver como a assinatura aparece no GitHub.</p>

    <p>Lembre-se de que a assinatura de commits é uma prática importante para aumentar a segurança e a integridade do seu código. Certifique-se de configurar corretamente as suas chaves GPG e utilizar commits assinados em projetos importantes.</p>
</body>
</html>