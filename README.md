# global-dynamic-landslide-susceptibility-maps
Examples of global dynamic landslide susceptibility maps

Files name description:
  ET: extremely randomized trees
  LGB: light gradient boosting machine
  RF: random forest

Susceptibility classification criteria:
  0: Very low
  1: low
  2: moderate
  3: high
  4: very high

we randomly took two days, December 15, 2020 (Northern Hemisphere winter) and June 15, 2021 (Northern Hemisphere summer), as examples.
After creating a global land fish-net consisting of 250-m blocks, the landslide influencing factors on these two dates were extracted.
Then, we applied the model to assess the landslide susceptibility and rasterize the fishnet to produce two landslide susceptibility probability maps for these dates at a spatial resolution of 500 m.
Finally, the landslide susceptibility probability map was di-vided into five categories by using the equal interval classification method with class names (probability ranges) of very low (0–0.2), low (0.2–0.4), moderate (0.4–0.6), high (0.6–0.8) and very high (0.8–1.0) 
