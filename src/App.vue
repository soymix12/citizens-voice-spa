<script setup></script>

<template>
    <v-layout>
      <v-app-bar
        color="black"
        height="100"
        >
        <template v-slot:prepend>
          <div  style="width:100px; margin:0px !important; padding:0px !important;"><v-img class="ma-3" style="height:100%; width: 100%;" src="/icon.png"></v-img></div>
        </template>
 
        <v-app-bar-title v-if="!this.$vuetify.display.mobile" class="d-flex justify-center flex-row">
          <v-btn>Our Mission</v-btn>
          <v-btn>Stories</v-btn>
          <v-btn>Impact</v-btn>
          <v-btn>Get Involved</v-btn>
        </v-app-bar-title>

        <template v-slot:append>
          <v-btn class="mr-3" style="background-color:#FF5349" rounded="xl"><span style="color:white">Join Now</span></v-btn>
        </template>
      </v-app-bar>

      <v-main>
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
        
        <v-container class="text-center">
          <div class="d-flex flex-column ma-8 justify-center align-center">
            <div><h1>Our Mission</h1></div>
            <v-col cols="12" sm="12" md="8" lg="8" xl="8">
              <p style="width:100%;">
                At Reforma Pilipinas, our mission is to ignite a transformative revolution rooted in radical transparency, people-
                powered governance, and bold innovation. We strive to dismantle the entrenched systems that perpetuate
                corruption and inequality, empowering every Filipino to reclaim their agency and redefine the political landscape.
                Through active participation, we are committed to fostering an inclusive democracy where every voice is heard and
                valued. Our mission is to cultivate a society that champions integrity, accountability, and social justice, ensuring that
                the aspirations of our diverse populace are reflected in every decision made within the halls of power.
              </p>
            </v-col>
          </div>

          <div class="d-flex flex-column ma-8 justify-center align-center">
            <div><h1>Our Vision</h1></div>
            <v-col cols="12" sm="12" md="8" lg="8" xl="8">
              <p style="width:100%;">
                We envision a future Philippines where governance is not a privilege reserved for the elite, but a collective pursuit
                of justice and empowerment for all citizens. In this equitable society, transparency is the norm, fostering a culture of
                trust between the government and its people. Citizen assemblies and grassroots movements will flourish, creating
                a powerful network where ordinary Filipinos are actively shaping policies, championing their rights, and leading
                initiatives that propel our nation forward. We aspire to be a beacon of bold innovation, embracing unconventional
                solutions that address our unique challenges and position our nation as a global leader in democracy and
                progressive governance. We see a Philippines that thrives on collaboration, where cultural diversity serves as a
                unifying strength, and where the potential of each individual is fully realized in a society committed to the common
                good. Together, we will forge a path to a brighter, just, and thriving future for generations to come.
              </p>
            </v-col>
          </div>

          <div class="d-flex flex-column ma-8 justify-center align-center">
            <div><h1>Our Manifesto</h1></div>
            <v-col cols="12" sm="12" md="8" lg="8" xl="8">
              <p style="width:100%;">
                In a time when our nation stands at the precipice of disillusionment, enveloped by a relentless tide of political
                chaos, we, the founders and passionate members of Reforma Pilipinas, boldly declare our existence as a
                catalyst for unparalleled change. The current political environment is not merely a challenge; it is a battleground
                where the integrity of our democracy is threatened, and we, patriots with an indomitable spirit, refuse to stand
                idly by.
                Our Call to Action: We represent the voice of the countless Filipinos who are fed up with rhetoric and empty
                promises. We have seen the erosion of trust, the decay of institutions, and the rampant spread of corruption that
                suffocates our potential as a nation. This is our moment to disrupt the status quo, to dismantle complacency,
                and to ignite a movement that embraces integrity, justice, and genuine empowerment.
                As Major Disruptors, We Stand on the Following Pillars:
              </p>
            </v-col>
          </div>
          
          <div>
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
          </div>
        </v-container>
        <v-container class="text-center">
          <div class="d-flex flex-column ma-8 justify-center align-center">
            <div><h1>Real Stories, Real Change</h1></div>
            <v-col cols="12" sm="12" md="6"><p>Hear from citizens who turned their frustration into action and achieved meaningful results in their communities.</p></v-col>
          </div>
          <div>  
            <v-carousel
              :show-arrows="false"
              height="auto"
              >
              <v-carousel-item style="height:100%;"
              >
                <v-row style="height: 100%;" align="center" justify="center" no-gutters>
                  <v-col align="center" class="pa-3" justify="center" cols="12" sm="4" md="4">
                    <v-img rounded="circle" style="max-width:180px;" src="/icon.png"></v-img>
                  </v-col>
                  <v-col cols="12" sm="12" md="8" align="left">
                    <div style="font-size: 20px;">
                    <p><v-icon style="color:#FF5349">mdi-format-quote-open</v-icon></p>
                    <br>
                    <p>Why are black and a spark of orange the colors of Reforma Pilipinas?</p>
                    <br>
                    <p><b>Black as Our Foundation</b></p>
                    <p>- Resolve and Strength – Black embodies the unyielding will of Reforma Pilipinas. It speaks to our determination to confront entrenched interests, to stand firm against corruption, and to refuse appeasement when our democratic ideals are under threat. </p>
                    <p>- Solidarity and Unity – In many cultures, black is the color of collective resolve. By adopting black as our core hue, we signal that every member—regardless of background—stands together, shoulder to shoulder, in pursuit of genuine reform.</p>
                    <p>- Cleansing Shadows of the Past – Black also carries the weight of history’s darker chapters. It reminds us of the corruption, inertia, and disillusionment we seek to leave behind. Embracing black honors the struggles that came before and galvanizes us to ensure those mistakes are never repeated.</p>
                    <br>

                    <p><b>Orange as Our Spark</b></p>
                    <p>- Vision and Optimism – A flash of orange cuts through the darkness: it’s the dawn of new ideas, the warmth of fresh hope, and the promise that change is not only possible but within our grasp.</p>
                    <p>- Energy and Action – Orange is synonymous with movement and momentum. It’s the surge of creativity, the pulse of innovation, and the call to every Filipino to rise, speak up, and get involved.</p>
                    <p>- Inclusivity and Accessibility – Whereas black can be austere, orange feels approachable and human. It invites dialogue, bridges generations, and reminds us that reform is a collective, life-affirming endeavor.</p>

                    <br>

                    <p><b>The Combined Impact</b></p>
                    <p>By pairing black with a hint of orange, Reforma Pilipinas crafts a visual identity that is at once stern and hopeful. Black provides the bedrock of our convictions—unyielding, principled, and mindful of history’s lessons—while orange sparks the forward thrust of our mission: energizing citizens, illuminating pathways to progress, and celebrating the creative spirit that will define our nation’s next chapter. Together, these colors tell a story of steadfast resolve powered by bright possibility—a perfect emblem for a movement determined to forge a new path.</p>
                  
                    </div>
                  </v-col>
                </v-row>
              </v-carousel-item>

            </v-carousel>
          </div>
        </v-container>
  
       
  <v-container fluid>
    <div class="pa-3 text-center d-flex flex-column justify-center align-center">
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
  <v-container class="text-white" fluid style="background-color:#111827;">
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
  export default {
    data () {
      return {
        path: ''
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
    background-color: #1F2937;
    color: white;
    text-align: left;
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

  @keyframes draw {
    100% {
      stroke-dashoffset: 0;
    }
  }
</style>
