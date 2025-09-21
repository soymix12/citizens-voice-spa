<script setup></script>

<template>
    <v-layout>
      <v-app-bar
        color="white"
        height="90"
        >
        <template v-slot:prepend>
          <div style="width:120px; margin:0px !important; padding:0px !important;"><v-img style="height:100%; width: 100%;" src="/icon.jpg"></v-img></div>
        </template>
 
        <v-app-bar-title class="d-flex justify-center flex-row">
          <v-btn>Our Mission</v-btn>
          <v-btn>Stories</v-btn>
          <v-btn>Impact</v-btn>
          <v-btn>Get Involved</v-btn>
        </v-app-bar-title>

  
        <template v-slot:append>
          <v-btn style="background-color:#FF5349" rounded="xl"><span style="color:white">Join Now</span></v-btn>
        </template>
      </v-app-bar>

      <v-main>
        <!-- <v-container fluid> -->
        <v-parallax  src="/hero.jpg">
        <div class="d-flex flex-column justify-center align-center text-white" style="margin-top: 50vh;">
      <!-- <h1 class="text-h1">
        <b>Your Voice.</b>
      </h1>
      <h1 class="text-h1">
        <b style="color:#FF5349">Our Strength.</b>
      </h1> -->
      <v-col cols="12" sm="6" md="6" style="text-align: center;">
        <h3>
          We are the collective voice of citizens who refuse to accept empty promises and political rhetoric. Together, we demand real change, accountability, and genuine representation.
        </h3>
     
     
 
      </v-col>
      <v-col>
        <div class="d-flex justify-center flex-row pt-4">
          <v-btn color="#FF5349" rounded="xl" size="x-large" class="ma-1">Join the Movement</v-btn>
          <v-btn rounded="xl" variant="outlined" size="x-large" class="ma-1">Learn Our Story</v-btn>
        </div>
      </v-col>
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
    <v-col cols="12" sm="12" md="8" lg="8" xl="8"><p style="width:100%;">To amplify the voices of everyday citizens and hold our leaders accountable for their promises, creating real change through grassroots advocacy.</p></v-col>
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
            subtitle="We ensure that every citizen's concerns are heard and addressed, breaking through the noise of political spin and empty rhetoric."
            title="Amplify Citizen Voices"
            >
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
            subtitle="We track promises made by political leaders and hold them accountable for their commitments to the communities they serve."
            title="Demand Accountability"
            >
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
            subtitle="Through organized advocacy and community mobilization, we create tangible policy changes that improve lives across our nation."
            title="Drive Real Change"
            >
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
    <div style="width:50%;"><p>Hear from citizens who turned their frustration into action and achieved meaningful results in their communities.</p></div>
    </div>
    <div>  
      <v-carousel
      :show-arrows="false"
      >
        <v-carousel-item
        >
        <v-row style="height: 100%;" align="center" justify="center" no-gutters>
          <v-col align="center" justify="center" cols="12" sm="12" md="4">
            <v-img style="border-radius: 50%;"width="50%" src="https://readdy.ai/api/search-image?query=Professional%20portrait%20of%20Asian%20American%20woman%20in%20her%2030s%2C%20small%20business%20owner%2C%20confident%20smile%2C%20professional%20but%20approachable%2C%20natural%20lighting%2C%20authentic%20entrepreneur%20and%20community%20leader%2C%20simple%20background&width=400&height=400&seq=testimonial3&orientation=squarish"></v-img>
          </v-col>
          <v-col cols="12" sm="12" md="8" align="left">
            <div style="font-size: 20px;">
            <p>Empty promises about supporting small businesses were all we heard. Citizens Voice helped us organize local business owners to demand real policy changes. We now have the support and resources we need to thrive.</p>
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
            <p>I served this country, but when I came home, our leaders forgot about veterans like me. Citizens Voice gave me a platform to fight for veteran healthcare reform. Now my fellow veterans are getting the care they earned.
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
        <!-- </v-container> -->
  <v-container fluid style="background-color: #111827; width: 100%;">
    <div class="pa-3 text-center text-white">
      <h1>Proven Impact Across America</h1>
      <br>
      <h3>When citizens unite behind a common cause, we achieve real results. Here's how we've turned frustration into meaningful policy changes.</h3>
      <v-row style="margin-top:30px;">
        <v-col cols="12" md="4">
      <v-card
        link
        class="mx-auto"
      >
        <v-card-title> <v-btn
                  elevation="0"
                  class="my-3"
                  color="#FF5349"
                  icon="mdi-wrench"
                ></v-btn></v-card-title>
        <v-card-subtitle><h2>Healthcare Reform</h2></v-card-subtitle>
        <v-card-text>
          <p>Secured $2.3M in additional funding for rural healthcare clinics</p>
          <p style="margin-top: 15px;"><v-icon>mdi-map-marker-outline</v-icon>Michigan & Ohio</p>
        </v-card-text>
      </v-card>
    </v-col>
    <v-col cols="12" md="4">
      <v-card
        link
        class="mx-auto"
      >
        <v-card-title> <v-btn
                  elevation="0"
                  class="my-3"
                  color="#FF5349"
                  icon="mdi-wrench"
                ></v-btn></v-card-title>
        <v-card-subtitle><h2>Healthcare Reform</h2></v-card-subtitle>
        <v-card-text>
          <p>Secured $2.3M in additional funding for rural healthcare clinics</p>
          <p style="margin-top: 15px;"><v-icon>mdi-map-marker-outline</v-icon>Michigan & Ohio</p>
        </v-card-text>
      </v-card>
    </v-col>
    <v-col cols="12" md="4">
      <v-card
        link
        class="mx-auto"
      >
        <v-card-title> <v-btn
                  elevation="0"
                  class="my-3"
                  color="#FF5349"
                  icon="mdi-wrench"
                ></v-btn></v-card-title>
        <v-card-subtitle><h2>Healthcare Reform</h2></v-card-subtitle>
        <v-card-text>
          <p>Secured $2.3M in additional funding for rural healthcare clinics</p>
          <p style="margin-top: 15px;"><v-icon>mdi-map-marker-outline</v-icon>Michigan & Ohio</p>
        </v-card-text>
      </v-card>
    </v-col>
      </v-row>
      <v-row style="margin-top:20px;">
        <v-col cols="12" md="4">
      <v-card
        link
        class="mx-auto"
      >
        <v-card-title> <v-btn
                  elevation="0"
                  class="my-3"
                  color="#FF5349"
                  icon="mdi-wrench"
                ></v-btn></v-card-title>
        <v-card-subtitle><h2>Healthcare Reform</h2></v-card-subtitle>
        <v-card-text>
          <p>Secured $2.3M in additional funding for rural healthcare clinics</p>
          <p style="margin-top: 15px;"><v-icon>mdi-map-marker-outline</v-icon>Michigan & Ohio</p>
        </v-card-text>
      </v-card>
    </v-col>
    <v-col cols="12" md="4">
      <v-card
        link
        class="mx-auto"
      >
        <v-card-title> <v-btn
                  elevation="0"
                  class="my-3"
                  color="#FF5349"
                  icon="mdi-wrench"
                ></v-btn></v-card-title>
        <v-card-subtitle><h2>Healthcare Reform</h2></v-card-subtitle>
        <v-card-text>
          <p>Secured $2.3M in additional funding for rural healthcare clinics</p>
          <p style="margin-top: 15px;"><v-icon>mdi-map-marker-outline</v-icon>Michigan & Ohio</p>
        </v-card-text>
      </v-card>
    </v-col>
    <v-col cols="12" md="4">
      <v-card
        link
        class="mx-auto"
      >
        <v-card-title> <v-btn
                  elevation="0"
                  class="my-3"
                  color="#FF5349"
                  icon="mdi-wrench"
                ></v-btn></v-card-title>
        <v-card-subtitle><h2>Healthcare Reform</h2></v-card-subtitle>
        <v-card-text>
          <p>Secured $2.3M in additional funding for rural healthcare clinics</p>
          <p style="margin-top: 15px;"><v-icon>mdi-map-marker-outline</v-icon>Michigan & Ohio</p>
        </v-card-text>
      </v-card>
    </v-col>
    <v-col cols="12" sm="12" md="12">
      <div style="width: 100%; border-radius: 5px; background-color: #FF5349;">
        <div class="pa-8">
          <h1>Ready to Create Change in Your Community?</h1>
          <h3>Join thousands of citizens who refuse to accept the status quo</h3>
          <v-btn class="mt-4" elevation="0" rounded="xl"  style="color:#FF5349">Start Your Campaign</v-btn>
        </div>
   
      </div>
    </v-col>
      </v-row>

    </div>
  </v-container>
  <v-container fluid>
    <div class="pa-3 text-center d-flex flex-column justify-center align-center">
    <h1>Join the Movement</h1>

      <v-col style="text-align: center;" justify="center" align="center" class="text-center" cols="12" sm=12 md="6"><h3>Ready to turn your frustration into action? Become a member of Citizens Voice and help create the change your community needs.</h3></v-col>
    </div>
    <v-row>
      <v-col cols="12" sm="12" md="6">
        <v-col style="background-color:#FEF2F2 !important; border-radius:10px;"cols="12" sm="12" md="12">
          <div style="width:100%;" class="pa-5">
            <h2>Why Join Citizen's Voice?</h2>
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
            <h2>Why Join Citizen's Voice?</h2>
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
          
          <v-col cols="12" sm="12" md="6">
          <v-text-field
        v-model="first"
        color="primary"
        label="First name"
        hide-details="auto"
      ></v-text-field>
        </v-col>
        <v-col cols="12" sm="12" md="6">
          <v-text-field
        v-model="first"
        color="primary"
        label="Last name"
        hide-details="auto"
      ></v-text-field>
        </v-col>
        <v-col cols="12" sm="12" md="12">
          <v-text-field
        v-model="first"
        color="primary"
        label="Email"
        hide-details="auto"
      ></v-text-field>
        </v-col>
        <v-col cols="12" sm="12" md="6">
          <v-text-field
        v-model="first"
        color="primary"
        label="Phone"
        hide-details="auto"
      ></v-text-field>
        </v-col>
        <v-col cols="12" sm="12" md="6">
          <v-text-field
        v-model="first"
        color="primary"
        label="Zip Code"
        hide-details="auto"
      ></v-text-field>
        </v-col>
        
        <v-row style="padding:0px; margin:0px;">
          <v-col cols="12" sm="12" md="12"><p>Issues You Care About (Select all that apply)</p></v-col>
          <v-col cols="6" sm="6" md="6">
           
            <v-checkbox
            v-model="ex4"
            color="red"
            label="Healthcare Reform"
            value="red"
            hide-details
          ></v-checkbox>
          <v-checkbox
            v-model="ex4"
            color="red"
            label="Infrastructure"
            value="red"
            hide-details
          ></v-checkbox>
          <v-checkbox
            v-model="ex4"
            color="red"
            label="Housing Rights"
            value="red"
            hide-details
          ></v-checkbox>
          <v-checkbox
            v-model="ex4"
            color="red"
            label="Criminal Justice Reform"
            value="red"
            hide-details
          ></v-checkbox>
          
          </v-col>
          <v-col cols="6" sm="6" md="6">
            <v-checkbox
            v-model="ex4"
            color="red"
            label="Education Funding"
            value="red"
            hide-details
          ></v-checkbox>
          <v-checkbox
            v-model="ex4"
            color="red"
            label="Veterans Affairs"
            value="red"
            hide-details
          ></v-checkbox>
          <v-checkbox
            v-model="ex4"
            color="red"
            label="Environmental Protection"
            value="red"
            hide-details
          ></v-checkbox>
          <v-checkbox
            v-model="ex4"
            color="red"
            label="Economic Justice"
            value="Economic Justice"
            hide-details
          ></v-checkbox>
          
          </v-col>
        </v-row>
        <v-col cols="12" sm="12" md="12">
          <v-text-field
        v-model="first"
        color="primary"
        label="Email"
        hide-details="auto"
      ></v-text-field>
        </v-col>
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
          <v-btn color="#DC2626" size="x-large" block>Join Citizens Voice</v-btn>
        </v-col>
        </v-row>
        
      </v-col>
    </v-row>
  </v-container>
  <v-container class="text-white" fluid style="background-color:#111827;">
    <v-row style="margin-top:50px;">
      <v-col cols="12" sm="12" md="6">
        <v-col cols=12 sm="12" md="12" style="margin:0px; padding:0px;"><h3 class="pa-2">Citizens Voice</h3></v-col>
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
      <v-col>© 2024 Citizens Voice. All rights reserved.</v-col>
      <v-col></v-col>
    </v-row>
  </v-container>
      </v-main>
    </v-layout>
</template>


<script>
  export default {
    data() {
      return{

        items: [
    { text: 'Real-Time', icon: 'mdi-clock' },
    { text: 'Audience', icon: 'mdi-account' },
    { text: 'Conversions', icon: 'mdi-flag' },
  ],
        itemsP_peopl: [
          {
            'src': 'https://readdy.ai/api/search-image?query=Professional%20portrait%20of%20Hispanic%20woman%20in%20her%2040s%2C%20teacher%2C%20warm%20smile%2C%20confident%20expression%2C%20natural%20lighting%2C%20authentic%20person%20representing%20everyday%20citizens%20fighting%20for%20change%2C%20simple%20background&width=400&height=400&seq=testimonial1&orientation=squarish',
            'testimony': 'For years, I watched politicians promise better education funding and never deliver. Citizens Voice helped us organize our community and actually get new funding approved for our schools. My kids now have the resources they deserve.',
            'name': 'Maria Rodriguez',
            'occupation': 'Teacher & Mother',
            'location': 'Phoenix, AZ'
          },
          {
            'src': 'https://readdy.ai/api/search-image?query=Professional%20portrait%20of%20African%20American%20man%20in%20his%2050s%2C%20factory%20worker%20and%20military%20veteran%2C%20determined%20expression%2C%20wearing%20casual%20shirt%2C%20natural%20lighting%2C%20authentic%20grassroots%20activist%2C%20simple%20background&width=400&height=400&seq=testimonial2&orientation=squarish',
            'testimony': 'For years, I watched politicians promise better education funding and never deliver. Citizens Voice helped us organize our community and actually get new funding approved for our schools. My kids now have the resources they deserve.',
            'name': 'James Thompson',
            'occupation': 'Factory Worker & Veteran',
            'location': 'Detroit, MI'
          },
          {
            src: 'https://readdy.ai/api/search-image?query=Professional%20portrait%20of%20Asian%20American%20woman%20in%20her%2030s%2C%20small%20business%20owner%2C%20confident%20smile%2C%20professional%20but%20approachable%2C%20natural%20lighting%2C%20authentic%20entrepreneur%20and%20community%20leader%2C%20simple%20background&width=400&height=400&seq=testimonial3&orientation=squarish',
            'testimony': 'For years, I watched politicians promise better education funding and never deliver. Citizens Voice helped us organize our community and actually get new funding approved for our schools. My kids now have the resources they deserve.',
            'name': 'Sarah Chen',
            'occupation': 'Small Business Owner',
            'location': 'Portland, OR'
          }
        ]
      }
    }
  }
</script>
<style>
  .v-toolbar__prepend{
    margin: 0px !important;

  }
  .v-card{
    background-color: #1F2937;
    color: white;
    text-align: left;
  }

</style>
