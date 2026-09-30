# Dye Sublimation Printing HOWTO

## Machinery

* Printer: Epson ET-15000
* Flat heat press (t-shirts, flat pictures, mouse pads, etc): Vevor XXX
* Mug heat press (also tumblers etc): Vevor XXX

## Materials

### Ink

* Use only dye sublimation ink in the ET-15000 printer
  * NOT the ink that came with it, or any general purpose ecotank ink
  * Currently using Hiipoo brand dye sublimation ink
  * Ink can leak when refilling, even when using the special EZ refill system
  * Syringe can be a safer bet in terms of avoiding accidents

### Paper

* It's OK to print tests on regular paper
* When ready to press, use dye sublimation paper
  * Currently using Hiipoo brand sublimation paper
  * A-SUB brand paper is also commonly recommended
  * Only one side is printable
  * You can trim the part you didn't use for later use

### Blanks

#### T-shirts

* At least 65% polyester
* Light colored material

#### Mugs

* Use mugs marketed for "sublimation"

#### Metal photo rectangles

* There is usually a coating that has to be removed before heat pressing
* Press at 370F for 90 seconds

#### Mouse pads

* White polyester fabric coated
* Small mouse pad is 180x220 mm
  * Print slightly larger so the whole surface is covered
* Press at 360F for 65 seconds

## Steps

### Test print

* (Optional) test print to verify size and alignment

### REVERSE THE IMAGE!!!

* Typically you need to reverse the image, especially if it has text
* In gimp, right click, Image::Transform::FlipHorizontally

### Printing from Gimp

* Select the "EPSON ET 15000" from the list of printers
  * It might say "unavailable" or so (wait for it to be enabled)
* There are specific settings to use, as follows
  * If these are not present, ensure using specialized print panel not generic
  * Maybe try restarting printer, relaunching print panel
* Page setup
  * Paper
    * Paper type: Matte
    * Paper source: **Rear**
    * Output tray: Face Up
* Image Settings
  * Adjust the resolution / size parameters as appropriate
  * Zero the top/left params (there is still a built-in margin)
* Advanced
  * Print Quality: High

### Loading paper

* Load the dye sublimation from rear of printer, logo/watermark down
  * Path is straight through, image will be on top
* Initiate print from gimp
* It may complain about selected paper vs loaded
  * Assure the printer you want to print using supplied settings

### Let the print dry a bit before handling it

### Figure out where you're going to put the hot stuff to cool after printing

* Ideally we should have a wire rack that can be set out for hot stuff

### Set up for heat press

* Assemble the stack
  * Paper (parchment or butcher paper) to absorb bleed-out
  * Actual workpiece secured with **HEAT RESISTANT** tape:
    * Blank (side to print face up)
    * Sublimation paper (printed side face down)
  * Note: fasten well--if it shifts during pressing, the image will be blurred
  * More paper (again to avoid ink contamination)
* Place in press and adjust clamping pressure so clamps down firmly

### Preheat the heat press

* Turn on
* Set the temperature and time
* Close the press. When the timer starts, it's pre-heated
* Can double-check with digital thermometer in case built-in probe inaccurate

### Place the stack into the press

* **USE THE HEAT-RESISTANT GLOVES**
* Get everything aligned and close the press
* It should beep when it's done (you can use a separate timer if desired)
* Open the heat press, place the workpiece on a suitable cooling surface
