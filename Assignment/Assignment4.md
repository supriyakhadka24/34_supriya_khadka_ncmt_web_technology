
**Name:** Supriya Khadka  
**Date:** 2026/01/18  
**Roll No.:** 34  
**Program:** BIT 

# CHAPTER 4: WEBSITE DESIGN PRINCIPLE

## Group A: Short Questions (2 Marks)

### 1. Differentiate between Legibility and Readability.

**Legibility:** 
- It focus in individual characters and letterforms. 
- Its goal is to make each letter distinct and easily recognizable.  
- **Examples:** Font size, spacing, and style.

**Readability:**  
- It focus on overall flow and comprehension of the text.
- Its goal is to allow the reader to process the message smoothly without getting distracted or fatigued.
- **Examples:** Line spacing, line length, and paragraph structure.

### 2.  What is the "Rule of Thirds" in layout design?

- The page is divided into three equal horizontal and vertical sections.  
- Key elements are placed at the intersections or along the lines to create balance and focus.  
- Helps guide the user’s attention naturally.

### 3. Why should you limit the number of font families used on a website?

- Using too many fonts creates visual clutter.  
- Reduces consistency and professionalism.  
- Improves readability and user experience.  
- Usually, 2–3 fonts are sufficient.

### 4. Define "Responsive Web Design"

A design approach that adapts the layout of a website according to screen size and device.  
Ensures the website looks good and functions well on desktops, tablets, and mobiles.

## Group B: Long Questions (4 Marks)

### 5. Explain the "F-Pattern" of scanning and how it influences content on a web page.

- The F-pattern is a common eye- catching behavior of users when they scan web page, especially when they read heavy text. 
- Users first read the horizontal line on the top of the page 
- Moves slightly down and read horizontally, usually shorter.
- Finally, it moves down in vertical line of the left. 


**Influence on design:**
- Important content should be placed at the top.  
- Keywords and headings should align to the left.  
- Avoid long paragraphs; use subheadings and bullet points.  
- Buttons and links should be placed on the top-left area.

### 6. Discuss the psychological impact of colors in web design. Give examples of where Blue, Red, and Green should be used. 

Colors strongly influence emotions, behavior, and decision-making.

**Psychological impact of colors:**
- Colors help to create brand identity and trust.  
- They affect mood, attention, and user actions.  
- Improve user experience and conversions.

**Examples:**

- **Blue:** Represents trust, reliability, professionalism.Creates a calm and secure feeling.
  Used in banking, corporate, and social media websites.

- **Red:** Represnets energy, urgency, excitement.Grabs attention quickly. 
  Used for call-to-action buttons, sales, alerts.

- **Green:** Represents nature, growth, health, safety. Gives a relaxing and positive feeling. 
  Used in eco-friendly, health platforms, and success messages.

### 7. Explain the "60-30-10 Rule" of color balance

The 60-30-10 rule is the design principle used to maintain visual balance and harmony in web design.

- **60% :** It is known as primary Color: It dominates the design. It is used in background and main section.  
- **30% :** It is known as secondary color: It supports primary color. It is used in menus, panels, and content area .  
- **10% :** It is known as accent color: It highlights the importance of the elements. It is used in button, links.  

**Importance:**
- Prevents color overload.  
- Improves readability and focus.  
- Guides users to important areas.

## Group C: Scenario-Based Questions (5 Marks)

### 8. A website loads very slowly, causing users to abandon it. Upon inspection, you find the developer used high-resolution raw images directly from a camera. Explain the importance of Image Optimization and file formats (JPEG vs PNG) to solve this.

Raw camera images are extremely large, leading to slow load times and poor user experience.

**Importance of Image Optimization:**
- Reduces file size while maintaining quality.  
- Improves page speed, SEO, and user retention.  
- Saves bandwidth and hosting costs.

**File Formats:**

**JPEG**
- Uses lossy compression  
- Best for photographs and complex color gradients.
- Produces smaller file size, faster loading.

**PNG**
- Uses lossless compression  
- Supports transparency and sharp edges.
- Larger file size, ideal for logos and icons.

**Best Practices:**
- Resize images before upload.  
- Use compression tools (TinyPNG, ImageOptim, WebP)  
- Use JPEG for photos, PNG for graphics.

### 9.	You are designing a website for a Law Firm. The client wants to use a bright yellow background with Comic sans font to look "friendly." As a web designer, critique this choice based on Color Theory and Typography principles, and suggest a better alternative.

**Issue:** Bright yellow + Comic Sans creates an informal, unprofessional look unsuitable for a law firm.

**Color Theory Critique:**
- Bright yellow is energetic but overwhelming and associated with caution.  
- Law firms require colors conveying trust and authority (navy blue, gray, burgundy).

**Typography Critique:**
- Comic Sans is casual, playful and widely criticized for lack of seriousness.  
- Legal websites require formal and legible fonts.

**Recommended Fonts:**
o	**Serif fonts (Georgia, Times New Roman) :** tradition, reliability.
o	**Sans-serif fonts (Open Sans, Lato) :** modern clarity and readability.


**Suggested Alternative:**
- **Background:** White or light gray with navy accents.  
- **Typography:** Georgia or Open Sans for professionalism.  
- **Layout:** Clean, structured, professional.

### 10.	A website looks great on a laptop but is unreadable on a mobile phone because the user has to zoom in and scroll horizontally. Identify the design principle missing here and explain how Media Queries/Fluid Grids could fix it.

	Website lacks adaptability across devices, forcing zooming and horizontal scrolling.

**Missing Principle:** Responsive Web Design

**Explanation:**
- Ensures adaptability across devices  
- Prevents horizontal scrolling and zooming

**Media Queries:**
- CSS rules that apply styles based on device screen width, height, or orientation.

**Media Queries Example:**

```css
@media (max-width: 600px) {
  body { font-size: 14px; }
  .container { width: 100%; }
}
```

**Fluid Grids:**
- Use percentages instead of fixed pixels  
- Elements scale proportionally

**Flexible Images:**
- Images resize within containers to prevent overflow

**Solution:**
- Use responsive frameworks (Bootstrap, CSS Grid)  
- Test across multiple devices

