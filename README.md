# Sketchup Model

Preliminary sketchup model of what I plan to construct.

It is an industrial rice steamer, to be converted to a smoking chamber.

##A large heating element will be installed in the bottom of the chamber
  - The large heating element (1000-2000watts) will be installed
  - Element will be mounted in predrilled holes in rice cooked
      - Fill any un-needed holes with stainless steel washers and bolts
      - All power A/C connections will be protected by removable plate on smoker body
  - A thermocouple temperature sensor will monitor the temperature of the chamber
  - Arduino PID control outputs will activate a SSR relay to provide power to the heating relay
      - Signal wires should be contained in the wiring rail

##A smaller heating element will be installed near the bottom of the unit
  - A stainless steel pan of wood chips/sugar cane pulp will be placed on it
  \\\\\\\\\\\\\\\\\\unsure how to mount the smoke element at this time\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\
      - All power A/C connections will be protected by removable plate on smoker body
  - Timed outputs from the arduino will activate a SSR relay to provide power to the heating element
     - Signal wires should be contained in the wiring rail
  - The material on in the stainless pan will smolder producing smoke
  
##Drip shields will be constructed of bent stainless plate with 2 cross bars
  - Cross bars support the shields as they slide into the food tray supports
  - Direct drippings into foil lined collection trays to protect the heating elements from drippings
  
##Stainless steel grill racks will slide in and out of the food tray supports
  - Food to be smoked will be placed on these racks
  - Must make sure they have proper clearance with all installed hardware
  - Be aware of where the thermocouple temperature sensor will be installed
  
##Smoke chamber temperature sensor
  - Thermocouple installed into rear of smoker body
      - Probe must extend into the chamber far enough to get an accurate reading
          - Must not be touching any internal parts
          - Should be far enough from food to prevent misreadings
          - Small hole inside of smoker chamber fitted with a hightemp grommet for the probe
          - Large hole in rear body of smoker for the thermocouple to screw into
          - All the associated wiring should be contained in the wiring rail
  
##4 food temperature probes will be installed in the chamber
  - Upper left and upper right permanently mounted probes
  - Lower left and lower right removable probes for large cooking projects
  - 4 small holes to be drilled in the smoker body
      - Install high temp rubber grommets in the holes to protect sensor cables from abrasions
      - Temperature probes are pushed through the holes and the extra cable hangs out the back of the smoker
          - The 3.5mm mono jacks on the end of the probes will plug into female jacks in the wiring rail
          
##Wiring Rail
  - Rear Rail
      - Stain steel square tubing to be centered vertically along the rear of the smoker body
          - Majority of the side touching the smoker body will be removed for access
              - A few locations will be left intact for attachment to the smoker body
                - Access holes will be drilled opposite the attachment points
                - Self taping screws or rivets will attach the square tubing to the smoker body
          - Cables required to go to the arduino will be installed inside this tubing
          - 4 female 3.5mm jacks will be installed along the railing
              - These are the probe attachment points
          - Potentially interface with convection fan housing
  - Top Rail
      - Stain steel square tubing to be centered vertically along the top of the smoker body
          - Majority of the side touching the smoker body will be removed for access
              - A few locations will be left intact for attachment to the smoker body
                - Access holes will be drilled opposite the attachment points
                - Self taping screws or rivets will attach the square tubing to the smoker body
          - Cables required to go to the arduino will be installed inside this tubing
              - All of the cables will terminate into a 16 pin connector to be connected to the arduino control
              - Some sort of weather project should be taken into account
              
##Arduino Control housing
  - Stainless steel box with angled front panel
      - LCD screen will display smoker  information
      - 3 waterproof buttons will be used for manually programming the smoker
      - Smoke on Indicator light
      - Heat on Indicator light
      - The box will have 4 small rubber feet to raise it off the surface of the smoker
      - The rear of the box will have a 16 pin connector
          - Connect to the smoker using a 16pin cable
      
##Ventilation
  - Ventilation Holes near the bottom of the smoker
      - Check exisiting holes in rice cooker body for feasability
      - Protect the insulation from smoke by lining the passage with stainless flashing or something else
  - Ventilation Holes near the top of the smoker
      - Check exisiting holes in rice cooker body for feasability
      - Protect the insulation from smoke by lining the passage with stainless flashing or something else

##Circulation
  Possible convection fan installation on rear of smoker body
      - Smoker must remain a minimum width
        - Fan shaft enters though the main smoker body
            - Large blade mounted to shaft inside of smoking chamber for circulation
            - Small blade mounted to to shaft on rear of smoker body for heat dissipation
        - Fan motor mounted on rear of smoker body
            - All A/C power connections should be shielded from touch and grounded
            - Stainless cover to protect the body
                - Possible location for heating element SSR relays
                
  
        
