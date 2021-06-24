### How does Tourney work?

Despite the name and icon, Tourney doesn't use a [tournament bracket](https://en.wikipedia.org/wiki/Bracket_(tournament)). Bracket 

(Other dead-ends include [Condorcet methods](https://en.wikipedia.org/wiki/Condorcet_method), [merge-insertion sort](https://en.wikipedia.org/w/index.php?title=Merge-insertion_sort&oldid=983711349#:~:text=Merge-insertion%20sort%20is%20the%20sorting%20algorithm%20with%20the%20minimum%20possible%20comparisons), and [optimal sorting networks](https://en.wikipedia.org/w/index.php?title=Sorting_network&oldid=1020757527#Optimal_sorting_networks)).)

The problems are fuzziness and non-transitivity (cycles). TODO: make SVG of rock paper scissors

Another simple way to rank a set of items is to, as done in [Tom Scott's survey](https://www.youtube.com/watch?v=ALy6e7GbDRQ&t=11). This works OK if you have millions of votes like in that survey, but Tourney wouldn't be very useful if it needed thousands of comparisons to sort a list. The statistical "resolving power" of such a simple algorithm is inherently limited: [some things were tied](https://www.youtube.com/watch?v=ALy6e7GbDRQ&t=517) in Tom Scott's survey even thought the data collected would be enough to resolve the tie. Say for example the following two comparisons were collected:

    🍕 > 🍔
    🍔 > 🌭

The simple algorithm only collects 

    top
    pizza 1
    burger 1
    sandwich
    hotdog

(Other dead-ends include .)

### License

TODO CC0-1.0 or AGPLv3?

