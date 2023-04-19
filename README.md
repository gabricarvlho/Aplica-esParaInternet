<!DOCTYPE html>
<html>
        <head>
            <title>Página Html</title>
        </head>
        <body style="margin: 0;">
            <header id="topo" style="text-align: center; background-color: rgba(56, 12, 218, 0.89); padding: 10px;font-size: 30px;">
                <h1>HTML<sup>Marcação de Hipertexto</sup></h1>
                <h2>Tutoriais para iniciantes</h2>
            </header>
            <nav style="margin: 0;">
                <ul
                style="list-style: none; display: flex;justify-content: space-between;background-color: rgb(184, 115, 11); padding: 10px;">
                <li style="flex-grow: 1;"><a href="aula2.html" style=" text-decoration: none;">Inicio</a></li>
                <li style="flex-grow: 1;"><a href="aula2.html#HTML" style="text-decoration: none;">HTML</a></li>
                <li style="flex-grow: 1;"><a href="aula2.html#tabela" style="text-decoration: none;">Tabela e Lista</a></li>
                <li style="flex-grow: 1;"><a href="aula2.html#sobre" style="text-decoration: none">Sobre HTML, CSS e JS</a>
                <li style="flex-grow: 1;"><a href="aula2.html#rodape" style="text-decoration: none">Links</a></li>
                <li style="flex-grow: 1;"><a href="contato.html" style="text-decoration: none">Contato</a></li>
                </ul>
            </nav>
            <section style="width: 10%;margin-top: 30px;"><img align="left" width="180" height="100" hspace="10"
                    src="https://sp-ao.shortpixel.ai/client/to_webp,q_glossy,ret_img,w_740,h_354/https://devporai.com.br/wp-content/uploads/2020/09/html5-740x354.jpg">
            </section>
            <p id="HTML" style="width: 70%;"><b>HTML </b><i>(Linguagem de Marcação de Hipertexto)</i>
                é o bloco de construção mais básico da web. <mark>Define o <br>
                    significado e a estrutura do conteúdo da web.</mark> Outras tecnologias além do HTML geralmente são <br>
                usadas para descrever a aparência/apresentação (CSS) ou a funcionalidade/comportamento <br>
                <i>(JavaScript)</i> de uma página da web.
            </p>
            <br>
            <hr>
            <section id="tabela" style="display: flex;">
                <div style="width:50%;background-color: aqua;display: flex;">
                    <table style="background-color: aqua;border: 2px;" border="1" align="center">
                        <thead>
                            <caption>Tags úteis</caption>
                            <tr>
                            <tr>
                                <th colspan="2">Tabela de Tags</th>
                            </tr>
                            <th>Tag</th>
                            <th>Utilidade</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr>
                                <td align="center">a</td>
                                <td> Adiciona um link na marcação </td>
                            </tr>
                            <tr>
                                <td align="center">img</td>
                                <td>Adiciona uma imagem no código</td>
                            </tr>
                            <tr>
                                <td align="center">hr</td>
                                <td>Adiciona uma linha horizontal</td>
                            </tr>
                            <tr>
                                <td align="center">strong</td>
                                <td>Formata o texto em destaque</td>
                            </tr>
                            <tr>
                                <td align="center">sub</td>
                                <td>Formata o texto subescrito</td>
                            </tr>
                            <tr>
                                <td align="center">p</td>
                                <td>Abre um paragrafo</td>
                            </tr>
                            <tr>
                                <td align="center">h1</td>
                                <td>Define o cabeçalho 1</td>
                            </tr>
                            <tr>
                                <td align="center">ins</td>
                                <td>Formata um texto sublinhado</td>
                            </tr>
                        </tbody>
                    </table>
                </div>
                <div style="width:50%;background-color: rgb(110, 91, 91);display: flex;align-items: center;">
                    <p><h2>Exemplos de protocolos Web</h2>:</p>
                    <ol type="a">
                        <li>FTP: File Transfer Protocol</li>
                        <li>HTTP: Hypertext Transfer Protocol</li>
                        <li>POP: Email Transfer Protocol</li>
                        <li>IP: Internet Protocol</li>
                        <li>SSL: Secure Sockets Layer</li>
                    </ol>
                    <ul>
                        <li>FTP: File Transfer Protocol</li>
                        <li>HTTP: Hypertext Transfer Protocol</li>
                        <li>POP: Email Transfer Protocol</li>
                        <li>IP: Internet Protocol</li>
                        <li>SSL: Secure Sockets Layer</li>
                    </ul>
                </div>
            </section>
            <section id="sobre" style="display:flex;align-items: baseline;column-gap: 5px;">
                <section style="background-color: rgb(53, 107, 109);width: 33.3%;height: 200px;padding: 20px;">
                    <h2>
                        O que é CSS?
                    </h2>
                    <p>CSS é a sigla para o termo em inglês Cascading Style Sheets que, traduzido para o português, significa
                        Folha de Estilo em Cascatas. O CSS é fácil de aprender e entender e é facilmente utilizado com as
                        linguagens de marcação HTML ou XHTML. </p>
                </section>
                <section style="background-color: rgb(250, 0, 0);width: 33.3%;height: 200px;padding: 20px;">
                    <h2>
                        O que é HTML?
                    </h2>
                    <p>O HTML é o componente básico da web, ele permite inserir o conteúdo e estabelecer a estrutura básica de
                        um website. Portanto, ele serve para dar significado e organizar as informações de uma página na web.
                        Sem isso, o navegador não saberia exibir textos como elementos ou carregar imagens e outros conteúdos.
                    </p>
                </section>
                <section style="background-color: rgb(73, 78, 65);width: 33.3%;height: 200px;padding: 20px;">
                    <h2>
                        O que é JavaScript?
                    </h2>
                    <p>JavaScript é uma linguagem de programação interpretada estruturada, de script em alto nível com tipagem
                        dinâmica fraca e multiparadigma. Juntamente com HTML e CSS, o JavaScript é uma das três principais
                        tecnologias da World Wide Web.</p>
                </section>
            </section>
            <hr>
            <footer id="rodape" style="padding: auto;">
                <div style="display: flex;align-items: baseline;column-gap: 5px;">
                    <section style="width: 25%; background-color: rgb(155, 52, 52);">
                        <p>Sobre</p>
                        <ul>
                            <li><a href="aula2.html#topo">Topo</a></li>
                            <li>Politica de privacidade</li>
                            <li><a href="Dados.html">Fale conosco</a></li>
                        </ul>
                    </section>
                    <section style="width: 25%; background-color: rgb(153, 153, 150);">
                        <p>Referências</p>
                        <ul>
                            <li><a href="https://devporai.com.br" target="blank">Devporai</a></li>
                            <li><a href="https://google.com.br" target="blank">Google</a></li>
                            <li><a href="https://wikipedia.com" target="blank">Wikipedia</a></li>
                        </ul>
                    </section>
                    <section style="width: 25%; background-color: rgb(155, 52, 52);">
                        <p>Tutoriais</p>
                        <ul>
                            <li>Empreendedorismo</li>
                            <li>Programação</li>
                            <li>Marketing</li>
                        </ul>
                    </section>
                    <section style="width: 25%;background-color: rgb(153, 153, 150);">
                        <p>Outros Links</p>
                        <ul>
                            <li><a href="https://www.instagram.com">Instagram</a></li>
                            <li><a href="https://www.twitter.com/">Twitter</a></li>
                            <li><a href="https://www.correios.com.br">Correios</a></li>
                        </ul>
                    </section>
                </div>
                <div style="width: 100%; text-align: center;">
                    <p>Gabriel Fernandes de Carvalho&copy</p>
                </div>
            </footer>
        </body>

        </html>
