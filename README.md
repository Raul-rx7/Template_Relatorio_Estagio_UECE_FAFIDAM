# Template_Relatorio_Estagio_UECE_FAFIDAM
![template](https://user-images.githubusercontent.com/72898972/117222708-7c9fe580-ade2-11eb-9a59-9951c7818673.png)

Template em LaTeX do relatório de estágio destinado a estudantes da Universidade Estadual do Ceará (UECE).
Projeto para auxiliar os estudantes das disciplinas de Estágio supervisionado de ensino da Universidade Estadual do Ceará.

O presente projeto foi parte de uma das atividades realizadas pelo o autor durante a Monitoria das disciplinas de Estágio de Ensino de Ciências e Física 1. 

# Começo por onde?
Para usar o Tamplate_Relatorio_Estagio_UECE_FAFIDAM siga os seguintes passos: 

1. Clique [aqui](https://github.com/Raul-rx7/Tamplate_Relatorio_Estagio_UECE_FAFIDAM/archive/refs/heads/main.zip) para realizar o download do projeto.
2. Desempacote o arquivo no diretório de sua preferência.
3. Abra a pasta e em seguida o arquivo *template_relatorio_estagio.tex* para dar início a escrita.

# Como compilar? 
Caso você for iniciante e não tenha em sua máquina o programa compilador de texto para gerar o PDF siga os seguintes links:

- **Windows**: basta acessar [http://www.profmat.cefetmg.br/modelos-dissertacao/latex/instalacao-do-latex/] e seguir os passos indicados pelo o autor

- **Linux**: para distros Ubuntu e derivados basta acessar [https://www.edivaldobrito.com.br/editor-latex-texstudio-no-ubuntu/] e seguir os passos indicados pelo o autor

Para iniciantes em LaTeX é aconselhável verificar a apostila desenvolvida pelo Programa Especial de Treinamento do curso de Telecomunicações (PETTELE) da Universidade Federal Fluminense no [link](http://each.uspnet.usp.br/sarajane/wp-content/uploads/2016/10/manual-latex-1.pdf). A apostila é altamente útil para o desenvolvimento do conhecimento da ferramenta LaTeX.

# Observações
- Por se tratar de um projeto compacto, o arquivo *template_relatorio_estagio.tex* contém os elementos pré-textuais (capa, contra-capa, sumário) juntos aos elementos textuais (introdução, fundamentação teórica, metodologia, discusão, conclusão) e pós-textuais (referências bibliográficas, apêndice). **Portanto, todo o texto deve ser escrito no arquivo *template_relatorio_estagio.tex***

- É pertinente que o **estagiário preencha todos os dados do seu estágio** (seu nome, professor, coordenador de estágio, o estágio) tanto na capa, quanto na contra capa e na página de assinatura
- O sumário é preenchido de forma automática

# Dicas
## Inserindo comentários: 
  Os comentários são inseridos utilizando '%' antes, pois dessa maneira não aparecerá no texto do PDF
  
  Exemplo:   ``` 
              % o comentário vem aqui 
             ```


## Inserindo imagens:
  ```
\begin{figure}
	\centering 
	\includegraphics[scale=2.5]{figuras/nome_do_arquivo}
\end{figure} 
  ```
  **Obs.:** É importante que todas as imagens a serem utilizadas no texto, sejam alocadas na pasta *figuras* !

## Inserindo arquivo PDF: Altamente necessário para incluir arquivos no *Apêndice*
```
\includepdf[pages=-]{apendice/PLANO_DE_AULA_1}
```
**Obs.:** É importante que todos os arquivos em PDF a serem utilizados no apendice, devem estar na pasta *apendice*.
## Criando Capítulo:
```
\chapter{Fundamentação Teórica}
\label{cap:fundamentacao-teorica}
```
## Criando seções
### Seção secundária: 
```
\section{Primeira aula}
\label{sec:primeira-aula}
```
### Seção terciária:
```
\subsection{Primeira aula 1.1}
\label{subsec:primeira-aula11}
```
### Seção quaternária:
```
\subsubsection{Primeira aula 1.1.2}
\label{subsubsec:primeira-aula112}
```
## Criando itens:
```
\begin{itemize}

\item Primeiro item
\item Segundo item

\end{itemize}
```
## Criando enumeração:
```
\begin{enumerate}

\item Primeira enumeração
\item Segunda enumeração

\end{enumerate}
```
### Enumeração em algarismo romano:
```
\begin{enumerate}[label=\Roman*.]

\item Primeira enumeração em algarismo romano
\item Segunda enumeração em algarismo romano

\end{enumerate}
```

# Atenção !
O Template_Relatorio_Estagio_UECE_FAFIDAM é fornecido gratuitamente e pode ser redistribuído livremente para fins acadêmicos. O template não se encontra vinculado oficialmente à Universidade Estadual do Ceará (UECE)

# Agradecimentos
Prof. Dr. Robson Guimarães Sanabio, orientador da Monitoria de Estágio de Ensino de Ciências e Física 1.

Profa. Ma. Francisca Daniele Costa de Lima Beserra, Professora de Estágio de ensino de Física 2 e 3 e Coordenadora dos Estágios supervisionados da Faculdade de Filosofia Dom Aureliano Matos (FAFIDAM - UECE).

Eduardo Yohann, designer gráfico responsável pela montagem da logo do projeto. Clique [aqui](https://www.instagram.com/duduyohannphotos/) para ver um pouco de seus trabalhos.
