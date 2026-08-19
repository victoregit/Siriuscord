# Siriuscord

O **Siriuscord** é uma versão personalizada e não oficial do cliente open source [Stoat](https://github.com/stoatchat), criada para o nosso grupo de amigos e inspirada na identidade do nosso servidor do Discord.

## Por que criei o projeto?

O projeto nasceu durante um período em que tivemos dificuldades para usar o compartilhamento de tela do Discord no Brasil. Como essa funcionalidade é importante para o nosso grupo — para conversar, jogar, assistir e compartilhar conteúdo — procurei uma alternativa aberta que pudesse ser adaptada às nossas necessidades.

Encontrei no Stoat uma base funcional e de código aberto. A partir dela, criei uma experiência temática para a nossa comunidade, mantendo a compatibilidade com o serviço original e concentrando as alterações no cliente.

O objetivo não é contornar mecanismos ou restrições do Discord. O Siriuscord é uma alternativa independente, construída sobre outro projeto open source.

## O que foi personalizado?

- Identidade visual e nome Siriuscord;
- ícone e tela de carregamento próprios;
- página inicial temática do nosso servidor;
- experiência de chamadas e compartilhamento de tela mais próxima daquela à qual o grupo estava acostumado;
- visualização expandida e miniatura persistente do compartilhamento;
- acesso mais direto aos canais de voz;
- indicação de quem está falando com resposta mais rápida;
- aplicativo Windows com o cliente web incorporado, sem exigir hospedagem própria do frontend.

## Instalação

### Instalador recomendado

Execute `Siriuscord-Setup.exe` e aguarde a instalação.

### Versão portátil

Extraia `Siriuscord-win32-x64-1.0.8.zip` e execute o aplicativo dentro da pasta extraída.

O Windows pode mostrar um aviso porque o instalador é uma compilação independente e não possui certificado comercial de assinatura de código. Confirme sempre que o arquivo veio da publicação oficial deste projeto e confira o hash quando ele estiver disponível.

## Base open source

O Siriuscord foi desenvolvido a partir dos projetos oficiais:

- Cliente web: [stoatchat/for-web](https://github.com/stoatchat/for-web)
- Aplicativo desktop: [stoatchat/for-desktop](https://github.com/stoatchat/for-desktop)
- Plataforma/API: [stoatchat/stoatchat](https://github.com/stoatchat/stoatchat)

As alterações desta versão estão concentradas principalmente no frontend e no empacotamento desktop. O backend e os contratos da API não foram modificados.

## Licença e créditos

Este trabalho derivado mantém a licença **GNU Affero General Public License v3.0 (AGPL-3.0)** da base original. Consulte o arquivo `LICENSE` incluído nesta pasta.

Stoat e os respectivos projetos pertencem aos seus autores e colaboradores. Discord é uma marca de seus respectivos proprietários. Siriuscord é um projeto comunitário independente, sem afiliação, aprovação ou suporte oficial do Stoat ou do Discord.

Ao distribuir os binários desta versão, o código-fonte correspondente e as informações de licença também devem permanecer acessíveis, de acordo com a AGPLv3.

## Versão

**Siriuscord 1.0.8 — Windows x64**

Criado como um projeto pessoal para transformar uma limitação enfrentada pelo nosso grupo em uma oportunidade de aprender, adaptar software livre e construir algo com a identidade da nossa comunidade.
