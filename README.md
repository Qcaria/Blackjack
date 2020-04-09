# Blackjack
Basic Blackjack player that learns through Monte Carlo sampling.

Cards drawn are replaced back to the deck, so card counting is not helpful in this particular example. It has been a cool program to write, where I tried to replicate the example shown in the Reinforcement Learning: An Introduction by Barto and Sutton.
Although the policy learned by the player in my program is the same as the one they show, the expected return seems to me too low (around -4.5%) while in some mathologer video where they talk about the basic strategy say that its expeted return is around -0.05%. The only explanation I can come with is that doubling and some other actions are not contempled in my program, which could account for the gap. I don't discard errors in the program though.

To sum up a little fun project that helped me get a bit more used to some basic concepts of reinforcement learning.
