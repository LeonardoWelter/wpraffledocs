Como usar
=====

.. _installation:

Instalação
------------

Para instalar o WP Raffle, primeiramente selecione a aba "Plugins" no menu administrativo do Wordpress:

.. figure:: https://raw.githubusercontent.com/LeonardoWelter/wpraffledocs/main/docs/images/wpraffle_docs_plugins_page2.png
   :width: 60%
   :align: center
   :alt: Página de plugins do Wordpress

   Página de plugins do Wordpress

Selecione "Adicionar Novo" no topo da página, e então selecione "Enviar Plugin":

.. figure:: https://raw.githubusercontent.com/LeonardoWelter/wpraffledocs/main/docs/images/wpraffle_docs_plugins_store2.png
   :width: 60%
   :align: center
   :alt: Página de envio de plugins Wordpress

   Página de envio de plugins Wordpress

Clique em "Procurar", selecione o arquivo ``wpraffle.zip`` e clique em "Instalar agora":

.. figure:: https://raw.githubusercontent.com/LeonardoWelter/wpraffledocs/main/docs/images/wpraffle_docs_plugin_send.png
   :width: 60%
   :align: center
   :alt: Enviando o plugin

   Enviando o plugin

Após enviar, aparecerá uma página informando o status da instalação do plugin, clique em "Ativar Plugin" para finalizar a instalação:

.. figure:: https://raw.githubusercontent.com/LeonardoWelter/wpraffledocs/main/docs/images/wpraffle_docs_plugin_install.png
   :width: 60%
   :align: center
   :alt: Instalando o plugin

   Instalando o plugin

Pronto, a instalação foi finalizada e a página de configuração do plugin pode ser encontrada no menu do Wordpress:

.. figure:: https://raw.githubusercontent.com/LeonardoWelter/wpraffledocs/main/docs/images/wpraffle_docs_admin_menu.png
   :width: 60%
   :align: center
   :alt: Menu do Wordpress

   Menu do Wordpress

Ao selecionar WP Raffle no menu, você será direcionado a dashboard do plugin:

.. figure:: https://raw.githubusercontent.com/LeonardoWelter/wpraffledocs/main/docs/images/wpraffle_docs_dashboard.png
   :width: 60%
   :align: center
   :alt: Dashboard

   Dashboard

Criando sua primeira rifa
----------------

Para criar a sua primeira rifa, no dashboard do plugin, clique em Sorteios.

.. figure:: https://raw.githubusercontent.com/LeonardoWelter/wpraffledocs/main/docs/images/wpraffle_docs_dashboard.png
   :width: 60%
   :align: center
   :alt: Dashboard WP Raffle

   Dashboard WP Raffle

Na página dos Sorteios, clique em "Novo Sorteio" no canto superior direito:

.. figure:: https://raw.githubusercontent.com/LeonardoWelter/wpraffledocs/main/docs/images/wpraffle_docs_raffle_index.png
   :width: 60%
   :align: center
   :alt: Página Sorteios

   Página Sorteios

Na página seguinte, preencha os dados do formulário e clique no botão "Criar":

.. figure:: https://raw.githubusercontent.com/LeonardoWelter/wpraffledocs/main/docs/images/wpraffle_docs_raffle_add.png
   :width: 60%
   :align: center
   :alt: Página de Criação de Sorteio

   Página de Criação de Sorteio

Após a criação, você será redirecionado a listagem dos sorteios criados, clique no botão com o ícone da prancheta para copiar o shortcode da rifa criada:

.. figure:: https://raw.githubusercontent.com/LeonardoWelter/wpraffledocs/main/docs/images/wpraffle_docs_raffle_index_shortcode.png
   :width: 60%
   :align: center
   :alt: Copiando o shortcode da Rifa criada

   Copiando o shortcode da Rifa criada

Após copiar o shortcode, deveremos inserir o mesmo em uma página.

Configurando a página da Rifa
----------------

Para disponibilizar o componente da rifa, basta inserir o shortcode em alguma página.

.. note::

   O componente da rifa inclui somente os números e as funções necessárias para reservar os mesmos, fica a cargo do administrador do site criar a apresentação da rifa.

Selecione uma página, insira um bloco de shortcode:

.. figure:: https://raw.githubusercontent.com/LeonardoWelter/wpraffledocs/main/docs/images/wpraffle_docs_add_block.png
   :width: 60%
   :align: center
   :alt: Inserindo bloco de Shortcode

   Inserindo bloco de Shortcode

Coloque o shortcode ``[lwraffle id=1]`` copiado anteriormente e salve a página:

.. note::

   O shortcode pode ser copiado no menu do plugin em Sorteios.

.. figure:: https://raw.githubusercontent.com/LeonardoWelter/wpraffledocs/main/docs/images/wpraffle_docs_add_shortcode.png
   :width: 60%
   :align: center
   :alt: Inserindo o shortcode

   Inserindo o shortcode

.. note::

   Na imagem é inserido o shortcode da Rifa id=5, devido a testes feitos anteriormente.

Se visitar a página onde foi inserido o shortcode, o componente da rifa estará funcionando:

.. figure:: https://raw.githubusercontent.com/LeonardoWelter/wpraffledocs/main/docs/images/wpraffle_docs_shortcode_numbers.png
   :width: 60%
   :align: center
   :alt: Componente da Rifa

   Componente da Rifa

Configurando a página de checkout
----------------

Para completar a reserva de um número da rifa, é necessário uma página de checkout.

.. note::

   O shortcode de checkout foi criado para representar uma página completa, por isso deve ser inserido em uma nova página

No menu do Wordpress, selecione "Páginas" e em seguida "Adicionar Nova"

.. figure:: https://raw.githubusercontent.com/LeonardoWelter/wpraffledocs/main/docs/images/wpraffle_docs_pages2.png
   :width: 60%
   :align: center
   :alt: Páginas do Wordpress

   Páginas do Wordpress

Adicione um título a pagina, esse título será usado como o link para a página

Configure sua página para não mostrar Barra Lateral, Título, Rodapé, Caminho de navegação e deixe a página com a Largura Total:

.. note::

   A imagem abaixo mostra as configurações do tema `Astra`

.. figure:: https://raw.githubusercontent.com/LeonardoWelter/wpraffledocs/main/docs/images/wpraffle_docs_astra_page_config.png
   :width: 60%
   :align: center
   :alt: Configurações da página

   Configurações da página

Após configurar, selecione o ``+`` e adicione um bloco de Shortcode:

.. figure:: https://raw.githubusercontent.com/LeonardoWelter/wpraffledocs/main/docs/images/wpraffle_docs_add_block_co.png
   :width: 60%
   :align: center
   :alt: Adicionando Shortcode

   Adicionando Shortcode

Dentro do bloco de Shortcode, digite ``[lwraffle-shortcode]`` e clique em "Atualizar" no canto superior direito:

.. figure:: https://raw.githubusercontent.com/LeonardoWelter/wpraffledocs/main/docs/images/wpraffle_docs_shortcode_checkout.png
   :width: 60%
   :align: center
   :alt: Shortcode do Plugin

   Shortcode do Plugin

Alterando as configurações do plugin
----------------

Para ir até a página de configuração do plugin, clique em "Configurações" no menu do plugin:

.. figure:: https://raw.githubusercontent.com/LeonardoWelter/wpraffledocs/main/docs/images/wpraffle_docs_menu_config.png
   :width: 60%
   :align: center
   :alt: Menu de configurações

   Menu de configurações

A primeira aba mostra as "Configurações Gerais":

.. note::

   É necessário configurar o link da página do checkout, caso contrário o plugin não irá funcionar corretamente.

Configure a URL da página de checkout criada anteriormente:

.. figure:: https://raw.githubusercontent.com/LeonardoWelter/wpraffledocs/main/docs/images/wpraffle_docs_config_geral.png
   :width: 60%
   :align: center
   :alt: Configurações Gerais

   Configurações Gerais

As configurações de Email e WhatsApp dessa página são usadas para a confirmação do pagamento:

A segunda e a terceira aba mostram as configurações das formas de pagamento:

.. note::

   Caso nenhuma forma de pagamento seja configurada, o usuário não terá como pagar pelos números

As formas de pagamento pode ser ativadas e desativas individualmente:

.. figure:: https://raw.githubusercontent.com/LeonardoWelter/wpraffledocs/main/docs/images/wpraffle_docs_config_pix.png
   :width: 60%
   :align: center
   :alt: Configurações Pix

   Configurações Pix

.. note::

   Para gerar o Token do PagSeguro siga o <a class="reference external" href="https://faq.pagseguro.uol.com.br/duvida/como-gerar-token-para-integracao-com-o-site/841#rmcl">tutorial como criar token</a>.

.. figure:: https://raw.githubusercontent.com/LeonardoWelter/wpraffledocs/main/docs/images/wpraffle_docs_config_pagseguro.png
   :width: 60%
   :align: center
   :alt: Configurações PagSeguro

   Configurações PagSeguro

A quarta aba apresenta as "Configurações Email" usadas para o envio do email de reserva e confirmação da compra

.. note::

   Somente emails do Gmail são suportados

Os emails de reserva e confirmação podem ser ativados e desativados conforme a preferência do administrador

.. figure:: https://raw.githubusercontent.com/LeonardoWelter/wpraffledocs/main/docs/images/wpraffle_docs_config_mailer.png
   :width: 60%
   :align: center
   :alt: Configurações do Email

   Configurações do Email

Se a documentação foi seguida, o ambiente de reserva e compra de números já está disponível para uso pelo usuário final.