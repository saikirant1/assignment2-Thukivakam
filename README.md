# assignment2-Thukivakam
# Thukivakam Sai Kiran
#### Tirumala Tirupati Devastanam Museum

Here you can see the  old **historical** things that are  used by lord Venkateshwara swamy. This place have the different type of currencies **that** were used at time.

---
#### Directions to the musuem

The nearest airport to the meseum is Tirupati International Airport.<br>
step1 - Take a cab from airport.<br>
step2 - Get down near the Vaikuntam complex bus stand.<br>
step3 - walk for 2 minutes and you will find the museum.<br>

Places near the musuem-
- Tirupati
- Chandeagiri
- Sri Kalahasti

[Link to my About Me](https://github.com/saikirant1/assignment2-Thukivakam/blob/main/README.md)
---
### Tables
| City | Locations | Time |
| --- | --- | ---: |
| North Carolina | Pineville <br> Trails | 4 hours <br> 3 hours to whole day |
| Missouri | Kansas City | 2 hours |
| Texas | Marvel Studios <br> Hollywood Shoots | 4 hours <br> 3 Hours |

---
### Pithy quotes
>Live the moment - *Dhruv Tej* <br>
>Enjoy each and every minute of your life - *Lokesh*

---
### Code Fencing
>SVG Patterns
[Link to stack overflow](https://stackoverflow.com/questions/50283115/filling-a-rotating-circular-svg-with-a-pattern-image)
```
<svg width="100%" height="100%">
  
  <!-- Create mask that we'll use to define a slight gradient -->
  <mask maskUnits="userSpaceOnUse" id="fade">
    <!-- Here's that slight gradient -->
     	<linearGradient id="gradient" x1="0" y1="0" x2="0" y2="100%">
      <stop offset="0" style="stop-color: #FFFFFF"></stop>
      <stop offset="1" style="stop-color: #000000"></stop>
    </linearGradient>
    <!-- The canvas for our mask -->
    <rect fill="url(#gradient)" width="100%" height="100%"></rect>
  </mask>
    
  <!-- Let's define the pattern -->
  <!-- The width and height should be double the circle radius we plan to use -->
  <pattern id="pattern-circles" x="0" y="0" width="40" height="40" patternUnits="userSpaceOnUse">
    <!-- Now let's draw the circle -->
    <!-- We're going to define the `fill` in the CSS for flexible use -->
    <circle mask="url(#fade)" cx="20" cy="20" r="20"></circle>
  </pattern>
  <!-- The canvas with our applied pattern -->
  <rect x="0" y="0" width="100%" height="100%" fill="url(#pattern-circles)"></rect>
  
</svg>
```
[css-tricks Link](https://css-tricks.com/snippets/svg/svg-patterns/)