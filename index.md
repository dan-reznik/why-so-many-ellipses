--- 
title: "Loci of 3-periodics in the Elliptic Billiard: Why so many ellipses?"
author: Ronaldo Garcia, Dan Reznik, and Jair Koiller
date: January, 2021
output:
  bookdown::html_document2:
      theme: cosmo
      highlight: kate
      css: style.css
      toc_depth: 1
      toc: true
      toc_float:
        toc_collapsed: true
        smooth_scroll: yes
      fig_caption: yes
      keep_md: yes
      number_sections: no
link-citations: yes
bibliography: [references.bib]
---

<!-- "default", "cerulean", "journal", "flatly", "darkly", "readable", "spacelab", "united", "cosmo", "lumen", "paper", "sandstone", "simplex", "yeti" -->



This page contains information supplementary to [@garcia2020-ellipses]. We consider Poncelet 3-periodic families interscribed in a pair of ellipses $\mathcal{E}$ and $\mathcal{E}_c$ with semiaxes $a,b$  and $a_c,b_c$, respectively. The Cayley condition for the pair to admit a Poncelet 3-periodic family is [@georgiev2012-poncelet]:

$$\frac{a_c}a+\frac{b_c}b=1$$

Below we report on triangle centers on [@etc] whose loci over Poncelet 3-periodics is an ellipse. These are typically first detected numerically and then proven rigorously, e.g., [@olga14],[@sergei2014-circumcenter-of-mass],[@sergei2016-com],[@garcia2019-incenter],[@fierobe2019].

Here we focus on first 200 triangle centers on [@etc]. We consider 3-periodic families in the confocal (elliptic billiard) and homothetic pair. Appendix A tabulates fit errors for loci in the confocal family, which should be negligible when a given locus is an ellipse.

The family of 3-Periodics in some classic ellipse pairs can be viewed [here](https://youtu.be/8hkeksAsx0E). All loci herein can be visualized with our [interactive app](https://dan-reznik.github.io/ellipse-mounted-loci-p5js/); illustrations and documentation are available on this [webpage](https://dan-reznik.github.io/ellipse-mounted-triangles/).

# I. Confocal Family: Semi-axes of elliptic loci

## Preliminaries 

The following explicit expressions were given for the semi-axes $a_c,b_c$ of the $N=3$ confocal caustic [@garcia2019-incenter]:

$$a_c=\frac{a\left(\delta-a^{2}\right)}{c^2},\;\;\;b_c=\frac{b\left(a^{2}-\delta\right)}{c^2}$$
with $\delta=\sqrt{a^4-a^2b^2+b^4}$ and $c^2=a^2-b^2$.

Below we provide explicit expressions for the semi-axes $a_i,b_i$ of loci, i.e., let the locus of center $X_i$ be described as:

$$\frac{x^2}{a_{i}^2}+\frac{y^2}{b_{i}^2}=1$$

A gallery of loci for all of $X_1$ thru $X_{100}$ appears [here](https://dan-reznik.github.io/billiard-loci/loci.html).

### X(1) and excenters, [see it](https://dan-reznik.github.io/ellipse-mounted-loci-p5js/?sc=11.470&xn1=1&lc1=vtx&lc2=trilins&tr1=excentral&rot=90)
 
$$a_1=\frac{\delta-b^{2}}a,\;\;\;b_1=\frac{a^{2}-\delta}b$$

The locus of the excenters is an ellipse with axes [@garcia2019-incenter]:
 
$$a_e=\frac{b^{2}+\delta}a,\;\;\; 
 b_e=\frac{a^{2}+\delta}b$$
 
Notice it is similar to the $X_1$ locus, i.e., $a_1/b_1=b_e/a_e$. 

**Note:** The ellipticity of $X_1$ for confocals was proven in [@olga14] and [@garcia2019-incenter].

### X(2) (similar to billiard), [see it](https://dan-reznik.github.io/ellipse-mounted-loci-p5js/?xn1=2)

$$\left(a_2,b_2\right)=k_2\left(a,b\right),\;\textrm{where}\; k_2=\frac{2\delta -a^{2}-b^{2}}{3c^2}$$

**Note:** The ellipticity of $X_2$ for any Poncelet family was proven in [@sergei2016-com], [@garcia2019-incenter]. 

### X(3) (similar to rotated caustic), [see it](https://dan-reznik.github.io/ellipse-mounted-loci-p5js/?xn1=3)
 
$$
 a_3=\frac{a^{2}-\delta}{2a},\;\;\;
 b_3=\frac{\delta-b^{2}}{2b}
$$

Additionally, when $a/b= \frac{\sqrt{2\sqrt{33}+2}}{2} \;{\simeq}\;1.836$, $b_3=b$, i.e., the top and bottom vertices of the locus of $X_3$ coincide with the billiard's.

**Note:** The ellipticity of $X_3$ for confocals was proven in [@garcia2019-incenter] and [@fierobe2019]. In [@sergei2014-circumcenter-of-mass], one consideres the ``circumcenter-of-mass'' which generalizes this result for any $N{\geq}3$ Poncelet family.

### X(4) (similar to rotated billiard), [see it](https://dan-reznik.github.io/ellipse-mounted-loci-p5js/?xn1=4)

$$
\left(a_4,b_4\right)=\left(\frac{k_4}a,\frac{k_4}b\right),\;  k_4=\frac{  (a^{2}+b^{2})\delta-2\,a^{2}b^{2} }{c^2}
$$

Additionally:

- When
$a/b=a_4=\sqrt{2\,\sqrt {2}-1}\;{\simeq}\;1.352$, $b_4=b$, i.e., the top and bottom vertices of the locus of $X_4$ coincide with the billiard's.
- Let $a_4^*$ be the positive root of
${x}^{6}+{x}^{4}-4\,{x}^{3}-{x}^{2}-1=0$, i.e.,
$a_4^{*}={\simeq}\;1.51$. When $a/b=a_4^{*}$, $a_4=b$ and $b_4=a$, i.e., the locus of $X_4$ is identical to a rotated copy of billiard.

### X(5), [see it](https://dan-reznik.github.io/ellipse-mounted-loci-p5js/?xn1=5)

$$
  a_5=\frac{- w'_5(a,b)+ w''_5(a,b) \delta}{ w_5(a,b)},\;\;\;b_5=\frac{ w'_5(b,a)-{w''_5(b,a) \delta}}{w_5(b,a)}
$$
 
$$
 w'_5(u,v)=u^2(u^2+3v^2),\;\;\;w''_5(u,v)=3u^2+ v^2,\;\;\;w_5(u,v)=4u(u^2-v^2).
$$

### X(7) (similar to billiard), [see it](https://dan-reznik.github.io/ellipse-mounted-loci-p5js/?xn1=7)
    
$$
\left(a_7,b_7\right)=k_7\left(a,b\right),\;\;  k_7=\frac{2\delta - a^{2}-b^{2}}{c^2}
$$

### X(8), [see it](https://dan-reznik.github.io/ellipse-mounted-loci-p5js/?xn1=8)

$$
 a_{8}= {\frac{ (b^2-\delta)^2 }{a c^2   }},\;\;\;
 b_{8}={\frac{  (a^{2} -\delta )^2  }{b c^2 }}
$$

### X(10) (similar to rotated billiard), [see it](https://dan-reznik.github.io/ellipse-mounted-loci-p5js/?xn1=10)

$$
\left(a_{10},b_{10}\right)=\left(\frac{k_{10}}a,\frac{k_{10}}b\right),\;\;   k_{10}=\frac{ \left( a^{2}+b^{2} \right)\delta-a^{4}-b^{4}}{2 c^2}
$$

### X(11) (identical to caustic), [see it](https://dan-reznik.github.io/ellipse-mounted-loci-p5js/?xn1=11)
 
$$a_{11}=a_c,\;\;\;b_{11}=b_c$$

### X(12), [see it](https://dan-reznik.github.io/ellipse-mounted-loci-p5js/?xn1=12)

$$a_{12}=\frac{ - w'_{12} (a,b)+ w''_{12}(a,b) \delta}{ w_{12} (a,b)},\;\;\;b_{12}=\frac{   w'_{12}(b,a)-w''_{12}(b,a)\delta}{ w_{12}(b,a)}$$

$$\begin{align*}
w'_{12}(u,v)=&
		  v^2(15\,{u}^{6}+12\,{v}^{2}{u}^{4}+3\,{u}^{2}{v}^{4}+2\,{v}^{6})\\
w''_{12}(u,v)= & 7\,{u}^{6}+12\,{v}^{2}{u}^{4}+11\,{u}^{2}{v}^{4}+2\,{v}^{6}  \\
w_{12}(u,v)=&  u( 7\,{u}^{6}+11\,{v}^{2}{u}^{4}-11\,{u}^{2}{v}^{4}-7\,{v}^{6}).
\end{align*}$$
 
### X(20), [see it](https://dan-reznik.github.io/ellipse-mounted-loci-p5js/?xn1=20)

$$a_{20}=     {\frac{a^{2} \left(3b^2- a^{2}  \right) -2b^2\,\delta }{ ac^2}}, \;\;\;
b_{20}=   {\frac{b^{2} \left(b^{2} -3a^2\right) +2a^2\,\delta}{b c^2 }}$$

### X(21), [see it](https://dan-reznik.github.io/ellipse-mounted-loci-p5js/?xn1=21)

$$
    a_{21}=\frac{-w'_{21}(a,b)+ w''_{21}(a,b) \delta}{ w_{21}(a,b)},\;\;\;b_{21}=\frac{ w'_{21}(b,a)- \,  w''_{21}(b,a)\delta}{ w_{21}(b,a)}\\
$$
  
$$w'_{21}(u,v)={u}^{4}+{u}^{2}{v}^{2}+ \,{v}^{4},\;\;w''_{21}(u,v)= 2( {u}^{2}+{v}^{2}),\;\;w_{21}(u,v)=u\left( 3\,{u}^{2}+5\,{v}^{2} \right)$$

### X(35), [see it](https://dan-reznik.github.io/ellipse-mounted-loci-p5js/?xn1=35)

$$\begin{align*}
a_{35}=&\frac{-w'_{35}(a,b)+w''_{35}(a,b) \delta}{w_{35}(a,b)},\;\;\;b_{35}=\frac{-w'_{35}(b,a)+w''_{35}(b,a)\delta}{w_{35}(b,a)} \\
w'_{35}(u,v)=&v^2( 11\,{u}^{4}+4\,{u}^{2}{v}^{2}+{v}^{4} ),\;\;\;w''_{35}(u,v)=\left( 7\,{u}^{2}+{v}^{2} \right)  \left( {u}^{2}+{v}^{2}\right)\\
w_{35}(u,v)=& u(7\,{u}^{4}+18\,{u}^{2}{v}^{2}+7\,{v}^{4} )
\end{align*}
$$

### X(36), [see it](https://dan-reznik.github.io/ellipse-mounted-loci-p5js/?xn1=36)

$$    a_{36}=\frac{w'_{36}(a,b)+ w''_{36}(a,b)\delta }{w_{36}(a,b)},\;\;\;b_{36}=\frac{  -w'_{36}(b,a)  -w''_{36}(b,a)\delta}{w(b,a)}$$

$$w'_{36}(u,v)=	{v}^{2} \left( {u}^{2}+{v}^{2} \right),\;\;\;w''_{36}(u,v)=  3\,{u}^{2}-{v}^{2},\;\;\;
w_{36}(u,v)=3u \left(u^2-v^2\right)$$

### X(40) (similar to rotated billiard), [see it](https://dan-reznik.github.io/ellipse-mounted-loci-p5js/?xn1=40)

$$a_{40}=\frac{c^2}a,\;\;\;b_{40}=\frac{c^2}b$$

Additionally:

- When $a/b= \sqrt{2}$, $b_{40}=b$, i.e., the top and bottom vertices of the $X_{40}$ locus coincides with the billiard's.
- When $a/b=(1+\sqrt{5})/2=\phi\;{\simeq}\;1.618$, $b_{40}=a$ and $a_{40}=b$, i.e., the $X_{40}$ locus is identical to a rotated copy of billiard.

### X(46), [see it](https://dan-reznik.github.io/ellipse-mounted-loci-p5js/?xn1=46)


$$a_{46}=\frac{w'_{46}(a,b)+w''_{46}(a,b) \delta}{ w_{46}(a,b) },\;\;\;b_{46}=\frac{-w'_{46}(b,a) - w''_{46}(b,a)\delta}{ w_{46}(b,a) }$$

$$\begin{align*}
w'_{46}(u,v)=& v^2(3\,{u}^{2}-{v}^{2} )(u^2-v^2),\;\;\;w''_{46}(u,v)= (5\,{u}^{2}+{v}^{2})(u^2-v^2) \\
w_{46}(u,v)=& v(5\,{u}^{4}-6\,{u}^{2}{v}^{2}+5\,{v}^{4} )
\end{align*}$$

### X(55) (similar to caustic), [see it](https://dan-reznik.github.io/ellipse-mounted-loci-p5js/?xn1=55)
      
$$a_{55}= {\frac{a\left(\delta-b^{2}
      		\right)}{a^{2}+b^{2}}},\;\;
       b_{55} =  { \frac{b \left( a^{2}-\delta
       	\right)}{a^{2}+b^{2}}}$$    

### X(56), [see it](https://dan-reznik.github.io/ellipse-mounted-loci-p5js/?xn1=56)

$$a_{56}=  \frac{-w'_{56}(a,b) + w''_{56}(a,b) \delta}{  w_{56}(a,b) },\;\;\;   
b_{56}= \frac{ w'_{56}(b,a) - w''_{56}(b,a) \delta}{  w_{56}(b,a) } $$

$$\begin{align*}
w'_{56}(u,v)=&v^2( {u}^{4}-{u}^{2}{v}^{2}+2\,{v}^{4}),\;\;\;w''_{56}(u,v)= 5\,{u}^{4}-5\,{u}^{2}{v}^{2}+2\,{v}^{4}  \\
w_{56}(u,v)=&u(5\,{u}^{4}-6\,{u}^{2}{v}^{2}+5\,{v}^{4} ) 
\end{align*}
$$

### X(57) (similar to billiard), [see it](https://dan-reznik.github.io/ellipse-mounted-loci-p5js/?xn1=57)

$$
\left(a_{57},b_{57}\right)=k_{57}\left(a,b\right),\;\;   k_{57}=\frac{c^2}{\delta}
%a_{57}=\frac{a (a^2- b^2)}{ \delta}, \;\;\;
%b_{57}=\frac{b (a^2- b^2)}{ \delta}$$

### X(63) (similar to billiard), [see it](https://dan-reznik.github.io/ellipse-mounted-loci-p5js/?xn1=63)

$$\left(a_{63},b_{63}\right)=k_{63}\left(a,b\right),\;\; k_{63}=\frac{c^2}{a^2+b^2}
%a_{63}={\frac{a \left( a^{2}-a^{2} \right) }{a^{2}+a^{2}}},\;\;\;
%b_{63}= {\frac{b \left( a^{2}-a^{2} \right) }{a^{2}+a^{2}}}$$

### X(65), [see it](https://dan-reznik.github.io/ellipse-mounted-loci-p5js/?xn1=65)

$$\begin{align*}
a_{65}=& \frac{w'_{65}(a,b) + w''_{65}(a,b) \delta}{  w_{65}(a,b)},\;\;\;
b_{65}=\frac{-w'_{65}(b,a)- w''_{65}(b,a) \delta}{  w_{65}(b,a)}
\end{align*}$$

$$\begin{align*}
w'_{65}(u,v)=& {u}^{4}{v}^{2}+{u}^{2}{v}^{4}+2\,{v}^{6},\;\;\;
w''_{65}(u,v)={u}^{4}-3\,{u}^{2}{v}^{2}-2\,{v}^{4}\\
w_{65}(u,v)=&u\left( {u}^{2}-{v}^{2} \right) ^{2}
\end{align*}$$

### X(72), [see it](https://dan-reznik.github.io/ellipse-mounted-loci-p5js/?xn1=72)

$$\begin{align*}
a_{72}=& \frac{w'_{72}(a,b) - w''_{72}(a,b) \delta }{w_{72}(a,b)},\;\;\;
b_{72}= \frac{-w'_{72}(b,a) + w''_{72}(b,a) \delta}{w_{72}(b,a) }
\end{align*}$$

$$w'_{72}(u,v)= {u}^{6}+2\,{u}^{2}{v}^{4}+{v}^{6},\;\;
w''_{72}(u,v)= (3\,{u}^{2}+{v}^{2}){v}^{2},\;\;
w_{72}(u,v)= u\left(u^2-v^2 \right)^{2}$$

### X(78), [see it](https://dan-reznik.github.io/ellipse-mounted-loci-p5js/?xn1=78)
          
$$a_{78}= \frac{w'_{78}(a,b) -w''_{78}(a,b) \delta }{w_{78}(a,b) },\;\;\;
b_{78}=  \frac{-w'_{78}(b,a)+w''_{78}(b,a) \delta}{w_{78}(b,a)}$$

$$\begin{align*}
w'_{78}(u,v)=&5\,{u}^{6}-4\,{u}^{4}{v}^{2}+{u}^{2}{v}^{4}+2\,{v}^{6},\;\;\;w''_{78}(u,v)= 2\,{v}^{2} \left( {u}^{2}+{v}^{2}\right)\\
w_{78}(u,v)=&u \left( 5\,{u}^{4}-6\,{v}^{2}{u}^{2}+5\,{v}^{4} \right)\
\end{align*}$$

### X(79), [see it](https://dan-reznik.github.io/ellipse-mounted-loci-p5js/?xn1=79)


$$a_{79}= \frac{-w'_{79}(a,b) + w''_{79}(a,b) \delta  }{w_{79}(a,b) }, \;\;\; 
b_{79}= \frac{  w'_{79}(b,a)- w''_{79}(b,a) \delta  }{  w_{79}(b,a)  }$$

$$\begin{align*}
w'_{79}(u,v)=&{v}^{2}   11\,{u}^{4}+4\,{v}^{2}{u}^{2}+{v}^{4},\;\;\;w_{79}''(u,v)= \left( 3\,{u}^{4}+12\,{u}^{2}{v}^{2}+{v}^{4} \right)   \\
w_{79}(u,v)=&u \left( u^2-v^2 \right) \left( 3\,{u}^{2}+5\,{v}^{2} \right)
\end{align*}$$

### X(80), [see it](https://dan-reznik.github.io/ellipse-mounted-loci-p5js/?xn1=80)
      
$$a_{80}={\frac{ \left( \delta-b^{2} 
      		\right)  \left( a^{2}+b^{2} \right)}{a c^2}},\;\;\;
b_{80}={\frac{ \left( a^{2}-\delta
      		\right)  \left( a^{2}+b^{2} \right)}{b c^2}}$$
      
### X(84) (similar to rotated caustic), [see it](https://dan-reznik.github.io/ellipse-mounted-loci-p5js/?xn1=84)

$$a_{84}=\frac{\left(b^{2}+\delta \right) c^2}{a^{3}},\;\;\;
b_{84}=\frac{\left( a^{2}+\delta \right) c^2}{b^{3}}$$
  
### X(88) (identical to billiard), [see it](https://dan-reznik.github.io/ellipse-mounted-loci-p5js/?xn1=88)
      
$$a_{88}=a,\;\;\;b_{88}=b$$
      
### X(90), [see it](https://dan-reznik.github.io/ellipse-mounted-loci-p5js/?xn1=90)


$$a_{90}= \frac{ w'_{90}(a,b) +  w''_{90}(a,b)\delta   }{w_{90}(a,b)},\;\;\;
b_{90}= \frac{w'_{90}(b,a)+w''_{90}(b,a) \delta  }{  w_{90}(b,a)}$$

$$\begin{align*}
w'_{90}(u,v)=&v^2(3u^2-v^2) (u^2-v^2),\;\;\;
w''_{90}(u,v)=u^4-v^4 \\
w_{90}(u,v)=& u \left( {u}^{4}+2\,{u}^{2}{v}^{2}-7\,{v}^{4} \right)
\end{align*}$$


### X(100) (identical to billiard), [see it](https://dan-reznik.github.io/ellipse-mounted-loci-p5js/?xn1=100)

$$a_{100}=a,\;\;\;b_{100}=b$$

**Note:** From $X_{101}$ thru $X_{200}$, also elliptic are the loci of $X_k$ $k$in 104, 119, 140, 142, 144, 145, 149, 153, 162, 165, 190, 191, 200.


# II. Homothetic Family: Locus Semi-Axes

Consider 3-periodics in an ellipse pair such that $a_c=a/2$ and $b_c=b/2$. From $X_{1}$ to $X_{200}$, the loci of 27 (resp. 4) triangle centers are ellipses (resp. circles). Their axes are given by:

### X(3)

\[ a_3= \frac{c^2}{4a},\;\;\;b_3=\frac{c^2}{4b} \]

### X(4)

\[ a_4= \frac{c^2}{2a},\;\;\;b_4=\frac{c^2}{2b} \]

### X(5)

\[ a_5= \frac{c^2}{8a},\;\;\;b_5=\frac{c^2}{8b} \]

### X(6)

\[ a_6= \frac{ac^2}{2(a^2+b^2)},\;\;\;b_6=\frac{bc^2}{2(a^2+b^2)} \]

### X(13), X(14), X(15), X(16): all circles! [see it](https://bit.ly/3bhA4dK) and [video](https://youtu.be/ZwTfwaJJitE)

\[ r_{13}= \frac{a-b}{2},\;\;\;r_{14}= \frac{a+b}{2},\;\;\;r_{15}= \frac{(a-b)^2}{2(a+b)},\;\;\;r_{16}= \frac{(a+b)^2}{2(a-b)} \]

### X(17)

\[ 	a_{17}=\frac{c^2}{2(a+3b)},\;\;\;b_{17}= \frac{c^2}{2(3a+b)} \]

### X(18)

\[ a_{18}=\frac{c^2}{2(a-3b)},\;\;\;b_{18}= \frac{c^2}{2(3a-b)} \]

### X(20)

\[ a_{20}= \frac{c^2}a,\;\;\;b_{20}=\frac{c^2}b \]

### X(32)

\[ a_{32}= \frac {a \left( c^2 \right)   \left( 3\,a^{2}+5\,b^{2} \right)}{2(3\,a^{4}+2\,a^{2}b^{2}+3\,b^{4})},\;\;\;
   b_{32}= \frac {b \left( c^2 \right)   \left( 3\,a^{2}+5\,b^{2} \right)}{2(3\,a^{4}+2\,a^{2}b^{2}+3\,b^{4})} \]

### X(39)

\[ a_{39}=\frac { \left( a^{2}-b^{2} \right) a}{2( a^{2}+3\,b^{2})},\;\;\;
	b_{39}=\frac{ \left( a^{2}-b^{2} \right) b}{2(3 \,a^{2}+\,b^{2})}\]

### X(61)

\[a_{61}= \frac {\left( c^2\right)\left( 3\,a-b	\right)}{2( 3a^{2}+2\,ab+3\,b^{2})},\;\;\;
b_{61}= \frac { \left( c^2 \right)\left( a-3\,b \right)}{2(3\,a^{2}+2\,ab+3\,b^{2})}\]

### X(62)

\[a_{62}=\,{\frac{\left( c^2\right)\left(3\,a+b\right)}{2(3\,a^{2}-2\,ab+3\,b^{2})}},\;\;\;
b_{62}={\frac{ \left( c^2 \right)  \left( a+3b\right) }{2(3\,a^{2}-2\,ab+3\,b^{2})}}\]

### X(69)

\[a_{69}={\frac { \left( c^2 \right)a}{a^{2}+b^{2}}},\;\;\;
b_{69}=\frac{\left( c^2 \right)b}{a^{2}+b^{2}} \]
				
				
### X(76)

\[ a_{76}=\frac{\left( c^2 \right)a}{a^{2}+3b^{2}},\;\;\;
b_{76}= \frac{ \left( c^2 \right)b}{3a^{2}+b^{2}} \]

### X(83)

\[a_{83} = \frac { \left( c^2 \right) a}{5a^{2}+3b^{2}},\;\;\;
b_{83} = \frac{ \left( c^2 \right) b}{3a^{2}+5b^{2}} \]

### X(98)

\[ a_{98}= \frac{a^2+b^2}{2a},\;\;\;b_{98}= \frac{a^2+b^2}{2b} \]

### X(99)

\[ a_{99}=a,\;\;\;b_{99}=b \]

### X(114)

\[ a_{114}= \frac{a^2+b^2}{4a},\;\;\;b_{114}= \frac{a^2+b^2}{4b} \]

### X(115)

\[ a_{115}= \frac{a }{2},\;\;\;b_{115}= \frac{b}{2} \]

### X(140)

\[ a_{140}= \frac{c^2}{16a},\;\;\;b_{140}= \frac{c^2}{16b} \]

### X(141)

\[ a_{141}=\frac{c^2 a}{4(a^2+b^2)}\;\;\;b_{141}= \frac{c^2 b}{4(a^2+b^2)} \]

### X(147)

\[ a_{147}=\frac{a^2+b^2}a,\;\;\;b_{147}= \frac{a^2+b^2}b \]

### X(148)

\[ 	a_{148}=2a,\;\;\;b_{148}=2b \]

### X(182)

\[ 	a_{182}=\frac{c^4}{8a(a^2+b^2)},\;\;\;
b_{182}= \frac{c^4}{8b(a^2+b^2)} \]

### X(187)

\[ 	a_{187}= \frac{a(a^2+3b^2)}{2c^2},\;\;\;
b_{187}=  \frac{b(3a^2+b^2)}{2c^2} \]

### X(190)

\[ 	a_{190}= a,\;\;\;b_{190}=b \]

### X(193)

\[ 	a_{193}=\frac{2c^2 a}{a^2+b^2},\;\;\;
		b_{193}=\frac{2c^2 b}{a^2+b^2} \]

### X(194)

\[  a_{194}=\frac{2c^2 a}{a^2+3b^2},\;\;\;
b_{194}=\frac{2c^2 b}{3a^2+b^2} \]



# Appendix A: Confocal Family: elliptic fit error

Let the least-squares fit error be defined by:

$$\text{err}^2(a_i,b_i)= \sum_{k=1}^M{\left[\left(\frac{x_k}{a_i}\right)^2+\left(\frac{y_k}{b_i}\right)^2-1\right]^2}$$

The 29 centers with elliptic loci amongst the first 100 in Kimberling's Encyclopedia [@etc]. These are listed in ascending order of (negligible) fit error, $a/b=1.5$, $M=1500$. Columns $\hat{a},\hat{b}$ show the estimated semi-axes' lengths. Notice for $X_{100}$ and $X_{88}$ these are identical to $a,b$, since these points lie on the EB. 


$$
\begin{array}{|c|c|c|c|c|}
\hline
 \text{rank} &  X_i & \hat{a} & \hat{b} & \sum{err{}^2} \\
 \hline
 1 & 100 & 1.50 & 1.00 & 5.9\times 10^{-14} \\
 2 & 80 & 1.65 & 0.77 & 8.1\times 10^{-14} \\
 3 & 46 & 1.47 & 1.18 & 8.3\times 10^{-14} \\
 4 & 36 & 2.57 & 2.34 & 1.\times 10^{-13} \\
 5 & 88 & 1.50 & 1.00 & 1.\times 10^{-13} \\
 6 & 56 & 1.05 & 0.74 & 1.1\times 10^{-13} \\
 7 & 20 & 1.18 & 2.43 & 1.1\times 10^{-13} \\
 8 & 72 & 0.75 & 0.35 & 1.1\times 10^{-13} \\
 9 & 63 & 0.58 & 0.38 & 1.2\times 10^{-13} \\
 10 & 40 & 0.83 & 1.25 & 1.3\times 10^{-13} \\
 11 & 78 & 1.12 & 0.28 & 1.3\times 10^{-13} \\
 12 & 57 & 0.96 & 0.64 & 1.4\times 10^{-13} \\
 13 & 79 & 0.85 & 0.68 & 1.4\times 10^{-13} \\
 14 & 4 & 0.98 & 1.48 & 1.4\times 10^{-13} \\
 15 & 65 & 0.90 & 0.58 & 1.4\times 10^{-13} \\
 16 & 7 & 0.79 & 0.52 & 1.5\times 10^{-13} \\
 17 & 11 & 1.14 & 0.24 & 1.7\times 10^{-13} \\
 18 & 5 & 0.44 & 0.50 & 1.7\times 10^{-13} \\
 19 & 84 & 1.09 & 5.25 & 1.8\times 10^{-13} \\
 20 & 12 & 0.55 & 0.38 & 1.8\times 10^{-13} \\
 21 & 1 & 0.64 & 0.30 & 1.8\times 10^{-13} \\
 22 & 2 & 0.26 & 0.17 & 2.3\times 10^{-13} \\
 23 & 3 & 0.10 & 0.48 & 2.5\times 10^{-13} \\
 24 & 55 & 0.44 & 0.09 & 2.9\times 10^{-13} \\
 25 & 8 & 0.48 & 0.07 & 3.3\times 10^{-13} \\
 26 & 10 & 0.08 & 0.11 & 3.6\times 10^{-13} \\
 27 & 90 & 3.93 & 0.34 & 4.\times 10^{-13} \\
 28 & 21 & 0.19 & 0.05 & 4.6\times 10^{-13} \\
 29 & 35 & 0.33 & 0.03 & 4.8\times 10^{-13} \\
 \hline
 \end{array}
$$
The remaining 71 centers amongst the first 100 in [@etc] whose loci are not elliptic, still ordered by increasing fit errors, which now are several orders of magnitude higher. Notice $X_9$ whose locus is a point has the highest of all errors.


<div class = "row">
<div class = "col-md-5">
$$
\begin{array}{|c|c|c|}
\hline
\text{rank} &  X_i & \sum{err{}^2} \\
\hline
 30 & 37 & 1.9\times 10^{-3} \\
 31 & 6 & 6.2\times 10^{-3} \\
 32 & 45 & 8.\times 10^{-3} \\
 33 & 60 & 8.3\times 10^{-3} \\
 34 & 86 & 1.3\times 10^{-2} \\
 35 & 71 & 1.6\times 10^{-2} \\
 36 & 41 & 1.8\times 10^{-2} \\
 37 & 81 & 1.8\times 10^{-2} \\
 38 & 58 & 3.3\times 10^{-2} \\
 39 & 62 & 4.\times 10^{-2} \\
 40 & 31 & 4.3\times 10^{-2} \\
 41 & 89 & 4.4\times 10^{-2} \\
 42 & 42 & 4.5\times 10^{-2} \\
 43 & 17 & 5.6\times 10^{-2} \\
 44 & 13 & 8.3\times 10^{-2} \\
 45 & 83 & 9.\times 10^{-2} \\
 46 & 48 & 1.1\times 10^{-1} \\
 47 & 32 & 1.3\times 10^{-1} \\
 48 & 61 & 1.3\times 10^{-1} \\
 49 & 82 & 1.3\times 10^{-1} \\
 50 & 43 & 1.5\times 10^{-1} \\
 51 & 51 & 1.6\times 10^{-1} \\
 52 & 85 & 1.6\times 10^{-1} \\
 53 & 19 & 1.7\times 10^{-1} \\
 54 & 27 & 1.9\times 10^{-1} \\
 55 & 69 & 1.9\times 10^{-1} \\
 56 & 47 & 2.5\times 10^{-1} \\
 57 & 39 & 2.7\times 10^{-1} \\
 58 & 38 & 2.8\times 10^{-1} \\
 59 & 16 & 3.4\times 10^{-1} \\
 60 & 52 & 5.3\times 10^{-1} \\
 61 & 28 & 5.6\times 10^{-1} \\
 62 & 25 & 7.5\times 10^{-1} \\
 63 & 99 & 8.2\times 10^{-1} \\
 64 & 14 & 8.3\times 10^{-1} \\
 65 & 98 & 8.5\times 10^{-1} \\
  \hline
\end{array}
$$
 
</div>
<div class = "col-md-5">
 $$
\begin{array}{|c|c|c|}
\hline
\text{rank} &  X_i & \sum{err{}^2} \\
\hline
 66 & 44 & 1.7 \\
 67 & 22 & 1.7 \\
 68 & 34 & 1.7 \\
 69 & 75 & 1.9 \\
 70 & 54 & 2.1 \\
 71 & 53 & 2.2 \\
 72 & 29 & 2.4 \\
 73 & 15 & 2.5 \\
 74 & 33 & 2.6 \\
 75 & 24 & 2.6 \\
 76 & 74 & 3.2 \\
 77 & 97 & 3.3 \\
 78 & 67 & 4. \\
 79 & 23 & 4.6 \\
 80 & 91 & 5.2 \\
 81 & 96 & 5.2 \\
 82 & 76 & 5.8 \\
 83 & 18 & 7.6 \\
 84 & 73 & 8.5 \\
 85 & 94 & 9.3 \\
 86 & 70 & 9.3 \\
 87 & 92 & 1.2\times 10^1 \\
 88 & 77 & 1.4\times 10^1 \\
 89 & 95 & 1.5\times 10^1 \\
 90 & 49 & 1.8\times 10^1 \\
 91 & 87 & 1.8\times 10^1 \\
 92 & 59 & 1.9\times 10^1 \\
 93 & 64 & 3.9\times 10^1 \\
 94 & 68 & 3.9\times 10^1 \\
 95 & 26 & 3.9\times 10^1 \\
 96 & 66 & 3.9\times 10^1 \\
 97 & 50 & 3.9\times 10^1 \\
 98 & 93 & 3.9\times 10^1 \\
 99 & 30 & 3.9\times 10^1 \\
 100 & 9 & 3.9\times 10^1 \\
 \hline
\end{array}
$$
</div>
</div>


# Contact

Any comments, ideas, corrections, suggestions, and proofs contributed are very welcome. Email me at: `dreznik _theat_ gmail _thedot_ com`.

***

# References
