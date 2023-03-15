Notes on Flex

display:flex should be put on the parent container and only affects its immediate children.

list of commands to put on parent container css:

display: flex
justify-content: center left right ... (aligns on main axis)
align-items (aligns on cross axis)
gap: something px (puts a gap between children in pixels)
max-width: 200px; (restricts element to a particular width)
flex-shrink:0; (makes it so element can't shrink)
flex: 1 (makes item fill up available space)

Useful non flex stuff:
align-text: center;
margin-bottom: 20px; (make margin on the bottom only)
font-weight: bold; 
font-size: 18px;
list-style-type: none; (removes bullet points from list)
height: 100vh; (makes container height same as viewport, so that flex can work with column direction)
a {
  color: #666;
  text-decoration: none;
}
ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  gap: 16px;
} (lists have automatic margin and padding, so this gets rid of it)



