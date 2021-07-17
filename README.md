# Observer State Access Theory of Consciousness

## Introduction
    // work in progress

## The Model

### Definition: World
A _world_ `W` consists of  
__W.1__ a _world state_ `Ws`.  
__W.2__ an event function `evt: Ws → Ws'` where each transition is called an _event_.  
__W.3__ we can describe `W := (Ws, evt)`.

### Definition: Observer
An _observer_ `O` is any physical or computational system that  
__O.1__ has an _internal observer state_ `Os` that is part of `Ws`.  
__O.2__ defines the _environmental state_ `Es` as the part of the world state that is not `Os`. `Ws` can now be described as `Ws := (Os, Es)`.  
__O.3__ is connected to its environment in such a way that it receives _messages_ `M` defined by `m: (Os, Es) → M` depending on this connection. `M°` denotes the _empty message_ (no message).  
__O.4__ changes its internal state based on the messages it receives as described by `obs: (Os, M) → Os'`. Where each transition is called an _observation_.  
__O.5__ An observation where `M = M°` is called a _thought_.  

#### Lemma: Observation Events
We notice that `(obs ∘ I): (Os, Es) → Os'` describes a transition between world states. We can say that observations are events which means we can categorize events so that `evt = (obs, eevt)` where `eevt` are _external events_.  

### Definition: World-model:
A _world-model_ `*W` is a collection of assumptions about the world.  

### Definition: Representation
__R.1__ A _representation_ `*t` is a collection of assumptions, about a _thing_ `t`. `*t` is a subset of a world-model `*W`.  
__R.2__ We say that `*t` is an _accurate representation of `t`_ and write `*t ≙ t` if it fulfills the following requirements:  
__R.2.1__ If `*t` is a composite `(*a, *b, …)`, all `*a, *b, …` have to be accurate representations of `a, b, … in t = (a, b, …)`.  
__R.2.2__ If `*t` is not a composite, it behaves in `*W` like t behaves in the world `W`.  
__R.3__ We say that `*t'` is _more accurate_ than `*t` if `*t` is not accurate and  
__R.3.1__ `*t'` is accurate or  
__R.3.2__ `*t' = (*a', *b', …)` has one or more `*x' in (*a', *b', …)` more accurate than `*x` while all other elements `*y' in *t'` have `*y' = *y`.  

#### Lemma: World Representation
__WR.1__ A world-model `*W` is a representation of the world `W`.  
__WR.2__ If `*W` is accurate, `*W = (*Ws, *evt)`.  

### Definition: Intelligent Observer
An _intelligent observer_ is an observer that  
__I.1__ maintains a world-model `*W` as part of his state `Os`. `Os := (*W, Hs)` where `Hs` denotes the _hidden state_ – the part of the observer state that is not part of `*W`.  
__I.2__ uses thoughts to make _predictions_ about the world. A prediction is a thought of the form  
`(Os, M°) → Os' = ((*W, Hs), M°) → (*W', Hs) = (((*Ws, *evt), Hs), M°) → ((*Ws', *evt), Hs)`  
and `*Ws' = *evt(*Ws)`.  
__I.3__ we say that generally, intelligent observers are _more intelligent_ when more of their predictions are accurate. A prediction as described in __I.2___ is accurate when `*Ws' ≙ evt(Ws)`.  

#### Note I.WR
An intelligent observer generally is more intelligent when his world-model is more accurate.  

### Definition: Self-awareness
An intelligent observer is a _self-aware observer_ if his world-model includes a represenation of itself. This means that his `*W = (*Ws, *evt) = ((*Os, *Es), (*obs, *eevt))`.  

#### Note I.SR
A self-aware observer is in general more intelligent because he can make predictions about himself.  

## Example
### Applying this model to the argument of Mary's room.

[Introduction to the argument of Mary's room](https://en.wikipedia.org/wiki/Knowledge_argument).

Mary is a self-aware observer with complete knowledge, which means she has an accurate world-model and thus can simulate herself seeing the color red by  

    obs(Os, M°) = Os'
    obs((*W, Hs), M°) = (*W', Hs)
    obs(((*Ws, *evt), Hs), M°) = ((*Ws', *evt), Hs)
    obs((((*Os, *Es), (*obs, *eevt)), Hs), M°) = (((*Os', *Es), (*obs, *eevt)), Hs)
    obs(((((**W, *Hs), *Es), (*obs, *eevt)), Hs), M°) = ((((**W, *Hs'), *Es), (*obs, *eevt)), Hs)
with `(**W, *Hs') = *obs((**W, *Hs), *Mred)` where `*Mred = *m(*Os, *Es)`.  
  
This is an accurate representation of what happens when she finally leaves her black and white world and sees the color red:  

    obs(Os, Mred) = Os'
    obs((*W, Hs), Mred) = (*W, Hs')

We note that `*W in Os'` stays unchanged by the observation `Mred`, which means Mary has not gained any new knowledge. This is exactly what we would expect, as her knowledge by constraint was already complete.
However, we also notice that Mary 'experiences' a change of her hidden state from `Hs to Hs'`, something she was able to functionally predict and describe, but not able to actually access by merely representing that process in her world-model.
This shows how at least some observations as described in this model must have _subjective qualities_ that are not accessed or not accessible by reasoning or communicating about them.
Thus these behaviors and relationships of observers, perspective and subjectivity should not be accepted as arguments against (classical) physicalism but to the contrary, as something predicted by it.  
  
This entire paper summarized in plain words:  
__Hitting your thumb with a hammer hurts in a way merely thinking about it does not. This relationship is obvious, is predicted by our physicalist understanding of the world and cannot reasonably understood or be used as an attack on physicalism.__  
