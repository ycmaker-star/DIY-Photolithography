DIY-Photolithography #HACKCLUB #RaspberryPi
Attempting to create a maskless, programmable photolithography machine and safe chemical process under 200$ USD capable of sub-10 micrometer resolution in my bedroom.

The Body of Materials is in the attached excel file, many of the materials I already had, so they didn't go into the budget, furthurmore a lot of materials were stripped from used projectors (DMD, Collimating lens, fans, heatsink). Also the project was made during my time in Taiwan, so prices are in NTD and may not account for inflation (high costs in the US). 

Building Journey:

Days 1-5:
Like every good successful projects, research must be done before touching ANYTHING. Specifically, researching the internal design of projectors and how they work; Optics of photolithograhpy (especially at the micrometer resolution); chemical properties and compositions of photoresist, etchant, developer, and photoresist stripper, and finding safer/accesible alternatives; researching material wattages, power, heat production, heat dissipation. Record everything in the Engineering Notebook.

Days 6-9:
I brainstormed and sketched the architecture/design of the photolithography machine in my engineering notebook. I drew 4 different possible variations of the design and weighed the pros and cons. I've come to learn that having multiple design iterations are completely normal, and finally ended up on this one <img width="2792" height="2234" alt="IMG_6204" src="https://github.com/user-attachments/assets/8228d5f5-3ea4-454d-b448-2b4473a28a91" />

Day 10:
The chemicals arrived. A 1-3% (by weight) aqueous Sodium Carbonate (Na2CO3) solution acts as the developer for photoresist. A 2-5% (by weight) aquueous Sodium Hydroxide (NaOH) solution acts as the final photoresist stripper. Extra pure IPA is the original substrate cleaner. These chemicals, although not as dangerous as the ones typically used by industries, are still strong irritants and should be stored in dark, cool, low moisture enviornemnts. For me, I stored them in airtight glass jars (Never use metal containers) and put a Silica Moisture remover packet in each one. <img width="4032" height="3024" alt="IMG_6202" src="https://github.com/user-attachments/assets/9cefbf5f-3023-4bd7-8a47-b3aab80fd46a" />

Day 11-14:
Now for the fun part, CADing the design and prepping for 3D printing. Personally, I like using onshape due to my familiarity with VEX robotics. This part isn't very arduous as only a small portion of the machine is 3D printed (the adapter). The main purpose of the Adapter is to house the 50-50 beam splitter and direct the UV light from DMD down to the 10x lens and hence substrate, but also letting the camera aim down. It also serves as UV light dissipater. The STL file will be attached.
