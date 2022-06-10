# Openhab controls for appartment
## Light
Most software light controls are currently following a design pattern as proposed by [littlechina]. There is one rule that tracks changes to certain items, therefore acting as some sort of a resusable function (which are unfortunately not possible in openhab rule syntax).

Rules include automatic dimming of light in the evening, switching between different flairs for watching TV, working or cooking, and automatic toggling at sun down and sun rise. 

22-06-09: Added IKEA tradfri hardware switches with seperate ruling

## Audio

API based controls of Yamaha R-N303D receiver for changing inputs, volume and power.
