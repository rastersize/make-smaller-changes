# Make Smaller Changes

Staying productive in an evergrowing codbase can be an uphill battle. Sometimes merging seemingly simple things can take days or even weeks. By the time someone gets around to reviewing your diff its often outdated and riddled with merge conflicts. The one strategy that has helped me deal with this more than any other is to **make smaller changes**.

I follow the rule of thumb that PRs with the word "and" in the description should probably be broken up - even if they are small to begin with. Not only do these PRs get reviewed and merged significantly faster, the quality of reviews also tends to be better. The process of dividing up a PR into independently mergeable parts also encourages simpler, more decoupled designs.

It's important to note that the parts you break your PR into should be dependent on each other. It should be possible to merge them in any order, and you should not expect all parts to get merged. Failing to adhere to this will not actually solve the problems caused by big changes - it will just spread them out.

When submitting any change, put yourself in the shoes of the reviewer. Which of the following would you rather be faced with when a colleague sends you a PR to look at?



Make a habit of making smaller changes.

