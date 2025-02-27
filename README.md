# Team_Venture_Land_Rover_Power_System_for_Venus

Hello and Welcome to Team Venture official GitHub Resources.

![Team Venture](/assets/images/team_photo.png)

<p align="center">Photo: Team Venture | NASA Space App Challenge 2022</p>

## Project Scope:

Designing Energy Storage System For Venus Surface Mission

## Start with a Story:

Suppose you wanna operate a mission somewhere where the temperature and pressure are too high to make the microcomputer functionalities, it is impossible to produce sufficient heat to power up your vehicle. What should you do then? That is the question we, the team venture, are trying to solve. Designing a powerful energy storage system for your next mission.

## Milestone to achieve(Requirements)

- <b>Operation time:</b> At least 60 days
- <b>Operation environment 1:</b> Approximately ~460 °C
- <b>Operation environment 2:</b> Air pressure nearly 93 bar
- <b>Battery Requiremnt:</b> Required 28 Volt power system

## Project Description Overview:

![System Workflow](/assets/images/Workflow.png)

<p align="center">Fig: System Workflow</p>

We conceptualize an energy storage system for the next NASA mission to venus. To explore Venus for at least 60 days, we proposed an energy producer, storage, and cooling system to power up the rover. We designed a system with no recharge time containing an mmRTG power system generating electricity. A sodium-sulfur battery for storing electricity and supplying it to the rover. A Stirling cooling system to maintain the operating temperature of semiconductors.

## Project Discussion:

Designing an energy storage system for Venus's mission is difficult. Because of the extreme atmospheric condition of Venus. That’s why we proposed a Radio-isotope Thermoelectric Generator(RTG) for our power source where plutonium-238 will be used for production. Then we have to store the energy. For storing, we will use NaS battery.

As Venus is a very hot planet and its temperature is ~460 °C. Also, the MMRTG will generate approximately 1020 °C, so the temperature will be so high that needs to be reduced. Then we need a cooler. And, that’s why we proposed to use a Stirring Cooler system which pumps the heat out of the rover. The Stirling cooler transfers the waste heat to convective radiators, which efficiently reject heat to the Venus atmosphere at a temperature of 500 °C, 40 °C above the surface ambient temperature.

To operate a Rover on Venus's surface, we have produced enough energy. Also, we have to ensure that the production system will work in Venus's harsh environment. That's why we choose MMRTG Plutonium-238 isotope. As it's a radioisotope, it generates huge heat(~1200°C), and we have to cool down the inside temperature of the Venus rover. And for this cooling requirement, we choose a Stirring Cooling system, which can reduce temperature to 200°C. We have to consider one fact here. MMRTG generates electricity constantly. So, we need to store the electricity. For this part, we consider using NaS battery to store the electricity. A depth discussion about these three is below:

### 1. MMRTG (Multi-Mission Radioisotope Thermoelectric Generator)

We have designed a system that can power up the land rover with a radio-isotope thermoelectric generator (RTG), a sodium-sulfur battery to provide any shortage of power, and a cooling system in the rover. To drive a rover we need a power source that can generate or provide at least 215 watts per hour.

![MMRTG](/assets/images/mmrtg1.png)

<p align="center">Video Source: NASA YouTube Channel(https://www.youtube.com/watch?v=dqBKDpfOeHc)</p>

The RTG will provide power to the rover constantly. We proposed to use Plutonium-238 as the radio-isotope material which can provide 0.54 watts per gram of energy, at 10% efficiency it will generate 0.054 watts per gram. We have calculated 4 kg of plutonium for our system to provide 215 watts per hour of energy and have an operational lifetime of at least 14 years.

RTG was used during the Appolo program to the moon, in voyagers 1 and 2, in Cassini to Saturn, in Curiosity, in Perseverance to mars and not a single thermocouple has failed. Plutonium 238 is an alpha emitter. Alpha particles can be very easily shielded. Even a sheet of paper is enough to protect us against alpha radiation. It's only a hazard to the human body if it's inhaled or is its ingested. To prevent that we use the fuel in an oxide form as plutonium 238 dioxides. Surrounding the plutonium fuel is a material called Iridium. Iridium at these operating temperatures is very strong and very ductile. Iridium also has a very high melting point and it has good material compatibility with the other materials found in the GPHS module. Over the last 40 years, an aggressive testing campaign is engaged to prove the safety of these devices. every time they behave exactly as they were designed.

### 2. Battery( NaS battery )

Sodium sulfur batteries can operate at 450-degree celsius. our batteries are sized to provide 2200 Whr of energy storage and specific energy of 220 Whr/kg (340 kWhr/m3) with an average power draw of 64.5 W. The purpose of this cooling system is to allow the electronics to be used at their functional temperature.

![Sodium Sulpher Battery](/assets/images/nas_battery.png)

<p align="center">Fig: Sodium Sulpher Battery</p>

The system allows a high-temperature silicon-on-insulator (SOI) microcontroller to be used at 3000C with an ambient heat load of 110 W. The mass of this system is 1.6 kg with an astounding mechanical efficiency of 85%.

### 3. Cooling System (Stirring Cooling System)

![Stiring Cooling System](/assets/images/stiring_cooling2.png)

<p align="center">Fig: Stiring Cooling System</p>

The cooling requirement to keep the heat pipe cold-side temperature at 475 K is 105 W of heat pumping. As calculated using the Stirling heat-engine design tool SAGE, the configuration that was modeled effectively pumps 100 W of heat across the required 300°C of temperature differential with an operating coefficient of performance of 0.44, requiring approximately 240 W of input power, which can be provided by an isotope power system.

## Space Agency Data:

We made sure to make the best use of NASA Website data for designing our power storage system for the Venus land rover. In some places, we used the latest research data which are published on NASA's Official website to design our system. Also, the information regarding Venus environmental situation of Venus, rover technology for outer space missions,s and the issues and challenges regarding the construction of high-temperature materials and electronics all are taken directly from NASA and different kinds of research facilities of NASA.

## Hackathon Journey:

This is for the first time all the members of our team participated in the NASA Space App Challenge Bangladesh Chapter. After getting the opportunity to participate in this prestigious hackathon, we were very thrilled as we get to work with the challenges from NASA.

We believed that the challenge of "Exploring Venus Together" was such a unique concept. As the previous missions regarding Venus were very much successful but not on the surface of its extreme environmental condition. The challenges we faced designing an energy storage system for a land rover was pretty rough and forced us to our limits. But our team members supported each other and we covered our backs each time we faced any difficulty. We wish to perform our best to be the global champion in this Space App Challenge 2022.

Overall our journey up to this point was full of excitement and adventure. We learned a lot about so many concepts, knowledge, and problem-solving technique during this time, and much more from our respected mentor who guided us from the very beginning of Space App Challenge 2022. We thank BASIS for arranging this glorious event and their astounding hospitality in bringing out people like us and giving us the opportunity to represent ourselves on this global platform.

## References:

- https://solarsystem.nasa.gov/resources/549/energy-storage-technologies-for-future-planetary-science-missions/
- https://solarsystem.nasa.gov/news/1519/venus-resources/?page=0&per_page=40&order=created_at+desc&search=&tags=Venus&category=324
- https://solarsystem.nasa.gov/planets/venus/overview/
- https://arc.aiaa.org/doi/pdf/10.2514/1.41886
- https://science.nasa.gov/science-red/s3fs-public/atoms/files/Venus%20Flagship%20Mission.pdf
- https://www.jpl.nasa.gov/news/press_kits/mars_2020/launch/mission/spacecraft/power/
