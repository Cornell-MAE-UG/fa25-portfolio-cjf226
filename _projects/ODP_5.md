---
layout: project
title: ODP 5
description: MAE2250 Open Design Project assignment number 5.
image: /assets/images/Spotted-Lanternfly-1.jpg
---

# ODP 5

---

## ODP 4 Testing Summary

For our last ODP assignment, we did a lot of testing similar to what is expected in this assignment, but for other aspects of our design. We wanted to highlight our progress here to show what we have done and how it relates to what we are testing this week.

Our previous prototype proved that our device could have an approximately 20 pound-foot moment at the end of it and still be manageable to control. This is much more than we will need to actually hold with our device. The handle and rod setup have already been tested, so this prototype is focused solely on the scraper itself (the part we haven't tested). Essentially, our findings from our last prototype led us to create a relatively simple prototype for this week, as seen in the documentation below.

---

## Documentation

**Parts Used:**
- 1.158" diameter Wooden Rod found in lab
- Custom 3D-printed scraper

**Design Intent Sketches/CAD:**

*(See CAD images in original document)*

**Dimensions:**
- Bottom length: 10" (from edge of the scraper to bottom end of hole)
- Height: 5.5" (from bottom plane to top of arch)
- Width: 6"
- Length of cylinder (for press-fit): 2.5"

**Instructions for Assembly:**
- We sanded down the wooden rod slightly to better press-fit it into the scraper's cylindrical hole
- The press-fit was the best technique for prototype purposes and could probably be used again for the final design, but we will likely add a notch to securely prevent rotation of the two parts

---

## Design Tests

### Scraping Efficacy

**Test:** Scraper ability to collect egg masses

**Procedure:** Put 10 different-shaped egg masses (clay blobs) on the wall and scrape them from different angles (between horizontal and vertical) to simulate scraping egg masses in real life. The heights of the egg masses varied from 126 cm above ground to 200 cm above ground; one was placed about 30 cm from ground for variety (specifically: 29, 126, 143, 145.5, 150, 152, 178, 196, 198, and 200 cm above ground). We scraped each egg mass 1–3 times or until approximately 90% of the clay was gone.

**Results:** Overall, the scraper was effective. It was able to scrape more than 90% of the clay for 9/10 of the "egg masses". The single point of failure occurred at a negative-clearance corner geometry, indicating a required design modification for the scraper's geometric profile. It is also important to note that these simulated egg masses were heavier and stickier than a real SLF egg mass is.

**Conclusions:** Our current scraper geometry is effective on smooth surfaces; it has issues with corners, and we noticed that the scraper's flared walls make it so that you can only scrape if the scraper is almost flush with the wall. We will probably remove this flare and possibly add a modular attachment/side of our scraper for less even geometry, like corners.

---

### Scraper Size

**Test:** Is the scraper big enough?

**Procedure:** During the efficacy trials, we conducted a visual audit of the debris capture rate.

**Results:** The current bowl geometry achieved a 100% capture efficiency for the successfully detached masses.

**Conclusions:** Because the debris consistently settled in the lower quartile of the bowl, we can quantitatively reduce the overall width of the scraper (from edge to rounded backing) by at least 1.0 inch in the next iteration to save material and reduce drag, without compromising the capture rate.

---

### Durability

**Test:** Is the scraper edge durable enough for repeated use?

**Procedure:** We performed an accelerated wear test using an abrasive substrate (sandpaper) to simulate extreme bark conditions. Set up a simulated rough edge with egg masses using clay and sandpaper. Measure the scraper base length. Scrape the rough edge for 2 sets of 20 scrapes and measure the new length of the scraper base after each set.

**Results:**
<table>
  <thead>
    <tr>
      <th>Set</th>
      <th>Base Length</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Initial</td>
      <td>18.7 cm</td>
    </tr>
    <tr>
      <td>After 20 scrapes</td>
      <td>18.4 cm</td>
    </tr>
    <tr>
      <td>After 40 scrapes</td>
      <td>18.3 cm</td>
    </tr>
  </tbody>
</table>

**Conclusions:** The scraper edge is not durable enough, especially at the very tip. This quantifiable material loss rate of 0.1 mm per cycle confirms that the plastic edge is insufficient for long-term deployment, necessitating a transition to a harder material (e.g., folded sheet metal, PETG, or a metal insert) for the final prototype. Additionally, the scraper took significantly more effort to scrape putty off the rough surface. To reduce this effort, we will look towards decreasing the width of the scraper, which will increase pressure due to less surface area. This is not too worrisome, though, because the putty we used is definitely stickier than SLF egg masses are, and sandpaper is rougher than most materials found outdoors.

---

### Scraper Load Bearing

**Test:** Outside of the durability of the scraping edge, is the scraper strong enough to deal with the loads it must bear to scrape?

**Procedure:** We conducted a qualitative dynamic load test by applying the maximum expected user shear force against the abrasive test wall. Additionally, the scraper held a static load equivalent to the mass of the 10 heavy clay test-pieces (approx. 0.5 to 1.0 lbs).

**Results:** Besides the receding edge, the scraper held up through all tests we ran. The press-fit joint and 3D-printed walls exhibited zero visible yielding or deflection under these peak operational loads.

**Conclusions:** The scraper geometry has thick enough walls and is strong enough for our purposes.

---

## Success Criteria

**Context:** Our project is a scraper designed to remove spotted lanternfly egg masses from surfaces such as walls, trees, and other outdoor structures while collecting the removed material. The egg masses are about 0.5g and 1.5in long. Our product specifically excels at targeting masses located out of normal reach. Our functional prototype is a high-reach, pole-mounted mechanical scraper designed to replace manual scraping methods.

### 1. Scraping Efficiency *(Highest Priority)*
- **Criterion:** The scraper should remove at least 90% of a simulated egg mass within 3 scraping motions.
- **Rationale:** Assesses the functional ability of the blade's geometry to detach masses from uneven/textured surfaces.
- **Test:** Place 10 clay masses at varying heights on multiple surfaces and scrape using the prototype. Visually analyze remaining clay. At least 8/10 egg masses must have >90% removal within three scrapes.
- **Demo:** Can be exemplified in an exhibit day demo of the procedure described above.

### 2. Blade Durability
- **Criterion:** The scraper blade must lose <5mm of material length after 40 aggressive scraping cycles.
- **Rationale:** Assesses the lifespan of the scraping edge of our prototype.
- **Test:** Measure the initial blade length with digital calipers, perform 40 scraping cycles on sandpaper, and take a final measurement to calculate material loss.

### 3. Total Weight
- **Criterion:** The total weight of the fully assembled tool (head, pole, handle, and fasteners) must not exceed 10 pounds.
- **Rationale:** Assesses user fatigue and ergonomic viability, as holding a heavy tool at the end of a long moment arm is physically taxing.
- **Test:** Weigh the fully assembled prototype on a digital scale.

### 4. Operational Reach
- **Criterion:** The scraper must achieve a >90% mass removal rate on targets placed between 8 and 10 feet tall.
- **Rationale:** Tests the tool's ability to transmit sufficient normal force (pushing into the wall) and shear force (scraping up) at extreme operating angles, without requiring the user to change their grip or use a ladder.
- **Test:** Use the scraping efficiency test above with clay masses placed at the maximum reach height of the device.