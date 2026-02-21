# Web Design for Web Developers: Build Beautiful Websites!

## Guidelines

### Typography

Typography is the art and technique of arranging type to make written language legible, readable, and visually appealing.

1. Use a font size between 15 and 25 pixels.
2. Use really big fonts for headlines and titles
3. Use line spacing between 120% and 150%
4. Use 45 to 90 charatcers per line
5. Use good loking fonts

#### Sans-serif

1. More neutral
2. Clean
3. Simple
4. Modern

#### Serif

1. Traditional
2. Storytelling
3. Long reading

#### Fonts

- Open Sans
- Lato
- Raleway
- Monsterrat
- PT Sans

### Colors

1. Use only one base color with darker and light versions of base one
2. Use color picker for more colors
3. Use colo to draw attention
4. Never user black color in design
5. Choose colors wisely

### The Meaning Of Colors In Web Design

Picking a color for a website means more then picking your favorite color and turning it into a design. It means picking the right color in order to get the desired response from your audience. Color really makes a difference. This happens because there are psychological effects behind each color.

- **Red** is a great color to use when power, passion, strength and excitement want to be transmitted. Brighter tones are more energetic and darker shades are more powerful and elegant.
- **Orange** draws attention without being as overpowering as red. It means cheerfulness and creativity. Orange can be associated with friendliness, confidence, and courage.
- **Yellow** is energetic and gives the feeling of happiness and liveliness. Also, it associates with curiosity, intelligence, brightness, etc.
- **Green** is the color of harmony, nature, life and health. Also, it is often associated with money. In design, green can have a balancing and harmonizing effect.
- **Blue** means patience, peace, trustworthiness, and stability. It is one of the most beloved colors, especially by men. It is associated with professionalism, trust and honor. That's actually why the biggest social networks use blue.
- **Purple** is traditionally associated with power, nobility and wealth. In your design, purple can give a sense of wisdom, royalty, nobility, luxury, and mystery.
- **Pink** expresses romance, passivity, care, peace, affection, etc.
- **Brown** is the color of relaxation and confidence. Brown means earthiness, nature, durability, comfort, and reliability.

### Images

- Put text directly on image (with dark images)
- Overlay on image
- Grdient overlays
- Put text in a box with transparency
- Blur image for text
- Floor fade (to black)

### CSS for images

To achieve the text-on-image effects I showed you before, you can use CSS for your websites. Here is example CSS code for some of the effects. Please change it according to your needs.

[Overlay the image](https://jsfiddle.net/drpak8vy/1/)

```css
.darken {
  background-image:
    linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)),
    url(YOUR IMAGE HERE);
}
```

[Put text in a box](https://jsfiddle.net/qg83m36p/)

```css
.text-box {
  background-color: rgba(0, 0, 0, 0.5);
  color: #fff;
  display: inline;
  padding: 10px;
}
```

[Floor fade](https://jsfiddle.net/gRzPF/409/)

```css
.floor-fade {
  background:
    linear-gradient(to bottom, rgba(0, 0, 0, 0), rgba(0, 0, 0, 0.6)),
    url(YOUR IMAGE HERE);
}
```

### Icons
