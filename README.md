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

Mary is a self-aware observer `(*W, Hs)` with complete knowledge, which means her `*W ≙ W`.
We assume that when she finally leaves her room and sees the color red (message `Mred`), her observer state `Os` is affected in some way:  
`obs(Os, Mred) = Os'`  
Because her `*W` is already accurate, this implies a change to her inner state:  
`obs((*W, Hs), Mred) = (*W, Hs')`.  
Something in herself has changed, something that cannot be part of any knowledge that can be transmitted through a black and white television.  
  
We can compare this process to what happened when she was merely thinking about this process, before she had left her room.  
We can model her observation as a thought, because we don't require a message:  
`obs(Os, M°) = Os'`  
She is making a prediction, so we can describe what happens as a simulated change of world state:  
`obs((*W, Hs), M°) = (*W', Hs)`  
`obs(((*Ws, *evt), Hs), M°) = ((*Ws', *evt), Hs)`  
The change she expects on seeing the color red is a change to her own observer state, but not to her world model, which is an accurate representation of what happens when she leaves her room:  
`obs((((*Os, *Es), (*obs, *eevt)), Hs), M°) = (((*Os', *Es), (*obs, *eevt)), Hs)`  
`obs(((((**W, *Hs), *Es), (*obs, *eevt)), Hs), M°) = ((((**W, *Hs'), *Es), (*obs, *eevt)), Hs)`  

We note that while she predicts a change of her hidden state `*Hs → *Hs'`, her actual hidden state `Hs` is not affected that way by her prediction. This change only manifests once she is actually seeing the color red. This means that there is a brain state associated with seeing the color red that she knows about and can functionally predict and destribe, but cannot reach (experience) without actually observing the color red.

Thinking about a brain state is different from experiencing (accessing it).
