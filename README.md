# Computer Vision - Object Detection and Classification with OpenCV

Projeto acadêmico de Visão Computacional desenvolvido em Python utilizando OpenCV para detectar, segmentar e classificar objetos em imagens com base em características visuais.

---

## Contexto Acadêmico

Este projeto foi desenvolvido para fins acadêmicos durante o curso de Inteligência Artificial Aplicada à Indústria, realizado no SENAI.

A atividade foi proposta na Unidade Curricular (UC) de Visão Computacional, com o objetivo de aplicar conceitos introdutórios de processamento de imagens, detecção de objetos e classificação baseada em características visuais utilizando OpenCV.

Embora o projeto utilize técnicas simples e não represente uma solução industrial completa, ele foi fundamental para compreender a lógica de construção de pipelines de Visão Computacional e sua relação com aplicações reais da indústria e da Inteligência Artificial.

---

## Objetivo

O objetivo deste projeto é desenvolver um pipeline básico de Visão Computacional capaz de:

- Carregar imagens
- Realizar pré-processamento
- Segmentar objetos
- Detectar contornos
- Extrair características
- Classificar objetos automaticamente

---

## Tecnologias Utilizadas

- Python 3
- OpenCV
- NumPy
- Matplotlib
- Pandas
- Jupyter Notebook

---

## Estrutura do Projeto

```plaintext
computer-vision-opencv-object-detection/
│
├── imagens/
│   └── objetos.jpg
│
├── atividade-visao.ipynb
│
├── atividade-visao.pdf
│
└── README.md
```

---

## Pipeline de Visão Computacional

O projeto segue as seguintes etapas:

1. Carregamento da imagem
2. Conversão para escala de cinza
3. Aplicação de Gaussian Blur
4. Segmentação com Threshold
5. Detecção de contornos
6. Extração de características
7. Classificação baseada em regras
8. Visualização dos resultados

---

## Funcionalidades

- Detecção automática de objetos
- Bounding boxes nos objetos detectados
- Classificação por tamanho:
  - Pequeno
  - Médio
  - Grande
- Geração de tabela com características dos objetos

---

## Características Extraídas

Para cada objeto detectado foram calculadas:

- Área
- Perímetro
- Largura
- Altura

---

## Relação com CNNs

O projeto utiliza técnicas clássicas de processamento de imagens e classificação baseada em regras.

Em aplicações mais avançadas, Redes Neurais Convolucionais (CNNs) podem automatizar a extração de características e melhorar significativamente a robustez do sistema.

---

## Resultados

O sistema foi capaz de:

- Detectar múltiplos objetos na imagem
- Segmentar regiões de interesse
- Classificar objetos automaticamente
- Exibir resultados visualmente

---

## Aprendizados

Este projeto permitiu aprofundar conhecimentos em:

- Visão Computacional
- OpenCV
- Processamento de Imagens
- Segmentação
- Detecção de Objetos
- Extração de Características
- Classificação baseada em regras

---

## Limitações

O projeto apresentou algumas limitações relacionadas à iluminação, sombras e proximidade entre os objetos.

Além disso, objetos com brilho elevado podem gerar reflexos que interferem na segmentação da imagem.

---

## Conclusão

O projeto demonstrou a construção de um pipeline simples de Visão Computacional utilizando OpenCV para detectar, analisar e classificar objetos com base em características visuais.

Mesmo sendo uma solução introdutória e acadêmica, o projeto permitiu compreender etapas fundamentais utilizadas em sistemas reais de automação industrial, inspeção visual e Inteligência Artificial aplicada à indústria.

---

## Autor

Matheus Pessoa Telles

- GitHub: github.com/matheuspessoa14
- LinkedIn: linkedin.com/in/matheuspessoa1816