# Yiddish-m17n
A Yiddish m17n layout for Unix/Linux optimized for letter/ligatures frequencies and desktop publishing.

This input method for Yiddish based on the traditional typewriter layout, which also serves as the base of modern Hebrew layouts. Unlike most other Yiddish layouts, which are either phonetical or based on randomly chosen ligature assignments, this method takes into consideration frequency of letters and ligatures in actual Yiddish texts. 

For the sake of compatibility with some software, especially Adobe Indesign (non-existent used Unix, but broadly taken as an industry standand) standard Yiddish ligatures are provided as character combinations and not as single Unicode characters. In some cases such rendering is beneficial for Scribus too.

To install, put the file in your m17n database directory and restart your Ibus or Scim. For Ibus, you can also run the following command:

ibus-daemon -d --xim --cache refresh

