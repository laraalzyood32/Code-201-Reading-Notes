# layout
This involves learning about how designing for a screen can be different to designing for other mediums  print).
in this chapter we will:
1. Explore different ways to position elements using normal flow, relative positioning, absolute positioning and floats.
2. various devices have different screen sizes and resolution, and how this affects the design process.
3. Learn the difference between fixed width and liquid layouts, and how they are created.
4. Find out how designers use grids to make their page designs look more professional.

# Building Blocks :
## 1.CSS treats each HTML element as if it is in its own box. This box will either be a block-level box
 or an inline box.

## 2.Containing Elements If one block-level element sits inside another block-level element then the outer box is
known as the containing or parent element.

## Position of Elements :
### CSS has the following positioning schemes that allow you to control the layout of a page:
1. NORMAL flow : Every block-level element appears on a new line, causing each item to appear lower down
the page than the previous one.
2. Relative Positioning This moves an element from the position it would be in normal flow, shifting it 
to the top, right, bottom, or left of where it would have been placed.
3. absolute positioning : This positions the element in relation to its containing element. It is taken out of
normal flow, meaning that it does not affect the position of any surrounding elements
4.Fixed Positioning : It positions the element in relation to the browser window. Therefore, when a user scrolls down the page, it stays in the exact same place
### You specify the positioning scheme using the position property in CSS.or you can use float 
5. float elements using the float property.Anything else that sits inside the containing element will
flow around the element that is floated
A lot of layouts place boxes next to each other. The float property is commonly used to achieve this

# box offset properties : to tell the browser how far from the top or bottom and left or right it should be placed.
# To indicate where a box should be positioned .
# z-index property : allows you to control which box appears on top.

# Clearing floats : The clear property allows you to say that no element (within the same containing element)
should touch the left or right hand sides of a box. It can take the following values:
### 1. left : The left-hand side of the box should not touch any other elements appearing in the same containing element.
### 2. right :The right-hand side of the box will not touch elements appearing in the same containing element.
### 3. both : Neither the left nor right-hand sides of the box will touch elements appearing in the same
containing element.
### 4.none : Elements can touch either side.. The CSS rule for this class uses the clear property
to indicate that nothing should touch the left-hand side of it

# Screen Sizes :
Different visitors to your site will have different sized screens that show different amounts of information, so your design needs to be able to work on a range of different sized screens.
# Screen Resolution :
Resolution refers to the number of dots a screen shows per inch. Some devices have a higher resolution than desktop 
computers and most operating systems allow users to adjust the resolution of their screens .

# Page Sizes :
Because screen sizes and display resolutions vary so much, web designers often try to create pages of around 960-1000 pixels wide .

# 1.Fixed Width Layouts :
do not change size as the user increases or decreases the size of their browser window. Measurements tend
to be given in pixels.
## 1.1  Advantages                                                                        
1. Pixel values are accurate at controlling size and positioning of elements.
2. The designer has far greater control over the appearance and position of items on the page than with liquid layouts.
3. You can control the lengths of lines of text regardless of the size of the user's window.
4. The size of an image will always remain the same relative to the rest of the page.
## 2.1  Disadvantages
1. You can end up with big gaps around the edge of a page.
2. If the user's screen is a much higher resolution than the designer's screen, the page can look smaller and text can be harder to read.
3. If a user increases font sizes, text might not fit into the allotted spaces.
4. The design works best on devices that have a site or resolution similar to that of desktop or laptop computers.
5. The page will often take up more vertical space than a liquid layout with the same content.

# 2.Liquid Layouts :
Liquid layout designs stretch and contract as the user increases or decreases the size of their browser
window. They tend to use percentages.
## 2.1  Advantages
1. Pages expand to fill the entire browser window so there are no spaces around the page on a large screen.
2. If the user has a small window, the page can contract to fit it without the user having to scroll to the side.

## 2.2  disAdvantages :
1. If the user has a wide window, lines of text can become very long, which makes them harder to read.
2. If the user has a very narrow window, words may be squashed and you can end up with few words on each line.

# 3.CSS Frameworks :
CSS frameworks aim to make your life easier by providing the code for common tasks, such as creating layout grids, styling forms .
##  3.1 Advantages :
1. They save you from repeatedly writing code for the same tasks.
2.  They will have been tested across different browser versions (which helps avoid browser bugs )

## 3.2  disAdvantages :
1. They often require that you use class names in your HTML code that only control the presentation of the page
2. In order to satisfy a wide variety of needs, they often contain more code than you need for your particular web
page .

# <div> elements are often used as containing elements to group together sections of a page.
# Grids help create professional and flexible designs.
# CSS Frameworks provide rules for common tasks.

*****************************
# quiz :
1. what are the positioning schemes that allow you to control the layout of a page ?
2. what is the screen resolution ?
3. how many types of layout ?
4. what the advantages and disadvantages of each type ?


