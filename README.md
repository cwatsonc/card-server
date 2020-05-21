
Card Room
------------

Current Release: Egregious Plight

Built with [Glitch](https://glitch.com/about).


A simple game application that stores a shared game state on a server. 

Multiple flavors of game tables to adapt. 

No rules, or AI, just play your game.

Plan:

* Convert to JSX Component based solution
* Provide a customizable deck strip out cards for irregular deck play
* Provide more fluid game play actions (trick play, trick booking, deck cutting)
* Fix errors in z-ordering, move from legacy drag and drop to a modern impl
* Implement correct ordering of card placement preventing seemingly random reordering
* Provide an insert gesture/implementation that corrects z-order of cards on drop
* Fix incorrect orientation of cards placed in 90 degree player areas.
* Flip on mapped key+click
* Orient card 90 degrees on mapped key (cmd+option)
* provide a dynamically discovered drop zone behavior for vertical player areas.
* Fix drop card to quantize the drop offsets -- if a newline is needed provide space
* Scoring area with selectable flavors (cribbage, chips, scorepad)
* fix client card move race condition if client - a completes an operation before client - b

Contact: @cwatsonc




