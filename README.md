# Estrutura em MDF – Tubo de Kundt Digital

Arquivos de recorte em MDF para a estrutura mecânica de suporte do experimento digital do Tubo de Kundt, desenvolvido com instrumentação baseada em Raspberry Pi.

Este repositório contém os arquivos de corte a laser utilizados na construção da estrutura física descrita no Trabalho de Conclusão de Curso:

**"Instrumentação Digital no Tubo de Kundt: Aplicação do Raspberry Pi para a Análise de Fenômenos Acústicos"**  
Universidade Federal de Catalão (UFCAT) – 2026

---

## 📌 Visão Geral do Projeto

A estrutura foi projetada com os seguintes objetivos:

- Sustentar um tubo de acrílico de 1 metro
- Permitir o alinhamento preciso do êmbolo móvel
- Integrar os alto-falantes
- Fixar régua milimetrada para medições experimentais
- Garantir estabilidade mecânica durante a coleta de dados

O projeto prioriza:

- Baixo custo
- Facilidade de replicação
- Fabricação por corte a laser
- Montagem simples e modular

---

## 🛠 Materiais Utilizados

- Chapas de MDF (espessura recomendada: 3 mm)
- Tubo de acrílico (1 metro)
- Haste ou tubo de alumínio para êmbolo
- Material de vedação (EVA ou similar)
- Cola instantânea 

---

## 📐 Fabricação

Os arquivos foram desenvolvidos para **corte a laser**.

Antes da fabricação, recomenda-se verificar:

- Compatibilidade da espessura do MDF com o encaixe projetado
- Compensação de kerf (largura do corte do laser)
- Configurações específicas do equipamento de corte

Todas as dimensões estão em milímetros.

---

## 📐 Formatos Disponíveis

Os arquivos de recorte estão disponibilizados nos seguintes formatos:

- **.CDR** (arquivo original do CorelDRAW)
- **.SVG** (Scalable Vector Graphics)
- **.DXF** (Drawing Exchange Format)

Os formatos **SVG** e **DXF** foram incluídos para garantir maior compatibilidade com diferentes máquinas de corte a laser e permitir a edição utilizando softwares livres.

O formato **DXF**, em especial, é amplamente utilizado em aplicações de corte a laser, CNC e fabricação digital, sendo compatível com diversos softwares gratuitos, tais como:

- **LibreCAD** (recomendado)
- **Inkscape**
- **FreeCAD**

A disponibilização nesses formatos tem como objetivo promover a replicabilidade do projeto, permitindo que a estrutura possa ser modificada e adaptada por estudantes, professores e pesquisadores sem a necessidade de softwares proprietários.

---

## 🧪 Integração com o Sistema Experimental

Esta estrutura faz parte de um sistema completo de instrumentação digital que inclui:

- Raspberry Pi 5
- Conversor analógico-digital ADS1015
- Microfone pré-amplificado MAX4466
- Sensor ambiental BME280
- Display OLED SSD1306
- Amplificador de áudio classe D

Para detalhes completos sobre a implementação eletrônica e de software, consulte o trabalho acadêmico correspondente.

---

## 📂 Estrutura do Repositório

```
kundt-mdf-structure/
│
├── design-files/      # Arquivos de corte (CDR, DXF e SVG)
├── README.md
└── LICENSE
```


---

## 📜 Licença

Este projeto é disponibilizado sob a licença MIT, permitindo uso, modificação e redistribuição mediante atribuição adequada ao autor.

---

## 👨‍🔬 Autor

Michel Douglas do Couto  
Curso de Bacharelado em Física – Universidade Federal de Catalão (UFCAT)  
2026

---

## 🔬 Objetivo Acadêmico

Este repositório tem como finalidade promover a replicabilidade experimental e contribuir com iniciativas de instrumentação científica de baixo custo no ensino de Física.
