# save-css-in-devtools
How to save CSS modifications in Chrome Devtools

Inside Devtools:
1) Decide which stylesheet to modify.
2) Make any desired changes in the Elements/Styles panel.
3) Navigate to the associated stylesheet in the Sources panel.
4) Right-click anywhere inside the modified code, and click "Save-as."
5) Save to a local destination. (Change the name, if desired, for easy identification. Example: style.css => style-modified.css)
6) Bonus: You can right-click inside the modified code in the Sources panel and select "Local Modifications" to display all of your changes neatly inside Devtools.

Once saved, compare code changes side-by-side in Visual Studio Code:

Inside VSCode:
1) Open the modified file along with the original.
2) Inside the VS Explorer (CTRL+SHIFT+E), right-click the modified file and choose "Select for Compare."
3) Also inside the Explorer, right-click the original file and choose "Compare with Selected."
4) View your compared changes.
