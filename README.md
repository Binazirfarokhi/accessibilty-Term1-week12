# accessibilty-Term1-week12

“Accessibility in web design is like building a ramp next to the stairs — it helps everyone access the same place, just in different ways.”
Know someone who wears glasses or has dyslexia?
Have you ever used your phone in bright sunlight and struggled to see the screen?

some people has : 
Cognitive Impairments
Learning Disabilities (ADHD, dyslexia)
Mental Illnesses
General difficulties with memory and understanding

Hearing Impairments
Partial hearing loss
Complete hearing loss

straw - test 


____________
Semantic HTML	:
Use correct tags like <nav>, <main>, <section> instead of <div> for everything. Helps screen readers.	

Alternative Text (Alt Text)	Add alt="" to images so screen readers can describe them to blind users.	Use an image with good and bad alt text, show how screen readers read them.

Keyboard Navigation	Make sure you can tab through buttons and links.	

Color Contrast	Ensure text is readable even for color-blind users.	Use  contrast-ratio.com on real examples.

Responsive Design for Mobile	Ensure zooming, readable text, and accessible touch targets on small screens.	Use DevTools to show mobile view. Demonstrate how small buttons are hard to tap.
____
Tips for accessibility : 
1.Use viewport meta tag properly.

3.Make sure buttons and links are large enough (48x48px recommended).

4.Use accessible form labels and inputs (<label for="name">Name</label>).


6. Use Descriptive Links
Avoid: <a href="#">Click here</a>
Better: <a href="/apply">Apply for the program</a>
Why: Screen reader users often navigate by links only — unclear links confuse them.

7. Headings Should Be Hierarchical
Use <h1> to <h6> in logical order — never skip levels (e.g., don’t jump from <h1> to <h4>).

8.Use only one <h1> per page.

Helps users scan content more easily and improves SEO.

9.<table>
  <thead>
    <tr><th scope="col">Name</th><th scope="col">Age</th></tr>
  </thead>
  <tbody>
    <tr><td>Alice</td><td>24</td></tr>
  </tbody>
</table>
Use scope="col" or scope="row" in <th> tags to help screen readers.
----------
screen reader for chrome and open the tools and try to use it and then you will turn it off
----------

  introduce to dom : there is a video that Tomoko explain how to turn on and turn off the menu,
10.7. Don’t Rely on Hover Effects
Mobile devices don’t support hover

Always provide clickable alternatives.
______________-
