# Mental Health Awareness

## Goal

The goal of this website is to provide **accessible, beginner-friendly information on mental health**. It aims to help users recognize common mental health issues and manage stress, all presented in a supportive and organized layout.

---

## AI-Assisted User Story Generation

To streamline the planning process, I used **ChatGPT** to generate several user stories. After reviewing and refining these stories to fit the project scope, I also used ChatGPT to generate acceptance criteria and tasks for each story. This approach significantly reduced the time required to develop user stories, criteria, and tasks.

All user stories were added to the GitHub project board and organized using **"must have," "should have," and "could have"** labels for clarity and prioritization.

---

## AI Palette Verification

I used ChatGPT to check if the color palette I created for the design of the page fit a calm and relaxing feel that is user friendly. This was the outcome of that question:

> **Here's a quick breakdown of the colors from your Coolors link:**
>
> - `#F1E0C5` – a warm, creamy beige  
> - `#C9B79C` – a soft, muted taupe  
> - `#7B6D8D` – a dusty lavender/gray-purple  
> - `#342A21` – a deep, earthy brown  
> - `#BEA7E5` – a gentle, pastel lilac
>
> **Does it invoke a calm feel?**
>
> Yes, it does. Here's why:
>
> - **Muted tones:** None of the colors are overly saturated, which contributes to a sense of tranquility and softness.
> - **Warm neutrals** (`#F1E0C5`, `#C9B79C`, `#342A21`): These earthy tones ground the palette and evoke comfort and calm.
> - **Soft purples** (`#7B6D8D`, `#BEA7E5`): Purples, especially in dusty or pastel tones, tend to feel introspective, serene, and slightly dreamy.
>
> **Overall Vibe:**  
> This palette feels like a quiet moment at dusk—warm light fading into cool shadows. It could easily be used for themes of reflection, gentle fantasy, nostalgia, or cozy minimalism.

---

## Image Creation and Integration

To maintain a cohesive and calming visual theme, I used GitHub Copilot’s AI-powered image generation to create a set of custom images for the website. This ensured that all visuals consistently reflect the site’s purpose—promoting mental health awareness in a supportive and soothing manner.

Each image was designed to complement the chosen color palette, emphasizing soft, tranquil tones that align with the overall aesthetic. This approach helps unify the site’s imagery, layout, and colors, resulting in a harmonious and inviting user experience. The custom images not only enhance visual appeal but also reinforce the site’s message of calm, clarity, and encouragement.

### Custom Images Created

- ![Anxiety illustration](assets/images/anxiety.png)
- ![PTSD illustration](assets/images/ptsd.png)
- ![Depression illustration](assets/images/depression.png)
- ![Imposter syndrome illustration](assets/images/impostersyndrom.png)
- ![Site logo](assets/images/logomh.png)
- ![Hero section image](assets/images/mentalhero.png)

Additionally, each carousel background was custom-generated to match the site’s theme, such as:

- ![Carousel background example](assets/images/carousel1.png)
---
### Wireframes

Based on the user stories generated with ChatGPT, I designed wireframes for the site, starting with a **mobile-friendly layout**:

![Mobile wireframe preview](assets/images/mobileversion.png)

Afterwards, I quickly created a **desktop (web) version** of the wireframe:

![Desktop wireframe preview](assets/images/webpageversion.png)

As the development progressed, some design elements evolved beyond the initial wireframes. To ensure the wireframes accurately reflected the updated look and feel of the site, I revised them to match the emerging design direction. Below are the updated wireframes, which incorporate these adjustments:

![Mobile wireframe 1.2 preview](assets/images/Mobile%20Version%201.2.png)

![Desktop wireframe 1.2 preview](assets/images/webpage%20version%201.2.png)

---

## Deployment

To deploy this website using **GitHub Pages**, follow these steps:

1. **Open your repository on GitHub.**
2. Click on the **Settings** tab at the top of the repository page.
3. In the sidebar, select **Pages**.
4. Under **"Branch"**, choose `main` as the source branch and set the folder to `/ (root)` or `/docs` (depending on where your `index.html` is located).
5. Click **Save**.
6. Wait a few moments for GitHub Pages to build and deploy your site.  
    - A link to your live website will appear at the top of the Pages settings once deployment is complete.


---
## Code Validation

After completing the minimum viable product, I used the [W3C Markup Validation Service](https://validator.w3.org/) to check the HTML code for errors. The initial validation revealed several issues, as shown below:

![Validation errors screenshot](assets/images/error%20during%20validation.png)

I promptly addressed these errors and revalidated the code. The updated validation confirmed that all issues had been resolved:

![Passing validation screenshot](assets/images/passing%20validation.png)

---

## Features

- Beginner-friendly mental health information and resources
- Calming, accessible design with a soothing color palette
- Mobile-first, fully responsive layout for all devices
- Custom AI-generated images tailored to the site’s theme
- User stories and planning powered by AI for clarity and focus
- Easy navigation and organized content structure
- Quick start: no build steps, just open `index.html`
- Helpful links to mental health support organizations
- Regularly updated wireframes reflecting design improvements
- Open-source and easy to contribute to

---

## Technologies Used

- HTML5 & CSS3
- Bootstrap 5
- AI tools: ChatGPT (user stories, palette), Copilot (images)

---

## Known Issues

- On mobile and tablet devices, after selecting an item from the dropdown menu, the menu does not automatically close. This causes it to remain open and cover the section title, resulting in a UI issue.

## Roadmap

- Add more mental health topics
- Expand resource links
- Add language/localization support
- Add a self check form page

---

## Credits

- [Jacob Smith] (https://github.com/JakeSoGreat)
- AI tools: ChatGPT, GitHub Copilot
- Livewell Southwest: https://www.livewellsouthwest.co.uk/inpatient-mental-health-neurology/first-response-24-7-helpline
- My Therapist: https://www.mytherapistonline.co.uk/
- NHS 111: https://111.nhs.uk/guided-entry/mental-health-help
- Devon Mind: https://www.devonmind.com/find-help/groups
- Mental Health Foundation: https://www.mentalhealth.org.uk/explore-mental-health/articles
- Nation Library of Medicine: https://www.ncbi.nlm.nih.gov/books/NBK470361/, https://www.nimh.nih.gov/health/topics/depression, https://www.ncbi.nlm.nih.gov/books/NBK559129/, https://www.ncbi.nlm.nih.gov/books/NBK585058/
