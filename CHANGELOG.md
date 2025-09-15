# Changelog

## [1.0.0] - 2025-07-29
- Primeira versão publicada do plugin FRZ.
- Criação automática de zonas de restrição de voo para drones ao redor de aeródromos conforme norma ICA 100-40.
- Execução baseada na feição selecionada, com suporte a projeções UTM.
- Interface simples via botão na barra de ferramentas do QGIS.

## [1.1.0] - 2025-08-11
- Adicionado suporte para geração de zonas de restrição de voo para drones em torno de helipontos, conforme norma ICA 100-40.
- As zonas são criadas a partir da feição selecionada, gerando buffers concêntricos com atributos específicos de limite de voo proibido.
- Inclusão de simbologia dedicada para helipontos e ajustes no processamento para garantir exclusividade da feição selecionada.
- Melhorias gerais na usabilidade e mensagens de feedback ao usuário.

## [1.1.1] - 2025-08-11
- Added a warning to check if the layer is in a projected coordinate system (e.g., UTM).
- Fixed helipad symbology.
- Implemented geometry type validation:
    - Helipads require a Point layer type.
    - Airfields require a Line layer type.
- Processing is automatically stopped if the requirements are not met.
