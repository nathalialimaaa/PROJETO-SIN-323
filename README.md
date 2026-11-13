# PROJETO-SIN-323
# 🌾 Agrocheck - Diagnóstico de Doenças em Milho e Cenoura com IA

O **Agrocheck** é uma solução de Inteligência Artificial e Visão Computacional desenvolvida para auxiliar no diagnóstico rápido e automático da sanidade foliar nas culturas de **Milho** e **Cenoura**.

## 📌 Sobre o Projeto

O objetivo principal é classificar imagens de folhas entre saudáveis e infectadas por patógenos, oferecendo suporte à tomada de decisão no campo e reduzindo perdas agrícolas.

## 🛠️ Tecnologias Utilizadas

- **Linguagem:** Python
- **Deep Learning / Visão Computacional:** TensorFlow e Keras
- **Arquitetura Base:** MobileNetV2 (*Transfer Learning*)
- **Ambiente de Treinamento:** Google Colab (Aceleração por GPU T4)
- **Aplicação Web:** Streamlit

## 🚀 Estrutura da Solução

1. **Pré-processamento e Seleção de Dados:** Filtragem automática das classes de folhas de milho e cenoura a partir do conjunto de dados (*dataset*).
2. **Treinamento da Rede Neural:** Ajuste da arquitetura MobileNetV2 para classificação multiclasse com congelamento das camadas de extração de características.
3. **Exportação do Modelo:** Geração do arquivo compilado `agrocheck_melhor.keras`.
4. **Interface Interativa:** Aplicação web em Streamlit para envio (*upload*) de fotos e exibição do diagnóstico em tempo real.
