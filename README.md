## Welcome! 👋

This project is a solution to the QR code component challenge on Frontend Mentor, extended with a custom landing page and a grid layout demonstration.

### Project Overview

**Functionality**

The website serves as a showcase for a QR code card component. It features a central **Landing Page** that directs users to two distinct implementations:

*   **Single Card View**: A standalone page displaying the component in isolation, centered on the screen.

*   **Grid Layout View**: A page displaying multiple instances of the component arranged in a responsive grid structure.

Both views include a navigation button to easily return to the Home screen.

**Behavior**
*   **Responsive**: The layout adapts seamlessly to different screen sizes. The grid view specifically shifts from a multi-column layout to a single column on devices with widths smaller than 1000px.

*   **Interactive**: Elements are engaging with cards and smooth navigation buttons that lift the elements and deepen their shadows, providing responsie feedback.

**Look-and-Feel**
A clean, modern aesthetic with the "Outfit" typeface and a soothing color palette of Slate Blue ![Slate 900](https://placehold.co/15/1F314F/1F314F) and White <img src="https://placehold.co/15/FFFFFF/FFFFFF" style="border: 1px solid #333; width: 15px; height: 15px; vertical-align: text-top;">.

The interface relies on card-based UI patterns with soft rounded corners and gentle drop shadows, creating a polished and professional appearance.

See the [Style Guide](style-guide.md) for detailed design specifications.
<br>

**Technologies:**

HTML, CSS, and [Mermaid.js](https://www.mermaid.ai) for diagramming.

## The challenge

The Frontend Mentor challenge is to build a QR code component and get it looking as close to the pictures of the following designs: 

### Challenge 1: Single QR Code

<figure>
    <img src="./design-preview/desktop-design-single-qrcode.jpg" style="width:15em; height:auto;"> <alt="QR Code Desktop design image.">
<br>
<Figure-caption>Figure 1. Desktop QR Code design</figure-caption>
</figure>

<figure>
    <img src="./design-preview/mobile-design-single-qrcode.jpg" style="width:15em; height:auto;"> <alt="QR Code Mobile design. image.">
<br>
<Figure-caption>Figure 2. Mobile QR Code design.</figure-caption>
</figure>
<br>

### Challenge 2: Multiple QR Codes

<figure>
    <img src="./design-preview/desktop-design-multi-qrcodes.jpg" style="width:15em; height:auto;"> <alt="QR Code Desktop design image.">
<br>
<Figure-caption>Figure 1. Desktop QR Code design</figure-caption>
</figure>

<figure>
    <img src="./design-preview/mobile-design-multi-qrcodes.jpg" style="width:15em; height:auto;"> <alt="QR Code Mobile design. image.">
<br>
<Figure-caption>Figure 2. Mobile QR Code design.</figure-caption>
</figure>
<br>

## Website Structure

```mermaid
graph LR
    root["QR-Codes"]
    
    %% Files in root
    root --> index["index.html"] --> card["card.html"]
    root --> index["index.html"] --> grid["grid.html"]
    root --> readme["README.md"]
    root --> styleguide["style-guide.md"]
    root --> changelog["CHANGELOG.md"]

    %% Directories
    root --> assets["assets"]
    root --> images["images"]
    
    %% Assets Structure
    assets --> css["css"]
    css --> maincss["main.css"]
    css --> gridcss["grid.css"]
    css --> landingcss["landing.css"]

    %% Images
    images --> img1["image-qr-code.png"]
    images --> img2["favicon-32x32.png"]
    images --> img3["favicon-single.svg"]
    images --> img4["favicon-grid.svg"]
```

All the **required assets** are in the `/assets` and `/images` folder. (Images are optimized.)

Use best judgment for displaying JPG files. e.g. `font-size`, `padding` and `margin`. 

The `style-guide.md` contains the color palette and fonts specifications.

## Website

<a href="https://LeoLinkDev.Github.io/QR-Codes">
    <img src="./images/landing.jpg" alt="Landing Page Screenshot" style="width:100%;">
</a>

* [GitHub repo](https://LeoLinkDev.Github.io/)


