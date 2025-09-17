<script setup></script>

<template>
    <v-layout>
      <v-app-bar
        color="white"
        density="comfortable"
        >
        <template v-slot:prepend>
          <div style="width:100px; margin:0px !important; padding:0px !important;"><v-img style="height:100%; width: 100%;" src="/icon.jpg"></v-img></div>
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
          <v-parallax height="100vh" src="/hero.jpg">
    <div class="d-flex flex-column justify-center align-center text-white" style="margin-top: 30vh;">
      <!-- <h1 class="text-h1">
        <b>Your Voice.</b>
      </h1>
      <h1 class="text-h1">
        <b style="color:#FF5349">Our Strength.</b>
      </h1> -->
      <v-col style="width: 55%; text-align: center;">
        <h3>
          We are the collective voice of citizens who refuse to accept empty promises and political rhetoric. Together, we demand real change, accountability, and genuine representation.
        </h3>
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
    <div style="width:50%;"><p>To amplify the voices of everyday citizens and hold our leaders accountable for their promises, creating real change through grassroots advocacy.</p></div>
    </div>
    <div>
      <v-row>
        <v-col md="6">
        <v-img src="https://readdy.ai/api/search-image?query=Group%20of%20diverse%20citizens%20in%20town%20hall%20meeting%2C%20engaged%20discussion%2C%20people%20raising%20hands%2C%20community%20gathering%2C%20authentic%20grassroots%20democracy%20in%20action%2C%20natural%20lighting%2C%20documentary%20photography%20style%2C%20real%20people%20having%20meaningful%20conversations%20about%20policy&width=800&height=600&seq=mission1&orientation=landscape"></v-img>
      </v-col>
      <v-col md="6">
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
    <div class="pt-5">  
      <v-carousel
      >
        <v-carousel-item
        >
        <v-row align="center" justify="center" no-gutters>
          <v-col align="center" justify="center" xs="12" md="4">
            <v-img style="border-radius: 50%;"width="50%" src="https://readdy.ai/api/search-image?query=Professional%20portrait%20of%20Asian%20American%20woman%20in%20her%2030s%2C%20small%20business%20owner%2C%20confident%20smile%2C%20professional%20but%20approachable%2C%20natural%20lighting%2C%20authentic%20entrepreneur%20and%20community%20leader%2C%20simple%20background&width=400&height=400&seq=testimonial3&orientation=squarish"></v-img>
          </v-col>
          <v-col xs="12" md="8" align="left">
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
      <v-row>
          <v-col align="center" justify="center" xs="12" md="4">
            <v-img style="border-radius: 50%;"width="50%" src="https://readdy.ai/api/search-image?query=Professional%20portrait%20of%20African%20American%20man%20in%20his%2050s%2C%20factory%20worker%20and%20military%20veteran%2C%20determined%20expression%2C%20wearing%20casual%20shirt%2C%20natural%20lighting%2C%20authentic%20grassroots%20activist%2C%20simple%20background&width=400&height=400&seq=testimonial2&orientation=squarish"></v-img>
          </v-col>
          <v-col xs="12" md="8" align="left" justify="left">
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
  <v-container fluid style="background-color:#082B59; width: 100%;">
    <div class="text-center text-white">
      <h1>Proven Impact Across America</h1>
      <br>
      <h3>When citizens unite behind a common cause, we achieve real results. Here's how we've turned frustration into meaningful policy changes.</h3>
    </div>
  </v-container>
      </v-main>
    </v-layout>
</template>


<script>
  export default {
    data() {
      return{
        items: [
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
</style>
