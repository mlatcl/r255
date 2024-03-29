---
title: 'Bias, Variance and Fairness: Stochasticity in Decision Making'
date: 2023-01-20
time: '12:30'
start: '13:00'
end: '15:00'
layout: topic
topic: 7
year: 2023
youtube: lLvzTJtYeU8
blog: 2017-11-15-decision-making.md
blog1: 2018-02-06-natural-and-artificial-intelligence.md
blog2: 2015-12-04-what-kind-of-ai.md
featured_image: slides/diagrams/ml/bias-variance008.png
transition: None
---

>>>>>>> d80589667b5c270bf9b8fc946f4d69b53cbb701d
\notes{\subsection{Overview}}

\notes{In this topic we will explore the relationship between the bias-variance dilemma and real world decisions. The opening session will set the context, then we will read the following four papers.}

\notes{1. [Neural Networks and the Bias/Variance Dilemma](https://www.dam.brown.edu/people/documents/bias-variance.pdf) by Stuart Geman, Elie Bienenstock, and René Doursat (the technical material of importance is in Section 3). 
2. [Probabilistic electrol methods, representative proability and Maximum Entropy](https://www.votingmatters.org.uk/ISSUE26/I26P3.pdf) by Roger Sewell, David MacKay and Ian McLean
3. [Habitual Ethics? Chapter 7](https://library.oapen.org/bitstream/handle/20.500.12657/58884/9781509920433.pdf) by Sylvie Delacroix
4. [Killing, Letting Die and the Trolley Problem](https://learning.hccs.edu/faculty/david.poston/phil1301.80361/readings-for-march-31/JJ%20Thomson%20-%20Killing-%20Letting%20Die-%20and%20the%20Trolley%20Problem.pdf) by Judith Jarvis Thomson}

\notes{The presentation for each paper will be in the form of an 800 word summary that captures the main message of the work and sets it against the context of the wider discussion we will set up in this first session.}

\include{_philosophy/includes/utilitarianism.md}
\include{_philosophy/includes/utility-utilitarianism.md}
\include{_philosophy/includes/uncertainty-and-absolutism.md}
\include{_ml/includes/what-is-ml-2.md}
\include{_philosophy/includes/bias-towards-variance.md}
\include{_philosophy/includes/bias-variance-in-ml.md}
\include{_philosophy/includes/bias-variance-rational.md}

\notes{
\subsection{Fairness in Decision Making}}

\notes{As a more general example, let's consider fairness in decision making. Computers make decisions on the basis of our data, how can we have confidence in those decisions?}

\newslide{}

\figure{\includepng{\diagramsDir/data-science/convention-108-coe}{70%}}{The convention for the protection of individuals with regard to the processing of personal data was opened for signature on 28th January 1981. It was the first legally binding international instrument in the field of data protection.}{convention-108-coe}

\notes{\include{_governance/includes/gdpr-overview.md}}

\notes{The GDPR gives us some indications of the aspects we might consider when judging whether or not a decision is "fair".}

\notes{But when considering fairness, it seems that there's two forms that we might consider.}

\notes{\include{_ai/includes/p-n-fairness.md}}

\newslide

\slides{\figure{\includediagramclass{\diagramsDir/ai/n-p-fairness}{80%}}{We seem to have two different aspects to fairness, which in practice can be in tension.}{n-p-fairness}}

\notes{\include{_ai/includes/reflexive-reflective.md}}

\newslide

$$\text{reflect} \Longleftrightarrow \text{reflex}$$

\newslide

\newslide{Conclusion}
\slides{
* Tendency to seek proxies such as *consistency* in decision making. 
* Consistent algorithms oversimplifies.
* Society would be more robust if diversity of solutions and opinions are sustained and respected. 
}

\notes{Simplistic interpretations of utility theory are misleading about the real decisions we face, and similarly for the machines we design. These simplistic perspctives have also led to a tendency to seek proxies for a notion of "correct" decision making such as consistency. However, in practice uncertainty means that our decisions will often be incorrect. Faced with this incorrectness. Once we accept errors will be made, we can see that making consistent errors is likely to be more harmful than when those errors are inconsistent. }

\subsection{Links}

>>>>>>> d80589667b5c270bf9b8fc946f4d69b53cbb701d
* [This paper on decision making and diversity](http://inverseprobability.com/2017/11/15/decision-making)
* [This post on System Zero](http://inverseprobability.com/2015/12/04/what-kind-of-ai/) and [This post on the Mechanistic Fallacy](http://inverseprobability.com/2015/11/09/artificial-stupidity/) relate to the ideas in this talk.
* [This post on natural vs artificial systems](http://inverseprobability.com/2018/02/06/natural-and-artificial-intelligence)
* Articles in the Guardian are available from my [Guardian Profile Page](http://www.theguardian.com/profile/neil-lawrence)
* [My blog](http://inverseprobability.com/blog.html) has articles relating to this area.


\thanks

\references
