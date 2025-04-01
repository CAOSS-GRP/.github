# Pacotes Composicionais

## CANA
> ▶️ Biblioteca de análise e modelagem espectral.

### <u>Estado da arte</u>
- [x] Manipulacao de espectros
- [ ] Análise parametrica
	- [x] Classificacao Taxonomia Bus-Demeo
	- [x] Calculo de inclinacao espectral
	- [ ] Caracterizacao de bandas de absorcao (areas, profundidades e largura meia altura)
		- [ ] Gaussianas
		- [x] Polinomiais
		- [x] Spline
- [ ] Modelagem composicional
	- [ ] Teorias de reflectanca
		- [ ] Hapke simplificado
		- [ ] Hapke elaborado
		- [ ] Mie
		- [x] Shkuratov
	- [ ] Tipos de mistura
		- [x] Intima
		- [ ] Geograficas
		- [ ] Camadas
	- [ ] Teoria de meio efetivo
		- [ ] Inclusoes (Maxuell-Garnett)
		- [ ] Bruggeman

## SDOC
> ▶️ Banco de dados de constantes oticas e reflectancia absolutas

### <u>Estado da arte</u>
- [ ] Banco de dados de Reflectancia
	- [ ] Organizacao do Relab
	- [ ] Classificacao de amostras em grupos e subgrupos composicionais
- [ ] Banco de dados de Constantes Oticas
	- [ ] Coleta de constantes na literatura e base de dados publicas (e.g. sshade)
	- [ ] Classificacao das constantes por grupos e subgrupos composicionais (gelos, silicatos, complexos organicos, misturas, etc)
	- [ ] Algoritmo de conversao de reflectancias em constantes oticas
- [ ] Estruturacao do banco de dados relacional no servidor (Postgres)
- [ ] Ferramentas de acesso e manipulacao de dados

## CATUABA
> ▶️ Metodos de regressao e ajuste 

### <u>Estado da arte</u>
- [ ] Análise Bayesiana (Nested Sampling)
	- [ ] Definicão de priors e likelihood 
		- [x] Misturas
		- [ ] Camadas 
		- [ ] Teorias de modelos efetivos
	- [x] Comparacao de modelos
	- [ ] Ferramentas de visualizacao
- [ ] Definicao de condicoes iniciais
	- [ ] Wavelets
	- [ ] Machine learning 
