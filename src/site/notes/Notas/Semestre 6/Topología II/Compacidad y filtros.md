---
{"dg-publish":true,"permalink":"/Notas/Semestre 6/Topología II/Compacidad y filtros/"}
---

## Recordatorio
> ${}x{}$ es un [[Conceptos/Semestre 6/Punto de acumulación de un filtro\|Punto de acumulación de un filtro]] ${}\mathcal{F}{}$ si y solo si ${}x \in \bigcap_{F \in \mathcal{F}}F{}$.

> [!theorem|*] Compacidad con filtros
> Sea ${}(X,\tau){}$ un [[Conceptos/Semestre 6/Espacio topológico\|Espacio topológico]]. Son equivalentes:
> 1. ${}X{}$ es compacto.
> 2. Todo [[Conceptos/Semestre 6/Filtro\|filtro]] ${}\mathcal{F}{}$ en ${}X{}$ tiene un [[Conceptos/Semestre 6/Punto de acumulación de un filtro\|punto de acumulación]].

> [!corollary|*]
> ${}X{}$ es compacto si y solo si todo ultrafiltro en ${}X{}$ converge.

## Ejercicio 
${}X{}$ es compacto si y solo si toda ultrared en ${}X{}$ converge.

# Teorema de [[Conceptos/Semestre 6/Teorema de Tychonoff\|Tychonoff]]

> [!theorem|*] De [[Conceptos/Semestre 6/Teorema de Tychonoff\|Tychonoff]]
> Sea ${}\left\{(X_{\alpha},\tau_{\alpha}) \right\}_{\alpha \in \mathcal{A}}{}$ una familia de espacios topológicos. Entonces 
> $${}  X:= \prod_{\alpha  \in  \mathcal{A} }^{} X_{\alpha }  {}$$
> es compacto si y solo si cada ${}X_{\alpha}{}$ es compacto.
> 

# Redes y filtros 

> [!definition|*]
> Sea ${}(x_{\lambda})_{\lambda \in \mathcal{A}}{}$ una red en un conjunto ${}X{}$. Sea ${}\mathcal{C}= \left\{T_{\lambda}: \lambda \in \mathcal{A} \right\}{}$, donde ${}T_{\lambda}= \left\{x_{\mu}: \mu\geq \lambda \right\}{}$. Entonces ${}\mathcal{C}{}$ es base para un [[Conceptos/Semestre 6/Filtro\|filtro]] en ${}X{}$ llamado el [[Conceptos/Semestre 6/Filtro\|filtro]] generado por la [[Conceptos/Semestre 6/Red\|Red]] ${}(x_{\lambda})_{\lambda \in \mathcal{A}}{}$.

> [!theorem|*]
> Sea ${}(x_{\lambda})_{\lambda \in \mathcal{A}}{}$ una red en un [[Conceptos/Semestre 6/Espacio topológico\|espacio topológico]] ${}X{}$ y sea ${}\mathcal{G}{}$ el [[Conceptos/Semestre 6/Filtro generado por una red\|filtro generado por la red]]. Entonces ${}(x_{\lambda})_{\lambda \in \mathcal{A}}{}$ converge a ${}x{}$ si y solo si ${}\mathcal{G}{}$ converge a ${}x{}$.
> 

> [!definition|*] Red basada en un [[Conceptos/Semestre 6/Filtro\|filtro]]
> Sea ${}\mathcal{F}{}$ un [[Conceptos/Semestre 6/Filtro\|filtro]] en un conjunto ${}X{}$. Sea ${}\mathcal{A}_{\mathcal{F}}= \left\{(x,F): x \in F \in \mathcal{F} \right\}{}$. Definimos una relación ${}\leq{}$ en ${}\mathcal{A}{}$ por:
> $${}  (x,F) \leq (y,G) \iff G \subseteq  F .{}$$
> Sea ${}q:\mathcal{A}_{\mathcal{F}}\to X{}$ dada por ${}q(x,F)=x{}$. Entonces ${}(q(x,F))_{(x,F) \in\mathcal{A}_{\mathcal{F}}}{}$ es una red en ${}X{}$ llamada [[Conceptos/Semestre 6/Red basada en un filtro\| red basada en el filtro]] ${}\mathcal{F}{}$.
> 

> [!theorem|*]
> Sea ${}\mathcal{F}{}$ un [[Conceptos/Semestre 6/Filtro\|filtro]] en un [[Conceptos/Semestre 6/Espacio topológico\|Espacio topológico]] ${}X{}$ y ${}x_{0} \in X{}$. Entonces un [[Conceptos/Semestre 6/Filtro\|filtro]] ${}\mathcal{F}{}$ converge a ${}x_{0}{}$ si y solo si la [[Conceptos/Semestre 6/Red basada en un filtro\| red basada en]] ${}\mathcal{F}{}$ converge a ${}x_{0}{}$.
> 
