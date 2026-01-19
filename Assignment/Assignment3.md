
**Name:** Supriya Khadka  
**Date:** 2026/01/18  
**Roll No.:** 34  
**Program:** BIT  

# CHAPTER 3: WEBSITE STRUCTURE DESIGN

## Group A: Short Questions (2 Marks)

### 1. Define Information Architecture (IA).
Information Architecture (IA) is the process of organizing, structuring, and labeling website content so that users can easily find information and navigate the site effectively. 
IA is used everywhere, from the aisle layout in a grocery store (snacks together) to the clear sections on a website (Blog, Resources, Pricing).

### 2. What is a Wireframe?
A wireframe is a basic visual layout of a webpage that shows the structure, content placement, and functionality without colors, images, or detailed design. 
It uses simple shapes, lines, and grayscale to show where elements like navigation, content areas, and buttons go.

### 3. Explain the concept of Cognitive Friction in web design.
Cognitive friction refers to the mental effort required by users when a website is confusing, complex, or hard to understand, which reduces usability and user satisfaction.

### 4. Why should URL slugs use hyphens instead of underscores?
Hyphens are preferred because search engines read hyphens as word separators, improving SEO and readability, while underscores are treated as word connectors.

## Group B: Long Questions (4 Marks)

### 5. Compare and contrast Hierarchical (Tree) structure and Linear (Sequential) structure. Give examples.

**Hierarchical structure:**  
- It organizes content in a tree-like structure in which the main topic is on top and subcategories branch below. 
- It is flexible. 
- Users can jump between different branches. 
- It is complex if there are many branches. 
- Suitable for large website with many branches. 
- **Example:** E-commerce websites with categories and products.

**Linear structure:**  
- It organize content in straight step by step, one on another. 
- It is limited. 
- Navigation are sequential and have to follow step.
- It is simple to use. Suitable for step by step process. 
- **Example:** Online tutorials and step-by-step forms.

### 6. Explain the “Three-Click Rule” and its significance in UX design.
The Three-Click Rule states that users should be able to find any information on a website within three clicks.

**Significance in UX Design:**
- It improves usability by making information easy to locate.
-	It reduces user frustration and cognitive load.
-	It saves time and effort for users.
-	It encourages users to stay longer on the website.
-	It helps in designing clear navigation menus and proper information hierarchy.
-	It supports better user satisfaction and engagement.
-	It contributes to lower bounce rates and better overall UX.


### 7. “Plan before you do.” Explain how Card Sorting and Flowcharts help in website planning.

The statement emphasizes the importance of planning before website development.

**Card Sorting:**  
A technique used to organize content logically. Content items are written on cards and grouped by users or designers.

**Importance:**
- Helps understand how users expect information to be grouped.
- Improves website usability and navigation.
- Reduces confusion and makes the site easy to use.
  
**Example:** Grouping Home, About Us, Services, Contact for menu design.

**Flowcharts:**  
A diagram showing step-by-step flow of pages. Uses symbols like rectangles and arrows. Shows how users move from one page to another. Represents decision points and processes.

**Importance:**
- Provides a clear visual structure of the website.
-	Helps developers understand page sequence.
- Reduces errors during development.


**Example:** Home → Login → Dashboard → Logout.

## Group C: Scenario-Based Questions (5 Marks)

### 8.	You are designing a website for a University. It has hundreds of pages (Admissions, Departments, Alumni, News). Which structural model would you choose? Draw a rough diagram and justify your choice.
For a university website with hundreds of pages, a Hierarchical (Tree) Structure is most suitable.
- The Hierarchical structure organizes information in a parent–child relationship, starting from a main page (Home) and branching into categories, subcategories, and individual pages. Users navigate from general information to more specific information.

**Reasons:**
1. **Handles large content efficiently:** University websites have hundreds of pages. Hierarchical structure allows systematic organization of content into sections and sub-sections.

2. **Easy navigation for different users:** Users such as students, teachers, parents, and alumni can quickly locate information. Clear menus reduce confusion and cognitive load.

3. **Logical information flow:** Content flows from: University → Faculty → Department → Course
This matches how users naturally think and search.

4. **Scalable and flexible:** New departments, courses, or notices can be added easily without redesigning the entire website.
 
5. **Better UX:**Improves usability and reduces frustration. Users can reach desired pages in fewer clicks.
   
6. **SEO-friendly:** Search engines can easily crawl and index structured content. Improves visibility in search results. 

```
Home
 ├── Admissions
 ├── Faculties
 │    ├── Science
 │    ├── Management
 │    └── Arts
 ├── Departments
 ├── Alumni
 └── News
```

### 9. A user visits a website but leaves within 10 seconds because they cannot find the navigation menu, which is hidden behind a small icon on a desktop screen. Analyze this design failure using the “KISS (Keep It Simple)” principle.

The KISS principle in web design emphasizes simplicity, clarity, and ease of use.
Hiding the navigation menu behind a small icon on desktop violates the KISS principle.

**Problems:**
- **Increased cognitive friction:**
    • Hidden navigation forces users to think, guess, or search for the menu.
    •	Users must recognize the icon, understand its purpose, and click it.
    •	This extra mental effort reduces usability and efficiency.

- **Poor discoverability:** 
    •	Small icons may go unnoticed, especially by new or non-technical users.
    •	Important navigation links are not immediately visible.
    •	Users may leave the site within seconds due to confusion.

- **Violates desktop user expectations:**
    •	Desktop users expect:
           o	Visible top navigation bars
           o Clear menus and categories
    •	Hidden menus are mainly associated with mobile interfaces, not desktops.

- **Higher bounce rate:**
     When users cannot find navigation quickly, they leave the website.
     This results in:
          •	Poor user experience (UX).
          •	Negative impact on engagement and conversions.


**Why KISS fails:**
- **Over-simplification reduces usability:**  
    •	Simplifying the interface by hiding navigation removes clarity.
    •	KISS promotes simple but obvious, not simple but hidden design.

- **Important elements should be visible:**
     •	Navigation is a core element of any website.
     •	According to usability principles:
         o	“Don’t make users think”
     •	Hidden menus contradict this rule.


**Solution:**
- **Use visible navigation on desktop:**
    •	Display a clear horizontal or vertical navigation bar.
    •	Label menu items with text for better understanding.

- **Use icons only when necessary:**
    •	Icons can be used:
        o	On mobile devices
        o	When screen space is limited
    •	On desktop, icons should support text, not replace it.

- **Combine simplicity with clarity:**
    •	Keep layout clean and minimal.
    •	Make navigation easy to see, easy to understand, and easy to use.
 

### 10. 10.	An e-commerce website has a URL structure like:www.shop.com/prod?id=55&cat=9.Explain why this is bad for both users and Search Engines (SEO), and propose a better structure using page slugs.
**Bad URL:**  
www.shop.com/prod?id=55&cat=9

**Problem**	
1)	**Hard to read and remember:** The URL uses codes (id=55&cat=9) instead of meaningful words, making it difficult for users to recall.
2)	**Not descriptive:** It does not tell users what the page is about. Users cannot guess the content from the URL.
3)	**Poor for SEO:** Search engines prefer URLs with meaningful keywords; this URL lacks descriptive words, which can hurt ranking.


**Improved URL:**  
www.shop.com/products/mens-shoes

**Benefits:**
- **User-friendly:** Easier for users to read, remember, and share.
-	**SEO-friendly:** Contains keywords that search engines can index, improving visibility.
-	**Descriptive:** Clearly indicates the page content, helping users understand what they will find before clicking.


