
#EAGLE3D_HOME=/home/poine/work/eagle3d/eagle3d/
EAGLE3D_HOME=$(HOME)/Applications/eagle3d/

POVLIB=+L$(EAGLE3D_HOME)/povray  +L/usr/share/fonts/truetype/msttcorefonts +L$(EAGLE3D_HOME)/msttfonts

all:	small
small:
	povray -Iairswimmer-controller.pov $(POVLIB) +W1600 +H1200 +Q5  +Oairswimmer-controller.png
	povray -Iairswimmer-controller-x30.pov $(POVLIB) +W1600 +H1200 +Q5  +Oairswimmer-controller-x30.png
	povray -Iairswimmer-controller-x60.pov $(POVLIB) +W1600 +H1200 +Q5  +Oairswimmer-controller-x60.png
	povray -Iairswimmer-controller-x90.pov $(POVLIB) +W1600 +H1200 +Q5  +Oairswimmer-controller-x90.png
	povray -Iairswimmer-controller-x120.pov $(POVLIB) +W1600 +H1200 +Q5  +Oairswimmer-controller-x120.png
	povray -Iairswimmer-controller-x150.pov $(POVLIB) +W1600 +H1200 +Q5  +Oairswimmer-controller-x150.png
	povray -Iairswimmer-controller-x180.pov $(POVLIB) +W1600 +H1200 +Q5  +Oairswimmer-controller-x180.png
	povray -Iairswimmer-controller-x210.pov $(POVLIB) +W1600 +H1200 +Q5  +Oairswimmer-controller-x210.png
	povray -Iairswimmer-controller-x240.pov $(POVLIB) +W1600 +H1200 +Q5  +Oairswimmer-controller-x240.png
	povray -Iairswimmer-controller-x270.pov $(POVLIB) +W1600 +H1200 +Q5  +Oairswimmer-controller-x270.png
	povray -Iairswimmer-controller-x300.pov $(POVLIB) +W1600 +H1200 +Q5  +Oairswimmer-controller-x300.png

big: 
	povray -Iairswimmer-controller.pov $(POVLIB) +W3200 +H2400 +Q9 +R9 +A0.01 +Oairswimmer-controller-0-big.png
	povray -Iairswimmer-controller-x30.pov $(POVLIB) +W3200 +H2400 +Q9 +R9 +A0.01 +Oairswimmer-controller-30-big.png
	povray -Iairswimmer-controller-x60.pov $(POVLIB) +W3200 +H2400 +Q9 +R9 +A0.01 +Oairswimmer-controller-60-big.png
	povray -Iairswimmer-controller-x90.pov $(POVLIB) +W3200 +H2400 +Q9 +R9 +A0.01 +Oairswimmer-controller-90-big.png
	povray -Iairswimmer-controller-x120.pov $(POVLIB) +W3200 +H2400 +Q9 +R9 +A0.01 +Oairswimmer-controller-120-big.png
	povray -Iairswimmer-controller-x150.pov $(POVLIB) +W3200 +H2400 +Q9 +R9 +A0.01 +Oairswimmer-controller-150-big.png
	povray -Iairswimmer-controller-x180.pov $(POVLIB) +W3200 +H2400 +Q9 +R9 +A0.01 +Oairswimmer-controller-180-big.png
	povray -Iairswimmer-controller-x210.pov $(POVLIB) +W3200 +H2400 +Q9 +R9 +A0.01 +Oairswimmer-controller-210-big.png
	povray -Iairswimmer-controller-x240.pov $(POVLIB) +W3200 +H2400 +Q9 +R9 +A0.01 +Oairswimmer-controller-240-big.png
	povray -Iairswimmer-controller-x270.pov $(POVLIB) +W3200 +H2400 +Q9 +R9 +A0.01 +Oairswimmer-controller-270-big.png
	povray -Iairswimmer-controller-x300.pov $(POVLIB) +W3200 +H2400 +Q9 +R9 +A0.01 +Oairswimmer-controller-300-big.png


clean:
	rm *.png
