# Theming Notes

_These notes are from learning about VSCode features in order to theme them_

## Highlights

- **Current line highlight:** Current line highlight uses a low opacity so that
  it doesn't interfere with content. It is displayed for the line the cursor is
  in and creates the "base" highlight.
- **Current range highlight:** Highlights ranges of current matches, including
  the currently selected match for find and currently selected symbol in Go to
  symbol. Color is similar to line highlight, just slightly brighter because it
  is more active. No border is included.
- **Current selection highlight:** The current selection highlight uses a
  lighter purple to allow for better contrast of selected text while not being
  overwhelming for multiline selections. When selecting text, additional matches
  are highlighted with a subtler background and border of the same shade. The
  border is not an opacity to provide a base for layering other highlights on
  top of (such as the symbol access).
- **Find highlights:** Most bold to make it easy to see fin matches Has to
  overlay the current selection border...
- **Symbol access highlights:** VSCode highlights read and write access to
  symbols. This is themed with lighter colors using opacity because they often
  appear at the same time as the current selection highlight
- **Snippets highlights:** Coming soon!

## Bracket matching

Need a set of colors that can be mixed with background to provide a toned down
bracket match experience that works with the theme.

- #f600bb
- #ff00fc
- #fd43cd
- #d043cf
- #ba01ff
- #ff55fd
- #874df8

- #efe900
- #ffc400
- #ff8200
- #ff5300

- #78efc5