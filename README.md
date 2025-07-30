# Zonas de Restrição de Voo para Drones no QGIS

Este plugin para QGIS permite a criação automatizada de zonas de restrição de voo para aeronaves remotamente pilotadas (drones), com base em critérios espaciais definidos e em conformidade com a **ICA 100-40**, da Força Aérea Brasileira que trata do acesso ao espaço aéreo por esses sistemas.

## Funcionalidades

* Geração de zonas de restrição com buffers concêntricos ao pista de aeródromo.
* Interface intuitiva com botão de execução direto na barra de ferramentas do QGIS.
* Compatível com sistemas de coordenadas projetadas (UTM).

## Requisitos

* QGIS 3.x
* Bibliotecas padrão do PyQGIS

## Instalação

1. Clone ou baixe este repositório.
2. Copie a pasta do plugin para o diretório de plugins do QGIS (normalmente `~/.local/share/QGIS/QGIS3/profiles/default/python/plugins` em sistemas Linux).
3. Ative o plugin no QGIS via `Complementos > Gerenciar e Instalar Complementos`.

## Como Usar

1. Carregue suas camadas de interesse (por exemplo, camadas de pontos de interesse e da área geográfica a ser analisada).
2. Selecione uma feição da camada base (pista de aeródromo).
3. Clique no botão do plugin para executar a criação das zonas.
4. A camada gerada aparecerá no painel de camadas com o nome apropriado.

## Referência Normativa

As zonas de restrição seguem as diretrizes estabelecidas pela **ICA 100-40**, documento emitido pelo Departamento de Controle do Espaço Aéreo (DECEA), que regulamenta a operação de drones no espaço aéreo brasileiro.

## Licença

Este plugin é licenciado sob os termos da licença MIT.

## Autor

**Edson Tadeu da Silva Pinto**

Engenheiro Cartógrafo | Capitão do Exército Brasileiro

Desenvolvido no âmbito de estudos e aplicações em geotecnologias e segurança do espaço aéreo.

+ &copy;2025 Edson Tadeu da Silva Pinto
