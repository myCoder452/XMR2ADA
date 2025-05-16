XMR-2-ADA PROJECT: PURPOSE 

The poverty situation in Africa is dire for many individuals, this project many not only provide resources for others, but may also inspire others who have the opportunity and the path to make an impact , to make their path a force to support others, 
to walk in the light and to use their knowledge and resources to provide opportunities to those in need.

The project's belief is to develop a way for users to earn income and generate profit in a simple way.

Africa is in a position where many of its inhabitants are living far below the poverty threshold, without access to food and water, places them in a position where they are not able to attend school, as they are constantly having to find a way to get resources, instead of being able to learn and 
have a deeper understanding of the world we live in. Many of them lack the ability to even get the access to work which results in very minimal access to food and water, lacking access to basic needs leads to the people being in a position of malnourishment and starvation, 
resulting in a lack of growth of the population and a stagnant society. Since whether we may realize it or not, people need eachother to evolve and be happy.

The resources that can be generated from this project can align people in a healthier and happier position. It is a project that I hope can not only one day support others by providing them resources, but its development and purpose can also inspire others to be a pillar for those around them along their own journey, 
as supporting others and providing opportunities to others, I believe, is the truest form of fufillment.

I hope this project can inspire others to do well unto one another, and can see the good that can come from it, by recognizing the intent that it was built with so that those who use it or hear about will understand why it was built, and may be inspired by its purpose.



XMR-2-ADA: RUNNING THE PROJECT

Each of the 3 main folders: xmr-miner-full, auto-swap-full, and ada-net-full. Are pieces to the potential complete project.

The xmr-miner-full and ada-net-full sections of the project both have a main.py piece of code that executes each of their sections.

1. XMR-MINER-FULL
	- 	This piece of the project connects the user to the XMR-mainnet, and can generate a wallet address for the user if necessary. 
			- THE USER SHOULD MAKE SURE TO WRITE AND/OR COPY THEIR SEED PHRASE FOR THEIR GENERATED NEW WALLET AS IT MAY BE DIFFICULT TO RETRIEVE AFTERWARDS
			
	-	It can then connect to a Monero mining pool, and contribute to the actual valid mining operations from there
	-	The way I designed the program, the program could simply be adjusted to so the user can select their desired mining pool from an imported list, making the design of the implementation a user-friendly and potentially scalable program
	
2. AUTO-SWAP-FULL
	-	An automated swap program, that can detect a given wallet address, assess it's balance and then run an automated swap between XMR (Monero) and Cardano (ADA), hence the XMR2ADA title
	-	The program uses the Rubic API, a platform that allows swapping between these two coins at a minimal cost and relatively simpler implementation
	- 	I plan on experimenting with a variety of APIs, to see which ones are most scalable and simpler to implement, as the swap functionality optimization is crucial for the functionality of the project
	-	The program isn't fully operational as the functionality of the program is based connectivity on the other two sections,  and script that can compile all three sections at once, but the template and the skeleton is there, with some modifications it can surely be scalable
	
3. ADA-NET-FULL
	-	This program can either connect you to the mainnet or the testnet, depending on your wishes, then generate  wallet address based on your requirements and store that wallet as a .json file. 
	-	You should then be able to interact with that wallet, executing transactions and pushing those funds to the Cardano staking pool, generating profits from their platform as well
	-	The program is capable of connecting to a Cardano Node, which with further design will be able to be adjustable by the user as they wish


At the moment the project lacks complete cohesion, meaning the 3 sections are not communicating at this point. The first and third sections (1&3) possess complete functionality.

For the second piece AUTO-SWAP-FULL, to function properly, the script combining all 3 programs needs to be developed. That script would allow a connection from the functioning mainnet miner, to the AUTO-SWAP-FULL program and then connect that data to the ADA-NET-FULL program
demonstrating the actual capacity and potential of the project.

For the sake of pushing it to github, each piece of project is sealed in a zip file, they can be extracted and ran to examine their functionality.


XMR-2-ADA: SCALABILITY POTENTIAL

The scalability of the project comes from being able to more efficiently connect to the networks and store the data, although I have the entire mainnet synchronized to the project, which is necessary for optimal implementation, if the entire mainnet data was loaded onto a server that allowed user to connect to it
, it would result in simpler scalable system for many users to access. 

Being able to run the entire program as one cohesive software would be fantastic, it would allow others to not only gain access to resources, but allow other to be exposed to the technology, improving their skillset and allowing the future to be brighter for others who can benefit from the same type of implementation.

Data storage could be secured and simple using the .json files and storing them on a database implementing a variety of database CRUD operations. 

If scaled properly, and the data transfer is optimal, there is notable potential to build a functioning application or software for the program, allowing users to efficiently access the technology.


XMR-2-ADA: CLOSING REMARKS

The XMR-2-ADA has the capability to generate reasonable profits for those with the resources, and if scaled properly can provide exceptional support to those even without the advanced technological gear to optimize their profits. 

I hope the design and production of this type of product will inspire others to look for ways to support others who are serious need: Africans are in serious need of support, and it's important that those of us who have the knowledge and access to resources provide a path for others to experience
health and happiness. This website for example, https://www.children.org/global-poverty/global-poverty-facts/africa, outlines that about 48% of sub-saharan Africans live in poverty. Understanding this, it is important that people who have the opportunity, align themselves on a path to support others.

The will & desire to make the world a better place comes from graciousness, recognizing how grateful you are for the position you are in, will guide you towards proper fullfillment, which is being able to explore your own curiosities while aiming to provide aid to others. 

I am sincerely thankful for the opportunity to participate in this event, and I had a fantastic time! Thank you!




	