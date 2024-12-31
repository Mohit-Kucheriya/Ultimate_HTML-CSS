1. The CSS is written in a file with the extension .css

2. Three ways to style an element:

   a. Inline style
   b. Internal style
   c. External style

3. To apply any style to an element, you need to select it using a selector

   Syntax -
   h1{
   color: red;
   }

4. We can select an element using:
   a. Element selector (tag name)
   b. Class selector (.class-name)
   c. ID selector (#id-name)

5. The order of importance of selectors is:

   a. ID
   b. Class
   c. Element

6. When we use pseudo classes, like first-child, we are selecting the first child of the element i.e. the first element inside the parent element.

7. Using pseudo classes for the anchor tag is a good practice because it helps us to style the link in a different way i.e. we can specify if the anchor tag has the "href" attribute then only it will get styled.

   Syntax -
   a:link {
   color: red;
   }

8. Difference between '*' and 'body'
   '*' means all elements, no inheritance involves
   'body' whatever properties are defined in the body tag get's inherited to all the elements
