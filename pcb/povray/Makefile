# Generate with the following to be consistent
#
# Board Gray10
# Wires Gray70
# Pads Silver
# Holes Gray50
# Background White
# Silk Screen Gray90
# Through Holes Gray50
#

#EAGLE3D_HOME=/home/poine/work/eagle3d/eagle3d/
EAGLE3D_HOME=$(HOME)/Applications/eagle3d/

POVLIB=+L$(EAGLE3D_HOME)/povray  +L/usr/share/fonts/truetype/msttcorefonts +L$(EAGLE3D_HOME)/msttfonts

all:	small
small:
	povray -icon -Iairswimmer-controller.pov $(POVLIB) +W1600 +H1200 +Q5  +Oairswimmer-controller.png
	povray -icon -Iairswimmer-controller-30.pov $(POVLIB) +W1600 +H1200 +Q5  +Oairswimmer-controller-30.png
	povray -icon -Iairswimmer-controller-60.pov $(POVLIB) +W1600 +H1200 +Q5  +Oairswimmer-controller-60.png
	povray -icon -Iairswimmer-controller-90.pov $(POVLIB) +W1600 +H1200 +Q5  +Oairswimmer-controller-90.png
	povray -icon -Iairswimmer-controller-120.pov $(POVLIB) +W1600 +H1200 +Q5  +Oairswimmer-controller-120.png
	povray -icon -Iairswimmer-controller-150.pov $(POVLIB) +W1600 +H1200 +Q5  +Oairswimmer-controller-150.png
	povray -icon -Iairswimmer-controller-180.pov $(POVLIB) +W1600 +H1200 +Q5  +Oairswimmer-controller-180.png
	povray -icon -Iairswimmer-controller-210.pov $(POVLIB) +W1600 +H1200 +Q5  +Oairswimmer-controller-210.png
	povray -icon -Iairswimmer-controller-240.pov $(POVLIB) +W1600 +H1200 +Q5  +Oairswimmer-controller-240.png
	povray -icon -Iairswimmer-controller-270.pov $(POVLIB) +W1600 +H1200 +Q5  +Oairswimmer-controller-270.png
	povray -icon -Iairswimmer-controller-300.pov $(POVLIB) +W1600 +H1200 +Q5  +Oairswimmer-controller-300.png

big: 
	povray -icon -Iairswimmer-controller.pov $(POVLIB) +W3200 +H2400 +Q11 +R9 +A0.01 +Oairswimmer-controller-0-big.png
	povray -icon -Iairswimmer-controller-30.pov $(POVLIB) +W3200 +H2400 +Q11 +R9 +A0.01 +Oairswimmer-controller-30-big.png
	povray -icon -Iairswimmer-controller-60.pov $(POVLIB) +W3200 +H2400 +Q11 +R9 +A0.01 +Oairswimmer-controller-60-big.png
	povray -icon -Iairswimmer-controller-90.pov $(POVLIB) +W3200 +H2400 +Q11 +R9 +A0.01 +Oairswimmer-controller-90-big.png
	povray -icon -Iairswimmer-controller-120.pov $(POVLIB) +W3200 +H2400 +Q11 +R9 +A0.01 +Oairswimmer-controller-120-big.png
	povray -icon -Iairswimmer-controller-150.pov $(POVLIB) +W3200 +H2400 +Q11 +R9 +A0.01 +Oairswimmer-controller-150-big.png
	povray -icon -Iairswimmer-controller-180.pov $(POVLIB) +W3200 +H2400 +Q11 +R9 +A0.01 +Oairswimmer-controller-180-big.png
	povray -icon -Iairswimmer-controller-210.pov $(POVLIB) +W3200 +H2400 +Q11 +R9 +A0.01 +Oairswimmer-controller-210-big.png
	povray -icon -Iairswimmer-controller-240.pov $(POVLIB) +W3200 +H2400 +Q11 +R9 +A0.01 +Oairswimmer-controller-240-big.png
	povray -icon -Iairswimmer-controller-270.pov $(POVLIB) +W3200 +H2400 +Q11 +R9 +A0.01 +Oairswimmer-controller-270-big.png
	povray -icon -Iairswimmer-controller-300.pov $(POVLIB) +W3200 +H2400 +Q11 +R9 +A0.01 +Oairswimmer-controller-300-big.png


clean:
	rm *.png
