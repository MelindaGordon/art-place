# Summary
- This exercise is designed to help you approach, and love, merge conflict resolution.

<<<<<<< HEAD
## Exercise Three
- Similar to exercise 2, update the color for at least one column that you updated on the `atomic-commits` branch. Make sure that it's different than whatever you changed that column to within the `atomic-commits` branch.
- Want a challenge? Feel comfortable with merge conflicts? Update multiple columns.
- Want a greater challenge? Update individual rows within each column and try to make the gnarliest merge conflict that you can. Then resolve it.
- Add and commit your change to the branch.
- Type `git merge atomic-commits` in the CLI.
- Resolve the conflicts.

We'll be covering the steps of merge conflict resolution live, but here's a [video](https://www.youtube.com/watch?v=TMTDFMwU3sU&list=PLg7s6cbtAD16Pgp6WIVfX4VsGI-xyWkMz&index=11) of a resolution if you're following along outside of a workshop.
=======
**Don't make any commits until you're directed to in the instructions**

## Exercise Two
- Step one: Open your index.html file in your local browser.
- Step two: Using your text editor in the sketch.js file, change the letter `a` to the letter `b` in `column 2` starting on line 42. Should look like this:
  ![ ](./step1.png)
  - Pro tip: You can use Command + D to highlight a variable and all following instances of that variable in Atom + Sublime. You can also use Command + Option + G to highlight ALL instances of a variable. [Windows + Linux commands here.](https://www.sublimetext.com/docs/2/multiple_selection_with_the_keyboard.html)
- Step three: Using your text editor, change the letter `a` to the letter `c` in `column 3`.
- Step four through ???: Continue repetition of these steps for each variable on lines 10 - 16 until you are bored. Add new variables to complete the whole grid if you're interested.
  - This looks like:
    - Change the letter `a` to the letter `d` in `column 4`.
    - Change the letter `a` to the letter `e` in `column 5`.
    - Change the letter `a` to the letter `f` in `column 6`.
    - Change the letter `a` to the letter `g` in `column 4`.
- Step five: When your grid looks satisfactory, type `git status` to confirm that your file changes have been tracked via git.
- Step six: Type `git add -p`. Stage **only** the changes for column 2.
- Step seven: Type `git status`, and notice that you have multiple versions of the sketch.js document.
- Step eight: Commit the staged changes.
- Step nine: Repeat steps six through eight until you are bored.
>>>>>>> atomic-commits

## Next Steps
- Close any open items in your text editor.
- Type `git checkout gallery` and follow the instructions in the `instructions.md`
