# teste1
\documentclass[addpoints]{exam}
\usepackage[brazilian]{babel}
\usepackage[utf8]{inputenc}
\usepackage[export]{adjustbox}
\usepackage{amssymb,amsthm,amstext,latexsym,amsmath,fullpage,graphicx}
\usepackage{enumitem}

\pointpoints{ponto}{pontos}

\newcommand{\RR}{\mathbb{R}}
\begin{document}

\begin{center}
\fbox{\fbox{\parbox{5.5in}{\centering
C\'alculo IIB 2020/1 -- ATIVIDADE EM GRUPOS 2 -- GRUPOS D1  e L1}}}
\end{center}

\vspace{5mm}

%\makebox[\textwidth]{Nome:\enspace\hrulefill}
%
%\vspace{5mm}
%
\begin{itemize}
\item Por favor escreva as respostas de forma clara e leg\'ivel.
\item Em cada problema \'e necessario fornecer justificativas
  em cada passo para obter os pontos. Respostas sem justificativas N\~AO ser\~ao consideradas.

\end{itemize}
\vspace{3mm}

\begin{questions}
%   \question
% A altura h de ondas em mar aberto depende da velocidade do vento $v$ e do tempo $t$ durante o qual o vento se manteve naquela
% intensidade. Os valores da fun\c{c}\~ao $h=f(v, t)$, dados em metros, s\~ao apresentados na tabela a seguir:

% \begin{figure}[hht]
%   \centering
%   \includegraphics[width=7cm]{tabela1AG1.png}
  
% \end{figure}
% \begin{itemize}
%   \item[(a)] Qual o significado das derivadas parciais $\frac{\partial h}{ \partial t}$ e $\frac{\partial h}{\partial v}$ ?
%   \item[(b)]  Estime os valores de $f_v(80, 15)$ e $f_t(80, 15)$. Quais são as interpretações práticas desses valores?
%   \item[(c)] Qual parece ser o valor do seguinte limite? \newline
%           $$\lim_{t \rightarrow \infty}\frac{\partial h} {\partial t}$$
% \end{itemize}

% \vspace{\stretch{1}}


% \question

% Determine os sinais das derivadas parciais da função f cujo gráfico está mostrado. 

% \begin{figure}[hht]
%   \centering
%   \includegraphics[width=8cm]{questao2.jpg}
%   %\caption{}\label{}
% \end{figure}


% \begin{itemize}
%   \item[(I)] (a)$f_x(1,2)$   \hspace{4cm}(b)$f_y(1,2)$
%   \item[(II)] (a)$f_x(-1,2)$ \hspace{3,7cm}(b)$f_y(-1,2)$
% \end{itemize}

% \vspace{\stretch{1}}

% \newpage

\question

Um mapa de contorno de uma função f é apresentado. 

\begin{figure}[hht]
  \centering
  \includegraphics[width=10cm]{questao3.png}
  %\caption{}\label{}
\end{figure}

\begin{itemize}
  \item[(a)] Estimar o valor de $\nabla f(2, 1)$. Esboce o vetor no mapa de contorno.\medskip
   
  Resposta: Através da observação do ponto (2,1), podemos notar que a curva de nível varia de aproximadamente 10 a 14 em relação ao vetor (1,0) partindo do ponto. De mesma forma, podemos notar que a curva de nível varia de aproximadante 10 para 8 em relação ao vetor (0,1) partindo do ponto. Podemos então estimar que $\nabla f(2,1) = (4,-2.1)$\medskip%
  \item[(b)] Estimar o valor de $\nabla f(-1, 3)$. Esboce o vetor no mapa de contorno.\medskip
  
  Resposta: Através da observação do ponto (-1,3), podemos notar que a curva de nível varia de aproximadamente -2 a 0.3 em relação ao vetor (1,0) partindo do ponto. De mesma forma, podemos notar que a curva de nível varia de aproximadante -2 para -4 em relação ao vetor (0,1) partindo do ponto. Podemos então estimar que$\nabla f(-1,3) =  (1.7,-2)$\medskip%
  
  \item[(c)] Estime a equação da retas tangente à curva de nível que passa pelo ponto $(2,1)$. \medskip
  
  Resposta: Observando o gráfico, temos que a curva de nível que passa pelo ponto (2,1) é aproximadamente 10. Temos que a reta tangente pode ser descrita como, sendo $k$ a curva de nível no ponto $(x_0,y_0)$ do gráfico:
            %$$k = \frac{\partial f}{\partial x}(x_0,y_0)(x -x_0) +\frac{\partial f}{\partial y}(x_0,y_0)(y-y_0) $$
    
Temos que as coordenadas do vetor gradiente no ponto (2,1) são $\frac{\partial f}{\partial x}(2,1)$ e $\frac{\partial f}{\partial y}(2,1)$,respectivamente. Substituindo os valores que estimamos em (a) e (b) obtemos o seguinte:    
                       %10 = 4(x-2) -(2.1)(y-1)\medskip%
  
  \item[(d)] Estime a equação do plano tangente ao gráfico da função no ponto aproximado $(-1,3,-2)$.
  
  Resposta: Podemos descrever a equação do plano tangente do seguinte modo. Para um ponto $(x_0,y_0) \in Dom(f)$, o qual é diferenciável, temos o seguinte:
    $$z = f(x_0,y_0) + \frac{\partial f}{\partial x}(x_0,y_0)(x-x_0) + \frac{\partial f}{\partial y}(x_0,y_0)(y-y_0)$$ 
   Substituindo os valores obtemos o seguinte:
                    $$ z = -2 +(1.7)(x+1) -2(y -3)$$
\end{itemize}

%\medskip
\vspace{1cm}

\question

Considere a superfície $z=x^2+xy+3y^3+1$.


\begin{itemize}
  \item[(a)] Utilize o Geogebra para traçar o gráfico da superfície, do
plano tangente e da reta normal no ponto $(1, 1, 6)$ na mesma tela. 
 \item[(b)]  Dê zoom na construção anterior até que a superfície e o plano tangente se tornem indistinguíveis. Use o Geogebra para estimar o valor de $A$ no ponto da superfície $(0.9,1.1,A)$.
 \item[(c)] Esta superfície pode ser considerada como sendo a superfície de nível de alguma função $F:\mathbb{R}^3 \to
 \mathbb{R}$. Indique o nível e a tal função $F$.\medskip
 
 Respostas: \newline 
 
 Podemos tomar um termo independente da função, isolarmos as variáveis e supor que esse termo é o nível da superfície que almejamos. A seguir, tomamos os casos onde isolamos o valor -1, 0 e 1, respectivamente.
 
 Superfície de nível -1 da função $f(x,y,z) = x^2 +xy + 3y^3 -z$ \newline
 
 Superfície de nível 0 da função $f(x,y,z)= x^2 +xy +3y^3 -z +1$ \newline
 
 Superfície de nível 1 da função $f(x,y,z) = z -x^2 -xy -3y^3$\medskip
  \item[(d)] Faça o item $(a)$ com outra superfície de nível da função $F$ especificada no item anterior.
\end{itemize}

Observação: vocês podem enviar o print da tela do Geogebra ou o link do applet.

% \question
% Use a tabela de valores de $f(x, y)$ para estimar os valores de
% $f_x(3, 2)$, $f_x(3.2 ,2)$ e $f_{xy}(3, 2)$.

% \begin{figure}[hht]
%   \centering
%   \includegraphics[width=8cm]{questao4.jpg}
%   %\caption{}\label{}
% \end{figure}

% \medskip

\newpage

\question

Um mapa de contorno de uma função f é apresentado.

\begin{figure}[hhtp]%esse objeto faz parte do comando%
    \centering
    \includegraphics[width=6cm]{questão3ampliada.png}
\end{figure}
\begin{itemize}
  \item[(a)]Esboce o vetor gradiente $\nabla f(4,6)$ para a função $f$ cujas curvas de nível são mostradas. Explique como você escolheu a direção e sentido e o comprimento desse vetor..\medskip
   
  
  \item[(b)] Estime o valor de $\nabla f(4, 6)$.\medskip
  
  Resposta: Através da observação do ponto (4,6), podemos notar que a curva de nível varia de aproximadamente -2 para -1 em relação ao vetor (1,0) partindo do ponto. De mesma forma, podemos notar que a curva de nível varia de aproximadamente -2 para -4
 em relação ao vetor (0,1) partindo do ponto. Podemos então estimar que$\nabla f(4,6) =  (1,-2)$\medskip%
  
  \item[(c)] Estime a equação da retas tangente à curva de nível que passa pelo ponto $(4,6)$. \medskip
  
  Resposta: Observando o gráfico, temos que a curva de nível que passa pelo ponto (4,6) é aproximadamente -2. Temos que a reta tangente pode ser descrita como, sendo $k$ a curva de nível no ponto $(x_0,y_0)$ do gráfico:
            %$$k = \frac{\partial f}{\partial x}(x_0,y_0)(x -x_0) +\frac{\partial f}{\partial y}(x_0,y_0)(y-y_0) $$
    
    Temos que as coordenadas do vetor gradiente no ponto (4,6) são $\frac{\partial f}{\partial x}(4,6)$ e $\frac{\partial f}{\partial y}(4,6)$,respectivamente. Substituindo os valores que estimamos em  (b) obtemos o seguinte:    
                       %-2 = 1(x-4) -2(y-6)\medskip%
  
  \item[(d)] Estime a equação do plano tangente ao gráfico da função no ponto aproximado $(4,6,-2)$.
  
  Resposta: Podemos descrever a equação do plano tangente do seguinte modo. Para um ponto $(x_0,y_0) \in Dom(f)$, o qual é diferenciável, temos o seguinte:
    $$z = f(x_0,y_0) + \frac{\partial f}{\partial x}(x_0,y_0)(x-x_0) + \frac{\partial f}{\partial y}(x_0,y_0)(y-y_0)$$ 
   Substituindo os valores obtemos o seguinte:
                     $$ z = -2 +1(x-4) -2(y -6)$$
\end{itemize}
 
 \medskip

\question

Um mapa de contorno de uma função f é dado.
\begin{figure}[hhtp]%esse objeto faz parte do comando%
    \centering
    \includegraphics[width=12cm]{questao4.png}
\end{figure}

\begin{itemize}
  \item[(a)]Esboce o vetor gradiente $\nabla f(0,-2)$ para a função $f$ cujas curvas de nível são mostradas. Explique como você escolheu a direção e sentido e o comprimento desse vetor..\medskip
   
  
  \item[(b)] Estime o valor de $\nabla f(0, -2)$.\medskip
  
  Resposta: Através da observação do ponto (0,-2), podemos notar que a curva de nível é próxima a -8 em relação ao vetor (1,0) partindo do ponto. De mesma forma, podemos notar que a curva de nível varia de aproximadante -8 para -2 em relação ao vetor (0,1) partindo do ponto. Podemos então estimar que$\nabla f(0,-2) =  (-0.5,6)$\medskip%
  
  \item[(c)] Estime a equação da retas tangente à curva de nível que passa pelo ponto $(0,-2)$. \medskip
  
  Resposta: Observando o gráfico, temos que a curva de nível que passa pelo ponto (0,-2) é aproximadamente -8. Temos que a reta tangente pode ser descrita como, sendo $k$ a curva de nível no ponto $(x_0,y_0)$ do gráfico:
            $$k = \frac{\partial f}{\partial x}(x_0,y_0)(x -x_0) +\frac{\partial f}{\partial y}(x_0,y_0)(y-y_0) $$
    
    Temos que as coordenadas do vetor gradiente no ponto (2,1) são $\frac{\partial f}{\partial x}(0,-2)$ e $\frac{\partial f}{\partial y}(0,-2)$,respectivamente. Substituindo os valores que estimamos em  (b) obtemos o seguinte:    \\
                       $-8 = -0.5(x-0) -6(y+2)$\medskip%
  
  \item[(d)] Estime a equação do plano tangente ao gráfico da função no ponto aproximado $(0,-2,-8)$.
  
  Resposta: Podemos descrever a equação do plano tangente do seguinte modo. Para um ponto $(x_0,y_0) \in Dom(f)$, o qual é diferenciável, temos o seguinte:
    $$z = f(x_0,y_0) + \frac{\partial f}{\partial x}(x_0,y_0)(x-x_0) + \frac{\partial f}{\partial y}(x_0,y_0)(y-y_0)$$ 
   Substituindo os valores obtemos o seguinte:
                      $$ z = -8 -0.5(x-0) -6(y+2)$$
\end{itemize}

\medskip

\question
Um mapa de contorno de uma função f é dado acima.



\begin{figure} %esse objeto faz parte do comando%
    \centering
    \includegraphics[width=10cm]{questao5.png}
\end{figure}


\begin{itemize}
  \item[(a)]Esboce o vetor gradiente $\nabla f(-1,3)$ para a função $f$ cujas curvas de nível são mostradas. Explique como você escolheu a direção e sentido e o comprimento desse vetor..\medskip
  
  Resposta: Através da observação do ponto (-1,3), podemos notar que a curva de nível varia de aproximadamente 1 para 0.5 em relação ao vetor (1,0) partindo do ponto. De mesma forma, podemos notar que a curva de nível varia de aproximadamente 1 para 0 em relação ao vetor (0,1) partindo do ponto. Podemos então estimar que$\nabla f(1,3) =  (0.5,-1.5)$\medskip
   
  
  \item[(b)] Estime o valor de $\nabla f(1,3)$.\medskip
  
  Resposta: Observe que as curvas de nível estão ""refletidas" em relação ao eixo y. Podemos tomar o vetor da letra a, pegando seu simétrico em relação ao eixo y, e então estimar que$\nabla f(1,3) =  (-0.5,-1.5)$\medskip%
  
  \item[(c)] Estime a equação da retas tangente à curva de nível que passa pelo ponto $(1,3)$. \medskip
  
  Resposta: Observando o gráfico, temos que a curva de nível que passa pelo ponto (1,3) é aproximadamente 1. Temos que a reta tangente pode ser descrita como, sendo $k$ a curva de nível no ponto $(x_0,y_0)$ do gráfico:
            %$$k = \frac{\partial f}{\partial x}(x_0,y_0)(x -x_0) +\frac{\partial f}{\partial y}(x_0,y_0)(y-y_0) $$
    
    Temos que as coordenadas do vetor gradiente no ponto (1,3) são $\frac{\partial f}{\partial x}(1,3)$ e $\frac{\partial f}{\partial y}(1,3)$,respectivamente. Substituindo os valores que estimamos em  (b) obtemos o seguinte:  \\  
                       $1 = -0.5(x-1) -1.5(y-3)$ \medskip%
  
  \item[(d)] Estime a equação do plano tangente ao gráfico da função no ponto aproximado $(1,3,1)$.
  
  Resposta: Podemos descrever a equação do plano tangente do seguinte modo. Para um ponto $(x_0,y_0) \in Dom(f)$, o qual é diferenciável, temos o seguinte:
    $$z = f(x_0,y_0) + \frac{\partial f}{\partial x}(x_0,y_0)(x-x_0) + \frac{\partial f}{\partial y}(x_0,y_0)(y-y_0)$$ 
   Substituindo os valores obtemos o seguinte:
                      $$ z = 1 -0.5(x-1) -1.5(y+3)$$
\end{itemize}



\end{questions}
\end{document}

