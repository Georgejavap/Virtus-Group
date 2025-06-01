# Virtus Group Website

Welcome to the Virtus Group website — a futuristic, high-concept web platform built for a next-generation fitness facility. This project showcases an immersive digital presence reflecting Virtus Group’s innovative approach to fitness, wellness, and virtual integration.

---

## Project Overview

Virtus Group is a concept gym brand offering AI-powered fitness pods, smart wearables, virtual coaching, and community events. This website serves as both a showcase and interactive portal with various protected member-only sections, a dynamic blog, event widgets, and a Typeform consultation trigger. We also have some great location across the UK, were aiming to integrate online coaching, AI and in perosn gym classes to great the best fitness community in england.

---

## Technologies Used


### Front-End
- **HTML5**: Semantic markup with consistent structure
- **CSS3**: Flexbox layout, responsive design, custom styling
- **JavaScript**: DOM manipulation, modal control, smooth scrolling

### Interactive Features
- Modal pop-ups for consultations and support
- Login-protected widget revealing member resources
- Section-based navigation with smooth scroll and offset adjustment
- Auto-triggered promotional Typeform modal after 10 seconds

### External Integrations
- Typeform (consultation survey)
- Google Maps (location embed)
- Spotify (mental wellbeing podcast)
- BBC Good Food, Muscle & Fitness, Darebee (resources and challenges)


---

## File Structure

project-root/
├── index.html                         
├── styles.css                         
│
├── /header-content/                  
│   └── Logo.png                       
│
├── /home-widget-1/
│   └── widget-video.mp4            
├── /home-widget-2/
│   └── widget-video.mp4               
├── /home-widget-3/
│   └── widget-video.mp4               
│
├── /home-icon-content/                
│   ├── dumbbell.gif
│   ├── stopwatch.gif
│   ├── bicep.gif
│   ├── heart-rate.gif
│   └── brain-focus.gif
│
├── /resources-front-video/          
│   ├── resources-background.mov      
│   └── resources-background-landscape.mov  
│
├── /resources-content/               
│   ├── image1.png                    
│   ├── image2.png                     
│   ├── image3.png                     
│   ├── image4.png                    
│   ├── image5.png                    
│   ├── image6.png                     
│   ├── image7.png                   
│   ├── image8.png                     
│   └── image9.png                    
│
├── /blog-content/                    
│   ├── blog-1.jpeg                   
│   ├── blog-2.jpeg                  
│   └── blog-3.jpeg                   
│
├── /Events-front-content/          
│   ├── hyrox.mov
│   ├── ultrax.mov
│   └── 220-Tri.mov
│
├── /hyrox-widget-events/            
│   ├── image-1.png                   
│   ├── image-2.png                   
│   ├── image-3.png                   
│   └── image-4.png                   
│
├── /ultra-x-widget-events/          
│   ├── image-1.png                   
│   ├── image-2.png                   
│   ├── image-3.png                   
│   └── image-4.png                   
│
├── /220-widget-events/              
│   ├── image-1.png                   
│   ├── image-2.png                   
│   ├── image-3.png                   
│   └── image-4.png                  
│
├── /Footer-content/                 
│   ├── instagram.png
│   ├── facebook.png
│   └── twitter.png
│
├── /Documents/                      
│   ├── Virtus-group-Operations-overview.docx    
│   ├── Virtus_Group_Privacy_Policy.pptx          
│   └── Virtus_Group_Cookies_Policy.pptx          


---

## Demo Login for Protected Widget

To preview protected resources, use:

```
Username: 1
Password: 2
```

---

## UX & Design Rationale

The design follows current UX standards:

- **Information hierarchy**: Clear section headers, content groupings, and navigation structure
- **User control**: No audio autoplay, modals can be exited easily, login validation
- **Consistency**: Repeated structure in widgets, color use, button feedback
- **Accessibility**: Semantic HTML, alt text on images, responsive design, muted media
- **Confirmation**: Modals, protected login feedback, interaction highlights

Design decisions were made with real gym users in mind—supporting clarity, engagement, and trust.

---


## Attributions & References

### HTML/CSS Design Assistance
- **CSSDeck**: Conceptual inspiration for flex-based layouts and card styles  
- **ChatGPT**: Provided real-time suggestions and code snippets for layout enhancements, animations, and responsive grid design  

### JavaScript & Interactivity
- **ChatGPT DevCommunity**: Guidance on structuring interactive behavior such as modal display, protected content toggles, and widget closure  
- **Stack Overflow**: Code validation, event listener best practices, browser compatibility tweaks  
- **Jon Duckett — JavaScript & jQuery**: Referenced for foundational JS knowledge, form validation, and DOM scripting patterns  
- **Personal Research**: Self-taught JavaScript patterns and enhancements through experimentation and community tutorials  

### AI & Documentation
- All JavaScript, layout structuring, and responsive behavior were partly shaped by **ChatGPT (OpenAI)**, used to accelerate learning and iterate solutions with accuracy  


---

## Features

- Dynamic modal popups for booking & contact
- Protected resource portal with basic login gate
- Responsive video banners and widget integration
- Timeline visual of company history
- Interactive event widgets using `<details>` + `<summary>`
- Embedded Google Maps for physical location reference

---

## Testing Evidence

Below is visual proof of the key testing stages.

### HTML Validation Pass
![HTML Validation](docs/validation/html-validator.png)

### CSS Validation Pass
![CSS Validation](docs/validation/css-validator.png)

### Protected Widget Login Success
![Login Widget](docs/validation/login-success.png)

### Modal Interaction Test
![Modal Open](docs/validation/modal-open.png)  
![Modal Open Alternate](docs/validation/modal-open-1.png)

### Mobile View Tests
![Mobile View 1](docs/validation/responsive-mobile.png)  
![Mobile View 2](docs/validation/responsive-mobile-1.png)  
![Mobile View 3](docs/validation/responsive-mobile-2.png)  
![Mobile View 4](docs/validation/responsive-mobile-3.png)  
![Mobile View 5](docs/validation/responsive-mobile-4.png)

### Desktop View Tests
![Desktop View 1](docs/validation/responsive-desktop.png)  
![Desktop View 2](docs/validation/responsive-desktop-1.png)  
![Desktop View 3](docs/validation/responsive-desktop-2.png)  
![Desktop View 4](docs/validation/responsive-desktop-3.png)


## 🎨 Project Display Note

While developing this project, my goal was to create a polished and fully responsive events section, with smooth full-screen overlays, centered content, and clean layout transitions — as shown in my development environment screenshots.

However, due to limitations with GitHub Pages and how it handles rendering and styling updates (particularly with some CSS rules and layout behaviors), I wasn't fully able to replicate the final look as seen locally. Some elements, such as the expanded event widget overlays and centered text alignment, did not render exactly as expected once deployed.

Despite multiple commits and refinement attempts, the live version on GitHub Pages fell slightly short of the intended finish. This project still demonstrates the key functionality and design direction I was working toward, and the screenshots included represent the more accurate, polished version I achieved in my local environment.

> ⚠️ _Note: If certain layouts appear slightly off on GitHub Pages, please refer to the provided screenshots for the original intended design._

---


## Future Plans

- Integrate real-time booking APIs
- Connect Typeform consultation form for dynamic entry
- Enhance member portal with OAuth-based login
- Add backend CMS for blog & events updates

---

## Contact


**Email**: virtusgroupgyms@gmail.com  
**Project by**: George Baldwin  
**Web Design:** George Baldwin

--- 


Thank you for exploring the **Virtus Group Gym Project**   
Built with passion, purpose, and precision.
# Virtus-group