# Here's my sample text

This is some sample text

(section-label)=

## Here's my first section

Here is a [reference to the intro](intro.md). Here is a reference to [](section-label).

## Planet Jupiter

 ```{figure} https://solarsystem.nasa.gov/system/resources/detail_files/2486_stsci-h-p1936a_1800.jpg
 ---
 height: 300px
 name: jupiter-figure
 ---
 The beautiful planet Jupiter!
 ```

Jupiter is the fifth planet from the Sun and the largest in the Solar System.

In {numref}'jupiter-figure', you can see an image of the planet Jupiter captured by the Hubble Space Telescope.

Jupiter has a mass of:  $m_{j} \approx 1.9 \times 10^{27} \: \text{kg}$

Let's show this as a code block as well:

$$
  m_{j} \approx 1.9 \times 10^{27} \: \text{kg}
$$

Another way is to have the named equations so you can cross-reference them later:

 ```{math}
 :label: eq_label
 m_{j} \approx 1.9 \times 10^{27} \: \text{kg}
 ```

Equation {eq}'eq_label' is an example of a named equation

## Testing Area

:::{note} Did you know?
Jupiter is 11.0x larger than Earth!
:::

```{dropdown}What is the capital of Canada?
If you guessed Ottawa, give yourself a pat!
```
