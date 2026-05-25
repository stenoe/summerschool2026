# Summer school 2026

## Preparation

The preparation and ideas are to be checked for their possible realisation. We will have only one week, 8 days (incl weekend days).

### Ideas

#### Serial driver sensors
- Fedir sensors (those that are running)
Vaisala CO2 sensor deployment to small racks that can be put to the forest.

- 7-in-1 soil sensor, different soil parameters (ph, nitrogen, phosphorus, potassium, salinity, tds, ec?, temperature).  We want to deploy those to soil and try with fallen tree stems in different grade of decomposition to undestand if there are makers of the docompositioin state.

- Capacitive soil moisture sensor type that can be used to assess the soil moisture. We are also interested to measure the humidity of biomass like fallen trees in the forest exosystem. Background idea would be to find out if the stage of decay of woody biomass in forests can be classified with the humidity? A possible scenario is that wet and humid places lead to faster biomass decay. 

- Capacitive soil temperature sensor.

- DHT22 air temperature sensor. Need some housing solution when deployed to forest.

- DSM501A dust sensor, Particulate matter and density. Need check if it is much impacted by fog. 

Some thoughts from the current info: we need to check if the timestamp is at UTC and not local time. We need also to avoid daytime switching to be compatible with the SMEAR datalogging schema.

#### Water table measurements
- Emilio idea apply more of the pressure water-table sensors.

Enlarging the network of water table sensors would allow for some more input data into a hydrological model. Questions are the change in water table towards the ditches. Would need additonaly to have a drilling rig at the site for the deployment!


#### Small sensor kit to attach to a tree
- Kit with temp/rh/co2... that can be fixed to a tree. We can use part and bits and pieces that we also use already in Fedir's serial sensor kit project. That save some time with software development and deployment options.

This is a project where we can help out with more precise measurements on a spot like a specific tree within a permanent sample plot, e.g., for microcore measurements that are made for wood formation research. Wood formation is an enzymatic process, the cambium is for trees in a forest most times shaded and therefore it may have different microclimate and temperature than usual WMO rule following temperature measurement. 

#### 3D printing and sensor
- make 2d-cup-anemometer

This could be used to assess horizontal wind speed, even within the forest canopy. 
The cup anemometer might have some inductive electrical indicator, that need to be checked before we can get blueprints for the 3D-printing

#### Art - Science interface
- Sound sensor / microphone to deploy to tower
Nature and man made objects have sounds. That can be the wind moving the trees or passing by the tower contstructions. Recording these and use the data e.g., to "compose" something would be a cool art project. 

- LED visualisations

Visualise data e.g., when visitors are approaching (proximity sensor?) or use with QR codes allowing interaction with the "objects" in a forest.

#### AI/ML solutions

- Calibration solutions for low cost sensors 
- Patterns from existing data sets


## Participation

### Teachers

- Steffen
- Renato
- Emilio
-Ahto? (field trip)

### Assistants

- Fedir
- Cedric

### Students

Here we need to advertise it at the different partner Universities. EMÜ, TÜ, TalTech, Helsinki University, Aalto, UFPR (check if we can pay some travel grant as example), ABS/EnCHiL students if there is interest and funding possible. We can try to have as well connections to Uli's new University, check if there are interested persons (problem Uli starts his new job later than the Summerschool).

Audience are PhD but as well master and advanced bachelor level students. 


## Possible tasks

### Overall needed

- organise a "Summerschool server" to store and share all data that will be produced during the BIP
- get the "shopping lists" done. We need ESPs, wires, 
- Mobile phones (10 pcs, 9 available 1 with Uli), load their akkus

### Serial driver sensors

When deploying the 7-in-one sensor we should try to see how much differernt we
get the values per location. We may need later to really make additional measurements
for calibrating them! 

- Define soil types where to put the sensor
- Define fallen tree degradation to place the sensor
- Define "wetness" of places for deployment

Actually, these types of sensors measure in real only the electrical conductivity and uses some "standard soil" mixture to provide multiplication factors for the other parameters. Or, they measure the so called "dielectric constant" of the material. 

Chk for other sensors specs


### Water table measurements

Things we need to order / organise beforehand

- Check how many pressure sensors we still have and buy if more are needed
- Check the voltage enhancer get enough for the aimed number of measurements
- pipes
- geotextile
- mesh
- rent the drill gear
- measurement equipment for water depth
- drilling machine and drills for pipe holes that water can enter
- build the systems Maybe we need here again Raspberry Pi systems (check if we can do with ESP alone!)

Tasks we can do with the students:

- Calibate the systems by generating depth / Voltage data 
- Calculate for each sensor the calibration coefficient
- measure the drilled hole depth to know the sensor's distance from soil level


