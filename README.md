# Reconstrução e Interpretação de ECG

Este projeto foi desenvolvido na disciplina de **Processamento Digital de Sinais** e teve como objetivo reconstruir e analisar digitalmente um sinal de ECG a partir de uma **imagem impressa** com grade e parâmetros de calibração conhecidos (1 mV = 10 mm | 25 mm/s).

---

## Objetivos
- Extrair o traçado do ECG de uma imagem estática.  
- Reconstruir a série temporal em mV e segundos.  
- Processar o sinal com filtros e análise espectral.  
- Detectar picos QRS e calcular parâmetros cardíacos (FC, RR, SDNN, RMSSD).  
- Avaliar a coerência do sinal reconstruído e discutir limitações.  

---

## Metodologia
O processo envolveu as seguintes etapas:
1. **Digitalização e extração do traçado** da imagem.  
2. **Calibração** em amplitude (mV) e tempo (s).  
3. **Processamento do sinal**:  
   - Filtros (atenuação de ruído, suavização por mediana);  
   - Análise espectral (Fourier).  
4. **Detecção de QRS** e cálculo de parâmetros de variabilidade cardíaca.  
5. **Visualização em HTML** reunindo códigos, gráficos e resultados.  

🔗 [Versão interativa em HTML](https://raylam323.github.io/ecg_pds/)

---

## Resultados
- Foi possível reconstruir um traçado coerente, apesar das limitações do material de origem.  
- Os **indicadores cardíacos** calculados foram compatíveis com ritmo sinusal normal em repouso.  
- O processamento suavizou o sinal, reduzindo detalhes morfológicos finos.  
- A abordagem demonstrou o potencial de **digitalização automatizada de ECGs**, ainda que limitada pela resolução e fidelidade da imagem.  

---

## Principais constatações
- A reconstrução mostrou que técnicas simples de processamento digital permitem **recuperar informações relevantes** de sinais impressos.  
- Houve **perda de detalhes** morfológicos devido à qualidade da imagem original e às simplificações do processamento.  
- A metodologia é promissora para aplicações em **preservação, digitalização e análise automatizada** de ECGs antigos ou impressos.  

---

## Melhorias Futuras
- Usar imagens de maior resolução para melhorar a fidelidade.  
- Testar métodos de processamento mais avançados (ex.: wavelets).  
- Expandir a análise para outros parâmetros clínicos além da frequência cardíaca.  

---

## Referências
- Reis, Helder José Lima et al. *ECG: manual prático de eletrocardiograma.* Atheneu, 2013.  
- Diretriz da Sociedade Brasileira de Cardiologia sobre a Análise e Emissão de Laudos Eletrocardiográficos – 2022.  
- Salsekar, Bharti; Wadhwani, A. *Filtering of ECG signal using butterworth filter and its feature extraction.* IJEST, 2012.  

