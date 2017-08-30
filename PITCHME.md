#HSLIDE

# Blockchain

### Simple intrudiction to distributed ledgers

<span class="primary"><strong>Gergely Hegedüs</strong></span> - <a href="https://twitter.com/pshegger" target="_blank">@pshegger</a>

#HSLIDE

## So, what is it?

<p class="fragment">It's a chain of blocks of course</p>
<p class="fragment">With some clever tricks to make it suitable for various applications</p>

#VSLIDE

## What kind of applications?

- Digital Currencies (Bitcoin, Ethereum, etc.) <!-- .element: class="fragment" -->
- Supply Management Systems <!-- .element: class="fragment" -->
- Others (even ones nobody thought about yet!) <!-- .element: class="fragment" -->

#HSLIDE

## How does it work?

- The full chain is stored in every node <!-- .element: class="fragment" -->
- When a new transaction is created it is sent to every node <!-- .element: class="fragment" -->
- For a transaction to be confirmed it must be included in a block <!-- .element: class="fragment" -->
- The blocks are then broadcasted to the other nodes <!-- .element: class="fragment" -->


#VSLIDE

## What is a transaction?

Any kind of data, but usually:

- Goods movement (currency, product) <!-- .element: class="fragment" -->
- Smart contracts <!-- .element: class="fragment" -->

#VSLIDE

## And what is a block?

- A list of transactions stored together <!-- .element: class="fragment" -->
- A link to the previous block (to create a chain) <!-- .element: class="fragment" -->
- Hash of the data to detect changes <!-- .element: class="fragment" -->

#VSLIDE

## Who creates these blocks?

One of the nodes selected by a fair "lottery" algorithm. After creating the block it is broadcasted to every other node.

#HSLIDE

## How can the nodes trust each other?

- The chaining of blocks makes it really hard to change an old one <!-- .element: class="fragment" -->
- Because of this the nodes always accepts the longest chain as current <!-- .element: class="fragment" -->

#VSLIDE

## So what if a node creates a new longer chain?

- Blockcahins are design to make it hard <!-- .element: class="fragment" -->
- But if it happens somehow, it would overwrite the previous chain <!-- .element: class="fragment" -->

#VSLIDE

## 51% attack (Bitcoin's main enemy)

- Bitcoin uses a proof-of-work algorithm to make it harder to replace the current chain <!-- .element: class="fragment" -->
- If a node has more than 50% of the computing capacity it can slowly create a longer chain <!-- .element: class="fragment" -->

#HSLIDE

## Why is it good?

- No single point of failure <!-- .element: class="fragment" -->
- No centralized authority to trust <!-- .element: class="fragment" -->


#VSLIDE

## Why is it not so good?

- Every node have to store the full chain
    - Size of the Bitcoin blockchain at the time of writing: ~127 GB <!-- .element: class="fragment" -->
- Proof-of-work computing takes a lot of time/energy <!-- .element: class="fragment" -->
    - This can make the vonfirmation of transactions slow <!-- .element: class="fragment" -->
    - example: Bitcoin blocks are created every ~10 minutes and contain ~1800 transactions <!-- .element: class="fragment" -->

#HSLIDE

# Any Questions?
