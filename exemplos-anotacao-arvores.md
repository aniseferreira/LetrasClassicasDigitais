
# Dicas de anotações em árvore sintática que causam dúvidas nos anotadores com explicações em português #

## Faculdade de Ciências e Letras da UNESP de Araraquara 
**Parte dos Projetos Abertos em Letras Clássicas Digitais, 
<br>Coordª. Anise D'Orange Ferreira, CNPq proc.n.307431/2019-3 e proc. 432895/2018-3** <br>
(_Atualizado até abril de 2022_)
### Sumário

[I.Motivação](#imotivação)

[II.Principais diferenças entre AGDT 1 e AGDT 2  ](#iiprincipais-diferenças-entre-agdt-1-e-agdt-2)

[- APOS, _AP](#apos-ap)

[- PA](#__pa)

[- AuxG, ExD](#auxg-exd)

[- ATV, AtvV](#atv-atvv)

[III. Situações gramaticais específicas](#iii-situações-gramaticais-específicas)

[1. Infinitivo como complemento de adjetivos](#-1-infinitivo-como-complemento-de-adjetivos)

- [Uso de infinitivo complemento de adjetivo no Ragon](#-uso-de-infinitivo-complemento-de-adjetivo-no-ragon-)
<!--- [Exemplo como ADV](#exemplo-como-adv--capaz-para)
- [Exemplo como OBJ](#-exemplo-como-obj--merecer-)
- [Exemplo como ATR](#-exemplo-como-atr-determinação)-->

[2. Verbos de ligação ou Cópula cujo atributo é anotado como PNOM](#-2-verbos-de-liga%C3%A7%C3%A3o-ou-c%C3%B3pula-cujo-atributo-%C3%A9-anotado-como-pnom)

[3. Acusativo de relação dependendo de adjetivo como ADV](#-3-acusativo-de-rela%C3%A7%C3%A3o-dependendo-de-adjetivo-como-adv-)

[4. Artigo e pronome seguido de particípio no mesmo caso](#4-artigo-e-pronome-seguido-de-partic%C3%ADpio-no-mesmo-caso)

[5. Adjetivo verbal -τέος, - τέα, - τέον com sentido impessoal ou pessoal](#5-adjetivo-verbal--%CF%84%CE%AD%CE%BF%CF%82---%CF%84%CE%AD%CE%B1---%CF%84%CE%AD%CE%BF%CE%BD-com-sentido-impessoal-ou-pessoal)

### I.Motivação

Em geral,  anotadores iniciantes do AGDT da área de letras clássicas não estão familiarizados com a anotação em treebank de dependência e percebem conflitos com a intuição sintática que trazem da língua materna. Além disso, estão lidando com textos diversos de gêneros, estilos e épocas diferentes e podem encontrar estruturas sintáticas que podem gerar dúvidas em virtude do sentido empregado ou imaginado pelo autor. Assim, a anotação obriga o anotador a buscar mais informações sobre o texto específico a ser anotado. As convenções no AGDT 1 e 2 não dão conta de toda a complexidade da língua grega que pode surgir nos textos a serem anotados. Por esse motivo, estamos reunindo alguns casos específicos de anotação sobre os quais apareceram dúvidas durante as atividades realizadas em sala de aula e que são encontrados em publicações anteriores, cujas decisões são sustentadas por comentários, gramáticas e dicionários da língua grega e como as convenções das *guidelines* tratam esses casos. 

As ilustrações das ávores são obtidas do Perseus Greek na base Tündra Weblicht- https://weblicht.sfs.uni-tuebingen.de/Tundra/PerseusGreek/. Outras ilustrações são extraídas de gramáticas ou dicionários indicados na figura. Como a maioria das figuras foram feitas para fins didáticos em uso de sala de aula ao longo de alguns anos, não há uniformidade nas dimensões e, por isso, solicitamos compreensão do leitor. 

Pontuemos inicialmente as principais diferenças entre as diretrizes do AGDT 1 e 2. Elas residem na aplicação das etiquetas APOS, PA,ExD,AuxG,ATV e AtvV. 


### II.Principais diferenças entre AGDT 1 e AGDT 2 

#### APOS, AP

* <h4>No AGDT 1 </h4>
No AGDT 1, é a vírgula separando os elementos colocados em aposição que recebe a etiqueta APOS, e cada elemento recebe a etiqueta da função mais o sufixo __AP. O sufixo _AP é usado somente no AGDT 1,  para a aposição. Há também a variante _AP_CO, quando existem apositivos coordenados.

<img src="img/APOS_virgula_SBJ_AP.png">

* <h4>No AGDT 2 </h4>

<img src="img/AGDT2 - OBJ + APOS_CO.png">
A mesma sentença, Tuc. 1.122.4 pode ser vista na convenção do AGDT 1.0 em https://weblicht.sfs.uni-tuebingen.de/Tundra/PerseusGreek/5138.

#### __PA 
* <h4>Só no AGDT 1 </h4>

O sufixo __PA só se encontra nas anotações antigas feitas com AGDT 1, em orações parentéticas, separadas por um sinal gráfico, ou de travessão, ou de parênteses (AuxG). Nem consta como opção das etiquetas atuais do AGDT 1 e 2. A anotação de orações parentéticas é feita no AGDT 2 com ExD dependendo do PRED. 

<img src="img/PRED_PA.png">

### AuxG, ExD

- No AGDT 1, AuxG é a etiqueta das marcas gráficas que separam as orações parentéticas. 
- No AGDT 2, AuxG pode ser usada ainda para aspas em discurso direto.

- No ADGT 1, ExD é a etiqueta aplicada ao vocativo e elementos fora da sintaxe do período, como exclamações. 
- No AGDT 2, ExD é usado para vocativo, exclamações, etc, e também para constituintes sintáticos que não pertencem sintaticamente ao período, como as orações parentéticas.  

### ATV, AtvV 

ATV e AtvV são etiquetas do AGDT 1. São atributos ou predicativos verbais, chamados na gramática normativa em português de predicado verbo-nominal. Concordam com seu sujeito. Distinguem-se do PNOM por serem atributos de um agente mediados por um verbo que não é de ligação. A diferença entre ATV e AtvV está no fato de que o atributo ATV se liga ao agente que é modificado pelo atributo e está presente no período, ficando dependente desse. AtvV é a etiqueta usada para o atributo quando o elemento modificado pelo atributo está oculto e fica dependendo do verbo. 

No AGDT 2, tanto ATV como AtvV são anotados como ADV e dependem sempre do verbo. Compare os exemplos:


- <img src="img/ATV-monos.png" width="75%" height="70%">
- <img src="img/monos-AtvV.png" width="75%" height="70%">
- <img src="img/OBJ+ATV.png" width="90%" height="90%">
- <img src="img/eu_ADV_poieis_participio_AtvV.png" width="90%" height="90%">
          

## III. Situações gramaticais específicas 

<h2> 1. Infinitivo como complemento de adjetivos</h2>

O manual AGDT do treebank recomenda anotar com etiqueta OBJ não só os infinitivos como complementos verbos (orações completivas) como também quando *complementam adjetivos* embora haja alguns exemplos como ADV (192) e ATR (32). Isso porque na gramática do Smyth esse infinitivo teria um uso análogo ao infinitivo que modifica certos verbos que indicam finalidade, adequação, habilidade, facilidade, etc cf. [Smyth Grammar § 2001-2002](http://www.perseus.tufts.edu/hopper/text?doc=Perseus%3Atext%3A1999.04.0007%3Asmythp%3D2002). Assim, temos: 

> *2001 O infinitivo serve para definir o significado de adjetivos, advérbios e substantivos, especialmente aqueles que denotam habilidade, aptidão, capacidade, etc. (e seus opostos), e geralmente aqueles análogos em significado aos verbos que tomam o infinitivo (2000). Aqui o significado de dativo (propósito, destino) é muitas vezes aparente. Cp. 1969.*a. Some of these adjectives take the infinitive by analogy to the related verbs, as πρόθυμος zealous (προθυμοῦμαι), ἐπιστήμων knowing how (ἐπίσταμαι)"*. 
>> *1969. O infinitivo era originalmente um substantivo verbal no caso dativo (em parte possivelmente também no locativo). O uso para expressar propósito (2008) é uma sobrevivência do significado primitivo, do qual todos os outros usos amplamente divergentes foram desenvolvidos de maneira nem sempre clara para nós. Mas o significado **para** (to e for) visto em μανθάνειν ἥκομεν  'viemos aprender' (para aprender) também pode ser discernido em δύναμαι ἰδεῖν, 'Tenho poder para ver', então, 'posso ver'. Cp. 2000, 2006 a. Já em Homero, quando o significado do dativo foi parcialmente obscurecido, o infinitivo foi empregado como nominativo (como sujeito) e acusativo (como objeto). Depois de Homero, o infinitivo passou a ser usado com o artigo neutro, a ideia substantiva ganhando assim definição. O artigo deve ser usado quando o infinitivo está como objeto no genitivo ou dativo, e quando depende de preposições*

Por isso, trazemos os dois modos de anotação já registrados: como ADV (modificador opcional, como princípio geral) e como OBJ (complemento obrigatório, como princípio geral) abaixo. Supõe-se que, como ADV, está presente a ideia de finalidade, que seria adicional; como OBJ, está presente a ideia de que o verbo substituído pelo adjetivo não poderia prescindir do complemento. Achamos a diferença muito sutil e depende do sentido da ação verbal implícita.

* <h3> Uso de infinitivo complemento de adjetivo no Ragon </h3>
<img src="img/infinitivo-determinacao-adjetivos-ragon.jpg" width="600" height="600">

* <h3>Exemplo como ADV (= capaz para)</h3>
<img src="img/adjetivo-dunatos+infinitivo.png" width="840" height="380">

* <h3> Exemplo como OBJ (= merecer ...)</h3> 
<img src="img/adj+inf+OBJ.png" width="840" height="380">

* <h3> Exemplo como ATR (determinação)</h3>
<img src="img/PRED_PA.png">
  
<h2> 2. Verbos de ligação ou Cópula cujo atributo é anotado como PNOM</h2>

A Smyth Grammar contém uma pequena lista de verbos de ligação, ver: 
<img src="img/verbos_ligacao.png" width="800" height="600"> 

**O texto didático da Gildersleeve Grammar traz exemplos e a lista pode ser expandida**, ver: 
[Copula](https://www.perseus.tufts.edu/hopper/text?doc=Perseus:text:1999.04.0074:section=5)

>[*] *64. Verbos copulativos. 
Outros verbos copulativos são: “ἀκούειν”, “διατελεῖν”, "δύνασθαι", “καθίστασθαι” = “γἱγνεσθαι” (muitas vezes em oradores) “κυρεῖν”, calhar, "λαγχάνειν", “μένειν”, permanecer, "πέλειν, πέλεσθαι", "τελέθειν", “τυγχάνειν”, acontecer, “ὑπάρχειν”, ser, "φαίνομαι", aparecer, “Φῦναι”, comp. fuisse, etc.
>>Nos melhores dias da língua, verbos como “καθίστασθαι, τυγχάνειν, ὑπάρχειν” e “φῦναι” não são meros fluxos para o predicado. O uso frequente de “φῦναι” e “τυγχάνειν” surge da divisão grega de toda manifestação nas duas esferas de “φύσις” e “τύχη”. Em “ὑπάρχειν”, que acabou por se descolorir, a ideia de base, de algo a que recorrer, de recurso ou resíduo, não foi totalmente apagada no bom período.

<img src="img/kalew-voz-passiva+PNOM.png" width="800" hdight="400">

**Observação:** Quando um verbo de ligação predicativo depende de outro verbo de ligação teremos dois PNOMs, como na figura abaixo.


<img src="img/PNOM+PNOM.png" width="800" height="400" align="center"> 


* <h3> Alguns verbos podem ou não ser usados como verbos de ligação e, às vezes, se usam na forma da voz ativa quando pedem predicativo PNOM. </h3>
Parece ser o caso do verbo τυγχάνω  e  δοκέω que teriam complemento verbal obrigatório e, por isso, εἰμί recebe etiqueta OBJ. A diferença pode ser sutil, mas as anotações de εἰμί como OBJ e seu complemento PNOM são mais numerosas do que haver dois PNOMs.

**εἶναι é PNOM**

<img src="img/τυγχανω+2PNOMs.png" width="800" height="400"> 

**εἶναι  é OBJ**

<img src="img/τυγχανω+ OBJ+PNOM.png" width="600" height="300"> 

**εἶναι é OBJ**

<img src="img/dokew+OBJ+PNOM.png"> 

**εἶναι é PNOM**

<img src="img/dokew+2PNOMs.png">


* <h3> Outros verbos de ligação pedem predicativo em dois PNOMs quando em sentido passivo  </h3>
Com o verbo **νομίζω** por exemplo, entendido como   _ϳulgando_ ou  _julgado ser_, ou _acreditando ser_ καλὸν εἶναι νομιζόμενόν - "ser" pode ser anotado como OBJ. Já quando se refere a costume e uso, poderá pedir PNOM.

<img src="img/nomizetai-OBJ+PNOM.png">
<img src="img/OBJ+PNOM2.png">


<h2> 3. Acusativo de relação dependendo de adjetivo como ADV </h2>

O acusativo de relação ou de respeito expressa a forma em que se dá a ação, e dependerá do adjetivo ou verbo como um complemento adicional e etiquetado ADV e será anotado como ADV. Pode também estar mediado por uma preposição, i.e., ser "adposicional". 

<img src="img/acusativo_relacao.jpg" width="600" height="500">



<h2>4. Artigo e pronome seguido de particípio no mesmo caso</h2>

* <h3> Em sentenças com particípio articulado sem substantivo:</h3>

o artigo recebe a etiqueta ATR, e o particípio recebe a etiqueta correspondente à função (v. §366 Ragon):

<img src="img/participio-como-substantivo_ou_aquele_que.png" width="650" height="300">

Abaixo:  _O que se coroou percorreu (os tempos) dos deuses_ (Plutarco, _Licurgo_, 26.3)

<img src="img/artigoATR_particípioSBJ_nom.png" width="650" height="250"> 


* <h3> Em sentenças com pronome indefinido com particípio</h3>

O particípio recebe a etiqueta ATR (oração adjetiva) e o pronome indefinido recebe a etiqueta correspondente à função sintática:

Abaixo: _Alguém que seja sensato saiba isso._ (Sófocles, _Ájax_, 416)

<img src="img/pronome-indefinido+participio+nominativo.png" width="600" height="240">

<h2>5. Adjetivo verbal -τέος, - τέα, - τέον com sentido impessoal ou pessoal</h2>

Encontramos na SG a seguinte informação sobre o adjetivo verbal no parágrafo §2149. 

_Adjetivos verbais em -τέος expressam a necessidade. Eles admitem duas construções:_
_1. A construção pessoal (-τέος, -τέα, -τέον), passiva no sentido, e enfatizando o assunto.
_2. A construção impessoal (mais comum) (-τέον, -τέα^, 1052), praticamente ativa no sentido, e enfatizando a ação._

_Ambas as construções são utilizadas com a cópula **εἰμί**, que pode ser omitida. O agente - a pessoa sobre a qual repousa a necessidade - é expresso, se for o caso, pelo dativo (nunca pelo ὑπό e pelo genitivo)._

(...) _§ 2152a a. Como a construção impessoal é virtualmente ativa, e portanto equivalente **a δεῖ com o acusativo e infinitivo** (ativo ou médio), o agente às vezes fica no acusativo, como se dependesse de δεῖ. A cópula é (talvez) sempre omitida quando o agente é expresso pelo acusativo. Assim, τὸν βουλόμενον εὐδαίμονα εἶναι σωφροσύνην καὶ ἀσκητέον (= διωκτέον διώκειν καὶ ἀσκεῖν) é necessário que o homem que deseja ser feliz persiga e pratique a temperança P. G. 507c._

* Na árvore sintática, o verbo εἰμί ganha a etiqueta (rara) de **AuxV** em dependência do adjetivo verbal. Nesses casos, geralmente a oração tem um núcleo verbal expresso como um PRED explícito. Ver exemplo em https://weblicht.sfs.uni-tuebingen.de/Tundra/AncientGreekProse/10311

* Porém, há orações em que o verbo principal não está expresso e o próprio adjetivo verbal representa a ação principal da oração pelo implícito do valor deôntico: deve (-se) X . Exemplo em: https://weblicht.sfs.uni-tuebingen.de/Tundra/AncientGreekProse/22800. Neste caso, o adjetivo verbal assume o lugar do PRED. Mesmo quando há o verbo "ser" presente, cf. https://weblicht.sfs.uni-tuebingen.de/Tundra/AncientGreekProse/13582

- Todas as traduções são feitas automaticamente com a versão gratuita do tradutor - www.DeepL.com/Translator e corrigidas e revistas manualmente. 
