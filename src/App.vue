<script setup></script>

<template>
    <v-layout>
      <v-app-bar
        color="black"
        height="100"
        >
        <template v-slot:prepend>
          <div style="padding:0px !important; display:flex">
            <div style="width:90px;  " class="ma-3"><v-img  style="height:100%; width: 100%;" src="/icon.png"></v-img></div>
            <div style="padding:0px !important;  justify-content: center;
  align-items: center; display: flex;"><h2>REFORMA <span style="color:#FF5349">PILIPINAS</span></h2></div>
          </div>
  
        </template>
        <v-col cols="1" v-if="!this.$vuetify.display.mobile"></v-col>
        <v-app-bar-title v-if="!this.$vuetify.display.mobile" style="align-items: center;" class="d-flex justify-center flex-row wrap-text">

          <v-btn @click="scrollTo('mission')">Our Mission</v-btn>
          <v-btn @click="scrollTo('stories')">Stories</v-btn>
          <v-btn>Impact</v-btn>
          <v-btn @click="scrollTo('join')">Get Involved</v-btn>
  
        </v-app-bar-title>
        <v-col cols="2" v-if="!this.$vuetify.display.mobile"></v-col>
        <template v-slot:append>
          <v-btn class="mr-3" style="background-color:#FF5349" rounded="xl"><span style="color:white">Join Now</span></v-btn>
        </template>
      </v-app-bar>

      <v-main fluid>
        <v-parallax style="min-height:100vh;"  src="/hero.jpg">
          <div class="d-flex flex-column justify-center align-center text-white" style="margin-top: 2em;">

            <v-col cols="12" sm="6" md="6" style="text-align: left;">
              <!-- <h3>
                We are the collective voice of citizens who refuse to accept empty promises and political rhetoric. Together, we demand real change, accountability, and genuine representation.
              </h3> -->
              <div style="text-align: center;">
                  <div style="display: inline-block; font-size:30px; text-align: left;">
                  <h1><span class="marker">AKO</span> ang Simula.</h1>
                <h1>AKO ang Pagbabago.</h1>
                <h1>AKO ang Bayan.</h1>
                </div>
        
              </div>
              
            </v-col>

            <v-row>
              <v-col cols="12" sm="12" md="6" style="text-align: center;">
                <v-btn color="#FF5349" rounded="xl" size="x-large" class="ma-1">Join the Movement</v-btn>
              </v-col>
              <v-col cols="12" sm="12" md="6" style="text-align: center;">
                <v-btn rounded="xl" color="white"  size="x-large" class="ma-1"><span style="color:#FF5349">Learn Our Story</span></v-btn>
              </v-col>
            </v-row>

            <v-row class="text-center ma-5">
              <v-col md="4">
                <h1 style="color: orangered">50K+</h1>
                <div style="width:100%;">Active Members</div>
              </v-col>
              <v-col md="4">
                <h1 style="color: orangered">50K+</h1>
                <div style="width:100%;">Communities Reached</div>
              </v-col>
              <v-col md="4">
                <h1 style="color: orangered">50K+</h1>
                <div style="width:100%;">Policy Changes</div>
              </v-col>
            </v-row>      
          </div>
        </v-parallax>
   
        <div id="mission" class="text-center ma-7">
          <div class="d-flex flex-column ma-6 justify-center align-center">
         
            <v-row>
              <v-col style="width:100%;" class="mt-5" cols="12" sm="6" md="4" lg="4" xl="8">
                <div class="mt-14">
                    <p style="width:350px; line-height: 1.2; text-align: left; font-family: goulong; font-size: 25px; font-style: italic; font-weight: bold; color:#FF5349">"To cultivate a society that champions integrity, accountability, and social justice"</p>
                </div>

              </v-col>
              <v-col style="width:100%;" cols="12" sm="6" md="8" lg="8" xl="8">
                <div ><h3 style="text-align: center;"><b>OUR MISSION</b></h3></div>
                <br>
                <span  style="line-height: 1.2; font-size: 20px; width:350px;">
                  <p style="text-align: left; font-family: gravity; color: #6E7A7A;">At Reforma Pilipinas, our mission is to ignite a transformative revolution rooted in <span style="text-decoration: underline #FF5349;"><b>radical transparency</b></span>, people-
                  powered governance, and bold innovation. We strive to dismantle the entrenched systems that perpetuate
                  corruption and inequality, empowering every Filipino to reclaim their agency and redefine the political landscape.
                  Through active participation, we are committed to fostering an inclusive democracy where every voice is heard and
                  valued. Our mission is to cultivate a society that champions integrity, accountability, and social justice, ensuring that
                  the aspirations of our diverse populace are reflected in every decision made within the halls of power.</p>
                </span>
              </v-col>
            </v-row>
  
          </div>
            
    
          <div class="d-flex flex-column ma-8 justify-center align-center">
        

            
            <v-row>
              <v-col style="width:100%;" cols="12" sm="6" md="4" lg="4" xl="8">
                <div class="mt-14">
                  <p style="width:350px; line-height: 1.2; text-align: left; font-family: goulong; font-size: 25px; font-style: italic; font-weight: bold; color:#FF5349">"We see a Philippines that thrives on collaboration, where cultural diversity serves as a
                  unifying strength, and where the potential of each individual is fully realized in a society committed to the common
                  good."</p>
                </div>
           
              </v-col>
              <v-col style="width:100%;" cols="12" sm="6" md="8" lg="8" xl="8">
                <div><h3 style="text-align:center;"><b>OUR VISION</b></h3></div>
                <br>
                <span style="line-height: 1.2; font-size: 20px; width:350px;">
                  <p style="text-align: left; font-family: gravity; color: #6E7A7A;" >We envision a future Philippines where governance is not a privilege reserved for the elite, but a collective pursuit
                of justice and empowerment for all citizens. In this equitable society, transparency is the norm, fostering a culture of
                trust between the government and its people. Citizen assemblies and grassroots movements will flourish, creating
                a powerful network where ordinary Filipinos are actively shaping policies, championing their rights, and leading
                initiatives that propel our nation forward. We aspire to be a beacon of bold innovation, embracing unconventional
                solutions that address our unique challenges and position our nation as a global leader in democracy and
                progressive governance. We see a Philippines that thrives on collaboration, where cultural diversity serves as a
                unifying strength, and where the potential of each individual is fully realized in a society committed to the common
                good. Together, we will forge a path to a brighter, just, and thriving future for generations to come.</p>
                </span>
              </v-col>
            </v-row>

          </div>

          
          <div class="d-flex flex-column ma-8 justify-center align-center">
          

            <v-row>
              <v-col  style="width:100%;" cols="12" sm="6" md="4" lg="4" xl="8">
                <div class="mt-8">
                  <p class="pt-16" style="width:350px; line-height: 1.2; text-align: left; font-family: goulong; font-size: 25px; font-style: italic; font-weight: bold; color:#FF5349">"We represent the voice of the countless Filipinos who are fed up with rhetoric and empty
                promises."</p>
                </div>
                
              </v-col>
              <v-col style="width:100%;" cols="12" sm="6" md="8" lg="8" xl="8">
                  <div style="text-align: center"><h3><b>OUR MANIFESTO</b></h3></div>
                  <br>
                <span style="line-height: 1.2; font-size: 20px; width:350px;">
                  <p style="text-align: left; font-family: gravity; color: #6E7A7A;" >In a time when our nation stands at the precipice of disillusionment, enveloped by a relentless tide of political
                chaos, we, the founders and passionate members of Reforma Pilipinas, boldly declare our existence as a
                catalyst for unparalleled change. The current political environment is not merely a challenge; it is a battleground
                where the integrity of our democracy is threatened, and we, patriots with an indomitable spirit, refuse to stand
                idly by.
                Our Call to Action: We represent the voice of the countless Filipinos who are fed up with rhetoric and empty
                promises. We have seen the erosion of trust, the decay of institutions, and the rampant spread of corruption that
                suffocates our potential as a nation. This is our moment to disrupt the status quo, to dismantle complacency,
                and to ignite a movement that embraces integrity, justice, and genuine empowerment.
                </p>
                </span>
              </v-col>
            </v-row>




    
          </div>
     
          <!-- <div>
            <v-row>
              <v-col cols="12" sm="12" md="6">
                <v-img src="https://readdy.ai/api/search-image?query=Group%20of%20diverse%20citizens%20in%20town%20hall%20meeting%2C%20engaged%20discussion%2C%20people%20raising%20hands%2C%20community%20gathering%2C%20authentic%20grassroots%20democracy%20in%20action%2C%20natural%20lighting%2C%20documentary%20photography%20style%2C%20real%20people%20having%20meaningful%20conversations%20about%20policy&width=800&height=600&seq=mission1&orientation=landscape"></v-img>
              </v-col>
              <v-col cols="12" sm="12" md="6">
                <v-list
                  lines="three"
                  style="text-align: left;"
                  >
                  <v-list-item
                    class="wrap-text"
                    
                    title="Radical Transparency"
                    >
                    <v-list-item-subtitle class="wrap-text">
                      We demand a political revolution that
                      casts light on the darkness of secrets and deceit. Every transaction,
                      every decision made in the halls of power must be transparent and
                      available to the public. We will unleash an army of watchdogs and
                      champions of transparency, harnessing technology and grassroots
                      coalitions to ensure accountability at every level.
                    </v-list-item-subtitle>
                    <template v-slot:prepend="{ isSelected, select }">
                      <v-list-item-action start>
                        <v-btn
                          elevation="0"
                          class="ma-2"
                          color="#FF5349"
                          icon="mdi-wrench"
                        ></v-btn>
                      </v-list-item-action>
                    </template>
                  </v-list-item>
                  <v-list-item
                    title="People-Powered Governance"
                    >
                    <v-list-item-subtitle class="wrap-text">
                      Enough with the elitist politics that have long dictated our fate. 
                      We envision a new era where the voices of the marginalized, the youth, and the ordinary citizens 
                      are amplified and woven into the fabric of governance. We shall forge a robust network of citizen assemblies, 
                      summoning every Filipino to rise, engage, and reclaim their right to influence the destiny of our nation.
                    </v-list-item-subtitle>
                    <template v-slot:prepend="{ isSelected, select }">
                      <v-list-item-action start>
                        <v-btn
                          elevation="0"
                          class="ma-2"
                          color="#FF5349"
                          icon="mdi-wrench"
                        ></v-btn>
                      </v-list-item-action>
                    </template>
                  </v-list-item>
                  <v-list-item
                    title="Economic Prosperity and Equitable Distribution of Wealth"
                    >
                    <v-list-item-subtitle class="wrap-text">
                      Uphold economic prosperity as meaningful only when its benefits are shared by all Filipinos. 
                      Growth must create jobs, expand opportunities, and reduce inequality—not concentrate wealth among a few. 
                      RP promotes inclusive development through support for local industries, rural and urban economic balance, fair taxation, and people-centered economic policies so that national progress improves the lives of every Filipino.
                    </v-list-item-subtitle>
                    <template v-slot:prepend="{ isSelected, select }">
                      <v-list-item-action start>
                        <v-btn
                          elevation="0"
                          class="ma-2"
                          color="#FF5349"
                          icon="mdi-wrench"
                        ></v-btn>
                      </v-list-item-action>
                    </template>
                  </v-list-item>
                  <v-list-item
                    title="Unity Through Diversity"
                    >
                    <v-list-item-subtitle class="wrap-text">
                      We acknowledge that our strength lies in our differences. We are a tapestry of cultures, beliefs, and experiences. In this spirit, we will cultivate a coalition that transcends age, gender, and socioeconomic status. 
                      United in our diversity, we shall present a formidable front against the forces that seek to divide us for their gain.
                    </v-list-item-subtitle>
                    <template v-slot:prepend="{ isSelected, select }">
                      <v-list-item-action start>
                        <v-btn
                          elevation="0"
                          class="ma-2"
                          color="#FF5349"
                          icon="mdi-wrench"
                        ></v-btn>
                      </v-list-item-action>
                    </template>
                  </v-list-item>
                    <v-list-item
                    title="Restoration of Faith and Integrity"
                    >
                    <v-list-item-subtitle class="wrap-text">
                    Disillusionment has eroded the very fabric of our society. We are here to restore faith—not just in our leaders but in the essence of democracy itself. We will instate rigorous ethical standards, champion genuine leaders, and create a political environment where integrity is non-negotiable. No longer shall corruption tarnish our future. 
                    </v-list-item-subtitle>
                    <template v-slot:prepend="{ isSelected, select }">
                      <v-list-item-action start>
                        <v-btn
                          elevation="0"
                          class="ma-2"
                          color="#FF5349"
                          icon="mdi-wrench"
                        ></v-btn>
                      </v-list-item-action>
                    </template>
                  </v-list-item>

                  <v-list-item
                    title="Mobilizing the Silent Majority"
                    >
                    <v-list-item-subtitle class="wrap-text">
                    The time has come to awaken a sleeping giant—the vast majority of Filipinos who remain on the sidelines. We will implement large-scale campaigns that inform, inspire, and incite action. Every town, city, and barangay will be a hub of activism, driving a collective consciousness that will challenge the entrenched powers and demand change.

                    </v-list-item-subtitle>
                    <template v-slot:prepend="{ isSelected, select }">
                      <v-list-item-action start>
                        <v-btn
                          elevation="0"
                          class="ma-2"
                          color="#FF5349"
                          icon="mdi-wrench"
                        ></v-btn>
                      </v-list-item-action>
                    </template>
                  </v-list-item>

                  <v-list-item
                    title="Volunteerism and Bayanihan Spirit"
                    >
                    <v-list-item-subtitle class="wrap-text">
                    We recognize volunteerism and the Filipino bayanihan spirit as vital drivers of national transformation. True reform depends on citizens who willingly share their time, skills, and resources for the common good. This pillar promotes collective action, shared responsibility, and unity beyond political or social differences, empowering Filipinos to actively participate in nation-building as partners in creating lasting and meaningful change.
                    </v-list-item-subtitle>
                    <template v-slot:prepend="{ isSelected, select }">
                      <v-list-item-action start>
                        <v-btn
                          elevation="0"
                          class="ma-2"
                          color="#FF5349"
                          icon="mdi-wrench"
                        ></v-btn>
                      </v-list-item-action>
                    </template>
                  </v-list-item>
                </v-list>
              </v-col>
            </v-row>
          </div> -->
        </div>
        
   <div style="width: 100% !important; background-color: #FAFAFA;">
    
          <div class="pa-3 text-center text-white">
    
           
            <v-row class="ma-5">
              <v-col cols="12"><h3 style="color: black; text-align: left;">As Major Disruptors, We Stand on the Following Pillars:</h3></v-col>
              <v-col cols="12" md="4">
            <v-card
              link
              class="pa-5 zoom"
            >
              <v-card-title> 
                <v-btn
                  style="border-radius:10px; color:#FF5349;"
                  elevation="0"
                  class="my-3"
                  color="#FFE9CC"
                  icon="mdi-eye-outline"
                >
                </v-btn>
                  </v-card-title>
              <v-card-subtitle><h3>Radical Transparency</h3></v-card-subtitle>
              <v-card-text>
                <p style="  line-height: 1.5; color: gray;" :class="!truncateRA ? 'text-cut' : ''"> We demand a political revolution that
                      casts light on the darkness of secrets and deceit. Every transaction,
                      every decision made in the halls of power must be transparent and
                      available to the public. We will unleash an army of watchdogs and
                      champions of transparency, harnessing technology and grassroots
                      coalitions to ensure accountability at every level.</p>
                      <v-btn class="mt-2" @click="truncateRA = !truncateRA">Read {{ truncateRA ? 'less' : 'more' }}</v-btn>
              </v-card-text>
            </v-card>
          </v-col>
          <v-col cols="12" md="4">
            <v-card
              link
              class="pa-5 zoom"
            >
              <v-card-title> <v-btn
                        style="border-radius:10px; color:#FF5349;"
                        elevation="0"
                        class="my-3"
                        color="#FFE9CC"
                        icon="mdi-account-multiple-outline"
                      ></v-btn></v-card-title>
              <v-card-subtitle><h3>People-Powered Governance</h3></v-card-subtitle>
              <v-card-text>
                <p style="  line-height: 1.5; color: gray;" :class="!truncatePP ? 'text-cut' : ''">Enough with the elitist politics that have long dictated our fate. We envision a new era where the voices of the marginalized, the youth, and the ordinary citizens are amplified and woven into the fabric of governance. We shall forge a robust network of citizen assemblies, summoning every Filipino to rise, engage, and reclaim their right to influence the destiny of our nation.</p>
                 <v-btn class="mt-2" @click="truncatePP = !truncatePP">Read {{ truncatePP ? 'less' : 'more' }}</v-btn>
              </v-card-text>
            </v-card>
          </v-col>
          <v-col cols="12" md="4">
            <v-card
              link
              class="pa-2 zoom"
            >
              <v-card-title> <v-btn
                        style="border-radius:10px; color:#FF5349;"
                        elevation="0"
                        class="my-3"
                        color="#FFE9CC"
                        icon="mdi-finance"
                      ></v-btn></v-card-title>
              <v-card-subtitle class="wrap-text"><h3>Economic Prosperity and Equitable Distribution of Wealth</h3></v-card-subtitle>
              <v-card-text>
                <p style="  line-height: 1.5; color: gray;" :class="!truncateE ? 'text-cut' : ''">Uphold economic prosperity as meaningful only when its benefits are shared by all Filipinos. Growth must create jobs, expand opportunities, and reduce inequality—not concentrate wealth among a few. RP promotes inclusive development through support for local industries, rural and urban economic balance, fair taxation, and people-centered economic policies so that national progress improves the lives of every Filipino.</p>
                <v-btn class="mt-2" @click="truncateE = !truncateE">Read {{ truncateE ? 'less' : 'more' }}</v-btn>
              </v-card-text>
            </v-card>
          </v-col>
            </v-row>
            <v-row style="margin-top:20px;" class="ma-5">
              <v-col cols="12" md="3">
            <v-card
              link
              class="pa-2 zoom"
            >
              <v-card-title> <v-btn
                        style="border-radius:10px; color:#FF5349;"
                        elevation="0"
                        class="my-3"
                        color="#FFE9CC"
                        icon="mdi-heart-outline"
                      ></v-btn></v-card-title>
              <v-card-subtitle><h3>Unity Through Diversity</h3></v-card-subtitle>
              <v-card-text>
                <p style="  line-height: 1.5; color: gray;" :class="!truncateU ? 'text-cut' : ''">
                  We acknowledge that our strength lies in our differences. We are a tapestry of cultures, beliefs, and experiences. In this spirit, we will cultivate a coalition that transcends age, gender, and socioeconomic status. United in our diversity, we shall present a formidable front against the forces that seek to divide us for their gain. 
                </p>
                <v-btn class="mt-2" @click="truncateU = !truncateU">Read {{ truncateU ? 'less' : 'more' }}</v-btn>
              </v-card-text>
            </v-card>
          </v-col>
          <v-col cols="12" md="3">
            <v-card
              link
              class="pa-2 zoom"
            >
              <v-card-title> <v-btn
                        style="border-radius:10px; color:#FF5349;"
                        elevation="0"
                        class="my-3"
                        color="#FFE9CC"
                        icon="mdi-shield-check-outline"
                      ></v-btn></v-card-title>
              <v-card-subtitle class="wrap-text"><h3>Restoration of Faith and Integrity</h3></v-card-subtitle>
              <v-card-text>
                <p  style="  line-height: 1.5; color: gray;" :class="!truncateR ? 'text-cut' : ''">Disillusionment has eroded the very fabric of our society. We are here to restore faith—not just in our leaders but in the essence of democracy itself. We will instate rigorous ethical standards, champion genuine leaders, and create a political environment where integrity is non-negotiable. No longer shall corruption tarnish our future.</p>
                <v-btn class="mt-2" @click="truncateR = !truncateR">Read {{ truncateR ? 'less' : 'more' }}</v-btn>
              </v-card-text>
            </v-card>
          </v-col>
          <v-col cols="12" md="3">
            <v-card
              link
              class="pa-2 zoom"
            >
              <v-card-title> <v-btn
                        style="border-radius:10px; color:#FF5349;"
                        elevation="0"
                        class="my-3"
                        color="#FFE9CC"
                        icon="mdi-bullhorn-outline"
                      ></v-btn></v-card-title>
              <v-card-subtitle><h3>Mobilizing the Silent Majority</h3></v-card-subtitle>
              <v-card-text>
                <p style="  line-height: 1.5; color: gray;" :class="!truncateM ? 'text-cut' : ''">The time has come to awaken a sleeping giant—the vast majority of Filipinos who remain on the sidelines. We will implement large-scale campaigns that inform, inspire, and incite action. Every town, city, and barangay will be a hub of activism, driving a collective consciousness that will challenge the entrenched powers and demand change.</p>
                <v-btn class="mt-2" @click="truncateM = !truncateM">Read {{ truncateM ? 'less' : 'more' }}</v-btn>
              </v-card-text>
            </v-card>
          </v-col>

                    <v-col cols="12" md="3">
            <v-card
              link
              class="pa-2 zoom"
            >
              <v-card-title> <v-btn
                        style="border-radius:10px; color:#FF5349;"
                        elevation="0"
                        class="my-3"
                        color="#FFE9CC"
                        icon="mdi-bullhorn-outline"
                      ></v-btn></v-card-title>
              <v-card-subtitle class="wrap-text"><h3>Volunteerism and Bayanihan Spirit</h3></v-card-subtitle>
              <v-card-text>
                <p style="  line-height: 1.5; color: gray;" :class="!truncateV ? 'text-cut' : ''">We recognize volunteerism and the Filipino bayanihan spirit as vital drivers of national transformation. True reform depends on citizens who willingly share their time, skills, and resources for the common good. This pillar promotes collective action, shared responsibility, and unity beyond political or social differences, empowering Filipinos to actively participate in nation-building as partners in creating lasting and meaningful change.
                </p>
                <v-btn class="mt-2" @click="truncateV = !truncateV">Read {{ truncateV ? 'less' : 'more' }}</v-btn>
              </v-card-text>
            </v-card>
          </v-col>

            </v-row>

          </div>
        </div>
        
        <div id="stories" style="width: 100% !important;" class="gradient d-flex flex-column justify-center align-center" >
          <div class="pa-3">
               <v-row>
            <v-col class="mt-3"  cols="12" sm="12" md="8" lg="8" xl="8">
           
                <v-list style="background-color: transparent !important;">
                  <div class="px-4">
                    <p style="font-size: 35px;  margin-bottom: -0.5em;  margin-top: -0.5em;"><b>The Meaning Behind</b></p>
                    <p style="font-size: 35px; color: #FF5349; "><b>Our Colors</b></p>
                  </div>
              
                  <v-list-item
                    >
                    <v-list-item-title>
                      <b>Black as Foundation</b>
                    </v-list-item-title>
                    <v-list-item-subtitle class="wrap-text pt-1">
                      Unyielding will, strength, and the cleansing of the shadows of the past. It is our collective resolve.
                    </v-list-item-subtitle>
                    <template v-slot:prepend="{ isSelected, select }">
                      <v-list-item-action start>
                        <v-btn
                          elevation="0"
                          class="ma-2"
                          color="black"
                          icon=""
                        ></v-btn>
                      </v-list-item-action>
                    </template>
                  </v-list-item>
                
                  <v-list-item
                    >
                    <v-list-item-title>
                      <b>Orange as Our Spark</b>
                    </v-list-item-title>
                    <v-list-item-subtitle class="wrap-text pt-1">
                      Optimism, energy, and inclusion. It represents the surge of innovation and the pulse of action.
                    </v-list-item-subtitle>
                    <template v-slot:prepend="{ isSelected, select }">
                      <v-list-item-action start>
                        <v-btn
                          elevation="0"
                          class="ma-2"
                          color="#FF5349"
                          icon=""
                        ></v-btn>
                      </v-list-item-action>
                    </template>
                  </v-list-item>
              </v-list>
              
            </v-col>
            
            <v-col class="pa-5" cols="12" sm="12" md="4" lg="4" xl="8">
                 <div style="justify-content: center !important; display: flex;
  align-items: center !important;   height: 250px;">
                              <div style="font-size: 25px; font-family: gravity; font-style: italic; color:white; font-weight: bold;" class="circle-multiline"><div class="pt-6">Steadfast<br> Resolve<br> + <br> Bright <br> Possibility</div></div>
              </div>
             

            </v-col>

           
          </v-row>
          </div>
       
        </div>

        <div class="ma-7">
            <v-row>
              <v-col style="width:100%;" cols="12" sm="6" md="4" lg="4" xl="8">
                <div class="mt-8" style="justify-content: center !important; display: flex;
  align-items: center !important;   height: 250px;">
                            <div class="blackhole-blk">
        <div class="megna-blk">
          <div class="black-blk"></div>
        </div>
      </div>
                </div>
            

              </v-col>
              <v-col style="width:100%; line-height: 1.2; font-size: 20px; width:350px;" cols="12" sm="6" md="8" lg="8" xl="8" >
                       <div style="text-align: center"><b>BLACK AS OUR FOUNDATION</b></div>
                  <br>
                <span style="line-height: 1.2; font-size: 20px; width:350px; text-align: left; font-family: gravity; color: #6E7A7A;">
                    <p>- Resolve and Strength – Black embodies the unyielding will of Reforma Pilipinas. It speaks to our determination to confront entrenched interests, to stand firm against corruption, and to refuse appeasement when our democratic ideals are under threat. </p>
                    <p>- Solidarity and Unity – In many cultures, black is the color of collective resolve. By adopting black as our core hue, we signal that every member—regardless of background—stands together, shoulder to shoulder, in pursuit of genuine reform.</p>
                    <p>- Cleansing Shadows of the Past – Black also carries the weight of history’s darker chapters. It reminds us of the corruption, inertia, and disillusionment we seek to leave behind. Embracing black honors the struggles that came before and galvanizes us to ensure those mistakes are never repeated.</p>
                </span>
              </v-col>
          
            </v-row>


                       <v-row>
              <v-col style="width:100%;" cols="12" sm="6" md="4" lg="4" xl="8">
                <div  style="justify-content: center !important; display: flex;
  align-items: center !important;   height: 250px;">
                            <div class="blackhole-org">
        <div class="megna-org">
      
        </div>
      </div>
                </div>
            

              </v-col>
              <v-col style="width:100%; line-height: 1.2; font-size: 20px; width:350px;" cols="12" sm="6" md="8" lg="8" xl="8" >
                       <div style="text-align: center"><b>ORANGE AS OUR SPARK</b></div>
                  <br>
                <span style="line-height: 1.2; font-size: 20px; width:350px; text-align: left; font-family: gravity; color: #6E7A7A;">
                   <p>- Vision and Optimism – A flash of orange cuts through the darkness: it’s the dawn of new ideas, the warmth of fresh hope, and the promise that change is not only possible but within our grasp.</p>
                    <p>- Energy and Action – Orange is synonymous with movement and momentum. It’s the surge of creativity, the pulse of innovation, and the call to every Filipino to rise, speak up, and get involved.</p>
                    <p>- Inclusivity and Accessibility – Whereas black can be austere, orange feels approachable and human. It invites dialogue, bridges generations, and reminds us that reform is a collective, life-affirming endeavor.</p>
                  </span>
              </v-col>
          
            </v-row>


                               <v-row class="mt-16">
              <v-col style="width:100%;" cols="12" sm="6" md="4" lg="4" xl="8">
                <div class="mt-8" style="justify-content: center !important; display: flex;
  align-items: center !important;   height: 250px;">
                            <div class="blackhole-ref">
        <div class="megna-ref">
      <div class="black-ref"></div>
        </div>
      </div>
                </div>
            

              </v-col>
              <v-col style="width:100%; line-height: 1.2; font-size: 20px; width:350px;" cols="12" sm="6" md="8" lg="8" xl="8" >
                       <div style="text-align: center"><b>THE COMBINED IMPACT</b></div>
                  <br>
                <span style="line-height: 1.2; font-size: 20px; width:350px; text-align: left; font-family: gravity; color: #6E7A7A;">
                   By pairing black with a hint of orange, Reforma Pilipinas crafts a visual identity that is at once stern and hopeful. Black provides the bedrock of our convictions—unyielding, principled, and mindful of history’s lessons—while orange sparks the forward thrust of our mission: energizing citizens, illuminating pathways to progress, and celebrating the creative spirit that will define our nation’s next chapter. Together, these colors tell a story of steadfast resolve powered by bright possibility—a perfect emblem for a movement determined to forge a new path.
                  </span>
              </v-col>
          
            </v-row>
     
        </div>

       
        <v-container class="text-center">
          <div class="d-flex flex-column ma-8 justify-center align-center">
            <div><h1>Real Stories, Real Change</h1></div>
            <v-col cols="12" sm="12" md="6"><p>Hear from citizens who turned their frustration into action and achieved meaningful results in their communities.</p></v-col>
          </div>
          <div>  
               <div class="ma-3">
            <v-row>
              <v-col cols="12" sm="12" md="12" lg="4" xl="12"> <h1 style="color: #FF5349;">Editorial</h1></v-col>
                 <v-col cols="12" sm="12" md="12" lg="6" xl="12">
              <v-img class="ma-3" style="max-height:1000px;" src="/story.jpg"></v-img>
            </v-col>
            </v-row>
         
        </div>
          </div>
        </v-container>
         <v-container  style="background-color: lightgray" fluid class="text-center">
       
          <div>  
            <v-carousel
             
              hide-delimiters
              height="auto"
              >
              <v-carousel-item style="height:100%;"
              >
                <v-row style="height: 100%;" align="center" justify="center" no-gutters>
                  <v-col align="center" class="pa-3" justify="center" cols="12" sm="4" md="4">
                    <v-img rounded="circle" style="max-width:180px;" src="https://readdy.ai/api/search-image?query=Professional%20portrait%20of%20Asian%20American%20woman%20in%20her%2030s%2C%20small%20business%20owner%2C%20confident%20smile%2C%20professional%20but%20approachable%2C%20natural%20lighting%2C%20authentic%20entrepreneur%20and%20community%20leader%2C%20simple%20background&width=400&height=400&seq=testimonial3&orientation=squarish"></v-img>
                  </v-col>
                  <v-col cols="12" sm="12" md="8" align="left">
                    <div style="font-size: 20px;">
                    <p><v-icon style="color:#FF5349">mdi-format-quote-open</v-icon></p>
                    <br>
                    <p>Empty promises about supporting small businesses were all we heard. Reforma Pilipinas helped us organize local business owners to demand real policy changes. We now have the support and resources we need to thrive.</p>
                    <br>
                    <p><b>Sarah Chen</b></p>
                    <p>Small Business Owner</p>
                    <p style="color:#FF5349">Portland, OR</p>
                    </div>
                  </v-col>
                </v-row>
              </v-carousel-item>

              <v-carousel-item
                >
                <v-row style="height: 100%;"  align="center" justify="center" no-gutters>
                <v-col align="center" justify="center" cols="12" sm="4" md="4">
                  <v-img rounded="circle" style="max-width: 180px;" class="ma-3" src="https://readdy.ai/api/search-image?query=Professional%20portrait%20of%20African%20American%20man%20in%20his%2050s%2C%20factory%20worker%20and%20military%20veteran%2C%20determined%20expression%2C%20wearing%20casual%20shirt%2C%20natural%20lighting%2C%20authentic%20grassroots%20activist%2C%20simple%20background&width=400&height=400&seq=testimonial2&orientation=squarish"></v-img>
                </v-col>
                <v-col cols="12" sm="8" md="8"align="left" justify="left">
                  
                  <div style="font-size: 20px;">
                  <p><v-icon style="color:#FF5349">mdi-format-quote-open</v-icon></p>
                  <br>
                  <p>I served this country, but when I came home, our leaders forgot about veterans like me. Reforma Pilipinas gave me a platform to fight for veteran healthcare reform. Now my fellow veterans are getting the care they earned.
                  </p>
                  <br>
                  <p><b>James Thompson</b></p>
                  <p>Factory Worker & Veteran</p>
                  <p style="color:#FF5349">Detroit, MI</p>
                  </div>
                </v-col>
                </v-row>
              </v-carousel-item>
            </v-carousel>
          </div>
        </v-container>

   

  <v-container fluid>
    <div id="join" class="pa-3 text-center d-flex flex-column justify-center align-center">
    <h1>Join the Movement</h1>
      <v-col style="text-align: center;" justify="center" align="center" class="text-center" cols="12" sm=12 md="6"><h3>Ready to turn your frustration into action? Become a member of Reforma Pilipinas and help create the change your community needs.</h3></v-col>
    </div>
    <v-row>
      <v-col cols="12" sm="12" md="6">
        <v-col style="background-color:#FEF2F2 !important; border-radius:10px;"cols="12" sm="12" md="12">
          <div style="width:100%;" class="pa-5">
            <h2>Why Join Reforma Pilipinas?</h2>
              <li class="ma-3">
                <b>Direct Impact:</b> Your voice will be heard by decision-makers who can create real change
              </li>
              <li class="ma-3">
                <b>Community Network:</b> Connect with like-minded citizens in your area
              </li>
              <li class="ma-3">
                <b>Training & Resources:</b> Learn effective advocacy strategies and tools
              </li>
              <li class="ma-3">
                <b>Regular Updates:</b> Stay informed about policy changes and opportunities
              </li>
          </div>
        </v-col>

        <v-col class="mt-8" style="background-color:#f9fafb; border-radius:10px;"cols="12" sm="12" md="12">
          <div style="width:100%;" class="pa-5">
            <h2>Why Join Reforma Pilipinas?</h2>
              <li class="ma-3">
                <b>Direct Impact:</b> Your voice will be heard by decision-makers who can create real change
              </li>
              <li class="ma-3">
                <b>Community Network:</b> Connect with like-minded citizens in your area
              </li>
              <li class="ma-3">
                <b>Training & Resources:</b> Learn effective advocacy strategies and tools
              </li>
              <li class="ma-3">
                <b>Regular Updates:</b> Stay informed about policy changes and opportunities
              </li>
          </div>
        </v-col>
      </v-col>

      <!-- form -->
      <v-col cols="12" sm="12" md="6" style="background-color:#f9fafb;">
        <v-row style="margin:0px; padding:0px;">
          
      <v-col cols="12" sm="12" md="4">
          <v-text-field
        color="primary"
        label="First Name"
        hide-details="auto"
      ></v-text-field>
        </v-col>
        <v-col cols="12" sm="12" md="4">
        <v-text-field
          color="primary"
          label="Middle Name"
          hide-details="auto"
        ></v-text-field>
      </v-col>
      <v-col cols="12" sm="12" md="4">
        <v-text-field
          color="primary"
          label="Last Name"
          hide-details="auto"
        ></v-text-field>
      </v-col>
      <!-- <v-col cols="12" sm="12" md="1">
        <v-text-field
          color="primary"
          label="Suffix"
          hide-details="auto"
        ></v-text-field> -->
      <!-- </v-col> -->
      <v-col cols="12" sm="12" md="3">
        <v-text-field
          color="primary"
          label="Nickname"
          hide-details="auto"
        ></v-text-field>
      </v-col>
      <!-- <v-col cols="12" sm="12" md="3">
        <v-text-field
          color="primary"
          label="Telephone Number"
          hide-details="auto"
        ></v-text-field>
      </v-col> -->
      <v-col cols="12" sm="12" md="4">
        <v-text-field
          color="primary"
          label="Cellphone Number"
          hide-details="auto"
        ></v-text-field>
      </v-col>
        <v-col cols="12" sm="12" md="5">
          <v-text-field
        color="primary"
        label="Email"
        hide-details="auto"
      ></v-text-field>
      </v-col>
        <v-col cols="12" sm="12" md="3">
          <v-select
        color="primary"
        label="Gender"
        hide-details="auto"
        :items="['Male', 'Female', 'Prefer Not To Say']"
      ></v-select>
        </v-col>
        <v-col cols="12" sm="12" md="3">
          <v-select
        color="primary"
        label="Civil Status"
        hide-details="auto"
        :items="['Single', 'Married', 'Separated', 'Widow']"
      ></v-select>
        </v-col>
        <v-col cols="12" sm="12" md="6">
          <v-text-field
        color="primary"
        label="Name of Spouse, if married"
        hide-details="auto"
      ></v-text-field>
        </v-col>
        <v-col cols="12" sm="12" md="4">
          <v-text-field
        color="primary"
        label="Date Of Birth"
        hide-details="auto"
      ></v-text-field>
        </v-col>
        <v-col cols="12" sm="12" md="2">
          <v-text-field
        color="primary"
        label="Age"
        hide-details="auto"
      ></v-text-field>
        </v-col>
  
        <v-col cols="12" sm="12" md="3">
          <v-text-field
        color="primary"
        label="Place of Birth"
        hide-details="auto"
      ></v-text-field>
        </v-col>
        <v-col cols="12" sm="12" md="3">
          <v-text-field
        color="primary"
        label="Religion"
        hide-details="auto"
      ></v-text-field>
        </v-col>
        <v-col cols="12" sm="12" md="2">
          <v-text-field
        color="primary"
        label="Number"
        hide-details="auto"
      ></v-text-field>
        </v-col>
        <v-col cols="12" sm="12" md="5">
          <v-text-field
        color="primary"
        label="Street/Purok No."
        hide-details="auto"
      ></v-text-field>
        </v-col>
        <v-col cols="12" sm="12" md="5">
          <v-text-field
        color="primary"
        label="Subdivision/Sitio/Neighborhood"
        hide-details="auto"
      ></v-text-field>
        </v-col>

        <v-col cols="12" sm="12" md="3">
          <v-text-field
        color="primary"
        label="Barangay"
        hide-details="auto"
      ></v-text-field>
        </v-col>
        <v-col cols="12" sm="12" md="3">
          <v-text-field
        color="primary"
        label="City/Municipality"
        hide-details="auto"
      ></v-text-field>
        </v-col>
        <v-col cols="12" sm="12" md="3">
          <v-text-field
        color="primary"
        label="Province"
        hide-details="auto"
      ></v-text-field>
        </v-col>
        <v-col cols="12" sm="12" md="3">
          <v-text-field
        color="primary"
        label="District"
        hide-details="auto"
      ></v-text-field>
        </v-col>
        
        <v-row style="padding:0px; margin:0px;">
          <v-col cols="12" sm="12" md="12"><p>Issues You Care About (Select all that apply)</p></v-col>
          <v-col cols="6" sm="6" md="6">
           
            <v-checkbox
     
            color="red"
            label="Healthcare Reform"
            value="red"
            hide-details
          ></v-checkbox>
          <v-checkbox
     
            color="red"
            label="Infrastructure"
            value="red"
            hide-details
          ></v-checkbox>
          <v-checkbox
            color="red"
            label="Housing Rights"
            value="red"
            hide-details
          ></v-checkbox>
          <v-checkbox
      
            color="red"
            label="Criminal Justice Reform"
            value="red"
            hide-details
          ></v-checkbox>
          
          </v-col>
          <v-col cols="6" sm="6" md="6">
            <v-checkbox
       
            color="red"
            label="Education Funding"
            value="red"
            hide-details
          ></v-checkbox>
          <v-checkbox
       
            color="red"
            label="Veterans Affairs"
            value="red"
            hide-details
          ></v-checkbox>
          <v-checkbox
      
            color="red"
            label="Environmental Protection"
            value="red"
            hide-details
          ></v-checkbox>
          <v-checkbox
  
            color="red"
            label="Economic Justice"
            value="Economic Justice"
            hide-details
          ></v-checkbox>
          
          </v-col>
        </v-row>
        <!-- <v-col cols="12" sm="12" md="12">
          <v-text-field
        color="primary"
        label="Email"
        hide-details="auto"
      ></v-text-field>
        </v-col> -->
        <v-col cols="12" sm="12" md="12">
          <v-textarea
      label="What motivates you to join"
      name="input-7-1"
      variant="filled"
      hide-details="auto"
      auto-grow
    ></v-textarea>
    
      </v-col>
        <v-col cols="12" sm="12" md="12">
          <v-btn color="#DC2626" size="x-large" block>Join Reforma Pilipinas</v-btn>
        </v-col>
        </v-row>
        
      </v-col>
    </v-row>
  </v-container>
  <v-container class="text-white" fluid style="background-color:black;">
    <v-row style="margin-top:50px;">
      <v-col cols="12" sm="12" md="6">
        <v-col cols=12 sm="12" md="12" style="margin:0px; padding:0px;"><h3 class="pa-2">Reforma Pilipinas</h3></v-col>
        <v-col cols=12 sm="12" md="12" style="margin:0px; padding:0px;"><p class="pa-2">Empowering everyday citizens to create meaningful change in their communities through organized advocacy and grassroots action.</p></v-col>
        
        <v-col style="margin:0px; padding:0px;" cols=12 sm="12" md="12">
          <div class="pa-2">
            <v-btn
                  elevation="0"
                  class="mr-3"
                  color="#FF5349"
                  icon="mdi-facebook"
                  size="small"
                ></v-btn>
                <v-btn
                  elevation="0"
                  class="mr-3"
                  color="#FF5349"
                  icon="mdi-twitter"
                    size="small"
                ></v-btn>
                <v-btn
                
                  elevation="0"
                  class="mr-3"
                  color="#FF5349"
                  icon="mdi-instagram"
                    size="small"
                ></v-btn>
                <v-btn
                
                elevation="0"
                class="mr-3"
                color="#FF5349"
                icon="mdi-linkedin"
                  size="small"
              ></v-btn>
          </div>
  
                
        </v-col>
      </v-col>
      <v-col cols="12" sm="12" md="6">
        <v-row>
          <v-col cols="12" sm="12" md="6">
          <h4>Get Involved</h4>
          <p>Become A Member</p>
          <p>Volunteer</p>
          <p>Start A Campaign</p>
          <p>Donate</p>
        </v-col>
        <v-col cols="12" sm="12" md="6">
          <h4>Resources</h4>
          <p>Advocacy Training</p>
          <p>Policy Updates</p>
          <p>Success Stories</p>
          <p>Contact Us</p>
        </v-col>
        </v-row>
 
      </v-col>
    </v-row>
    
    <hr style="margin-top:3em;">
    <v-row class="py-5">
      <v-col>© 2024 Reforma Pilipinas. All rights reserved.</v-col>
      <v-col></v-col>
    </v-row>
  </v-container>
      </v-main>
    </v-layout>
</template>


<script>
import { ref, nextTick } from 'vue'
  export default {
    data () {
      return {
        path: '',
        truncateU: false,
        truncateR: false,
        truncateM: false,
        truncateV: false,
        truncateRA: false,
        truncatePP: false,
        truncateE: false
      }
    },
    mounted () {
    var marker = document.querySelector('.marker')
    var widthGain = 1; // 1 default
    var heightGain = 1; // 1 default
    var width = marker.offsetWidth,
      height = 2 * marker.offsetHeight,
      ns = "http://www.w3.org/2000/svg";
    var svg = document.createElementNS(ns, "svg");
    svg.style.width = width
    svg.style.height = height
    svg.style.transform = "scale(" + (2 * widthGain * width) / height + "," + heightGain + ")"
    svg.setAttribute('width', width)
    svg.setAttribute('height', height)
    svg.setAttribute('viewBox', "-1 -1 2 2")
    marker.appendChild(svg)
    this.path = document.createElementNS(ns, "path")
    this.path.setAttribute('pathLength', 100)
    this.path.setAttribute('vector-effect', 'non-scaling-stroke')
    svg.appendChild(this.path)
    this.setCircle(false);
    this.setCircle(true)
  },
  methods: {
    nextTick,
   scrollTo(id) {
      const yOffset = -100; 
      const element = document.getElementById(id);
      const y = element.getBoundingClientRect().top + window.scrollY + yOffset;
      this.nextTick(() =>  window.scrollTo({top: y, behavior: 'smooth'}))
     
   },
    setCircle(show_element) {
      if (show_element) {
        this.path.style.visibility = 'visible'
      } else {
        this.path.style.visibility = 'hidden'
      }
      
      var pathLength = 1000 * this.path.getTotalLength();
  
      this.path.setAttribute('d', this.circlePath(0.03,0.04,115,120,0.3,0.4))
      this.path.setAttribute('stroke-dasharray', pathLength)
      this.path.setAttribute('stroke-dashoffset', pathLength)
    },
    circlePath(dr_min, dr_max, θ0_min, θ0_max, dθ_min, dθ_max) {
      var c = 0.551915024494,
        β = Math.atan(c),
        d = Math.sqrt(c * c + 1 * 1),
        r = 0.9,
        θ = ((θ0_min + Math.random() * (θ0_max - θ0_min)) * Math.PI) / 180,
        path = "M";

      path += [r * Math.sin(θ), r * Math.cos(θ)];
      path += " C" + [d * r * Math.sin(θ + β), d * r * Math.cos(θ + β)];

      for (var i = 0; i < 4; i++) {
        θ += (Math.PI / 2) * (1 + dθ_min + Math.random() * (dθ_max - dθ_min));
        r *= 1 + dr_min + Math.random() * (dr_max - dr_min);
        path +=
          " " +
          (i ? "S" : "") +
          [d * r * Math.sin(θ - β), d * r * Math.cos(θ - β)];
        path += " " + [r * Math.sin(θ), r * Math.cos(θ)];
      }
      console.log(path)
      return path;
    }

  }
  }

</script>
<style>
  .wrap-text {
    -webkit-line-clamp: unset !important;
    white-space: normal;
  }
  .v-toolbar__prepend{
    margin: 0px !important;

  }
  .v-card{
  
    border-radius: 20px;
    text-align: left;
  }
  .v-card-subtitle{
    color: black !important;
  }
  .zoom {

  transition: transform .2s; /* Animation */

}
  .zoom:hover {
    z-index: 1000;
    transform: scale(1.2); /* (150% zoom - Note: if the zoom is too large, it will go outside of the viewport) */
  }

  /* Marker styling */
  .marker {
    position: relative;
    margin: 0 40px;
    text-decoration: none;
  }
  .marker svg {
    position: absolute;
    left: 0;
    top: -50%;
    right: 0;
    margin-left: auto;
    margin-right: auto;
    pointer-events: none;
  }
  .marker path {
    animation: draw 4s infinite;
    stroke-width: 3;
    stroke: #FFAE42;
    fill: none;
    stroke-linecap: round;
  }

  .gradient {
    background: #FFF;
    background: linear-gradient(90deg,rgba(42, 123, 155, 1) 0%, rgba(255, 255, 255, 1) 0%, rgba(122, 6, 0, 1) 100%);
  }

  @keyframes draw {
    100% {
      stroke-dashoffset: 0;
    }
  }

  @font-face {
    font-family: gravity;
    src: url('/gravity-book.ttf');
  }
  @font-face {
    font-family: goulong;
    src: url('/goulong.ttf');
  }
  .circle-multiline {
    display: table-cell;
    height: 250px;
    width: 250px;
    text-align: center;
    vertical-align: middle;
    border-radius: 50%;
    border: solid 3px;
    border-color: #FF5349;
}
html { scroll-behavior: smooth; }
.v-icon--size-default {
  color: red
}
.text-cut {
  line-clamp: 4;
  display: -webkit-box;
  -webkit-line-clamp: 4;
  -webkit-box-orient: vertical;  
  overflow: hidden;
}

.blackhole-blk {
  width: 10em;
  height: 10em;
  /* background-color: red; */
}

.blackhole-blk .megna-blk {
  width: 100%;
  height: 100%;
  border-radius: 100%;
  background: linear-gradient(white, white, white);
  /* box-shadow: 0 0 60px 30px rgba(255, 175, 83, 0.7); */

  display: flex;
  justify-content: center;
  align-items: center;
  filter: blur(5px);
}

.blackhole-blk .black-blk {
  width: 90%;
  height: 90%;
  border-radius: 45% 50% 50% 50%;
  background-color: black;
  transform: rotate(0deg);
  animation: hole 0.1s linear infinite normal;
}

@keyframes hole {
  100% {
    transform: rotate(360deg);
  }
}

.blackhole-org {
  width: 10em;
  height: 10em;
  /* background-color: red; */
}

.blackhole-org .megna-org {
  width: 100%;
  height: 100%;
  border-radius: 100%;
  background: linear-gradient(#ff4500, #ff4500, #ff9900);
  /* box-shadow: 0 0 60px 30px rgba(255, 175, 83, 0.7); */
  box-shadow: 0 0 60px 30px #fcbd3e, /* inner white */ 0 0 100px 60px #fd7a4d,
    /* middle magenta */ 0 0 100px 20px #ff0b6b; /* outer cyan */
  display: flex;
  justify-content: center;
  align-items: center;
  filter: blur(5px);
}

.blackhole-org .black-org {
  width: 90%;
  height: 90%;
  border-radius: 45% 50% 50% 50%;
  background-color: black;
  transform: rotate(0deg);
  animation: hole 0.1s linear infinite normal;
}

@keyframes hole {
  100% {
    transform: rotate(360deg);
  }
}

*,
::before,
::after {
  box-sizing: border-box;
}

html,
body {
  margin: 0;
  padding: 0;
  height: 100%;
  background-color: white;
}

.container {
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
}

.blackhole-ref {
  width: 10em;
  height: 10em;
  /* background-color: red; */
}

.blackhole-ref .megna-ref {
  width: 100%;
  height: 100%;
  border-radius: 100%;
  background: linear-gradient(#ff4500, #ff4500, #ff9900);
  /* box-shadow: 0 0 60px 30px rgba(255, 175, 83, 0.7); */
  box-shadow: 0 0 60px 30px #fcbd3e, /* inner white */ 0 0 100px 60px #fd7a4d,
    /* middle magenta */ 0 0 100px 20px #ff0b6b; /* outer cyan */
  display: flex;
  justify-content: center;
  align-items: center;
/*   filter: blur(5px); */
}

.blackhole-ref .black-ref {
  width: 90%;
  height: 90%;
  border-radius: 50% 50% 50% 50%;
  background-color: black;
  transform: rotate(0deg);
  animation: pulse 0.1s linear infinite normal;
  content:url(https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSqZt0s-HGM7YqCsn7Y_g5c1WakV8G5pjHZyA&s);
}

@keyframes hole {
  100% {
    transform: rotate(360deg);
  }
}


</style>
