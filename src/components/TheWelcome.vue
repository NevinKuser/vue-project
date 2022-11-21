<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
import Card from './Card.vue'
import CardStory from './CardStory.vue'
import Collage from './Collage.vue'
import Footer from './Footer.vue'
</script>

<template>
  <div id="top">
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Services offered</template>
    <ul>
  <li>Ceremony</li>
  <li>Healing</li>
  <li>Psychic reading</li>
  <li>Consultation</li>
  <li>Water blessing (melukat)</li>
</ul>
  </WelcomeItem>
</div>
  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Shopping</template>

    I produce and sell spiritual tools, incense, and natural medicines by request.
     
   
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Eco-friendly</template>
    Protecting nature is my passion. This is what all of my efforts go towards. 
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Community</template>
I'm always working hard to protect the forest and farmland in my village and provide my community with food, medical supplies, and quality education.
  </WelcomeItem>
<div id="bottom">
  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Support Me</template>

    I rely on community backing to improve the quality of life in my village. You can sponsor my village
    <a href="https://wise.com" target="_blank" rel="noopener">by opening this page to make a donation</a> with Wise transfer using recipient marantya87@gmail.com or use my local bank account: BCA 1350424446 
    
  </WelcomeItem>
</div>
  <main>
    <RouterView />
    <Card 
		  msg_h1="Psychic Reading" 
		  msg_h2="Let Jero Mangku Tya use her sixth sense
                	to provide valuable information" 
		  msg_p_1="Book a psychic reading to get insight on specific parts of your life that need attention. Jero Tya connects with your ancestors and relives past lives, childhood, and present to receive important messages about personal life, family, relationship, and career. Ask her anything you want and she will connect with spirit to provide you with the best answers." 
		  msg_p_2="This includes a blessing and purification in the beginning of the session to relieve negative energy and anxiety. One of the main functions of the psycic reading is to uncover the steps needed to reach your goals and your fullest potential." 
		  phoneNumber="WhatsApp: +62 83119517779">
		  <template #image>
			<img src="../../resources/img/ulu/5.jpeg" alt="Jero Tya in Uluwatu, Bali." id="pic">
		</template>
		  </Card>

	<Card msg_h1="Health treatments" 
		  msg_h2="I can help you get healthy" 
		  msg_p_1="I treat cancer, autoimmune disorders, diabetes, weight loss, and can greatly improve mental wellness. This is done through diet, natural medicine, energy healing, yoga, and pranayama."  
		  phoneNumber="WhatsApp: +62 83119517779"><template #image>
			<img src="../../resources/img/Tya_offerings4.jpg" alt="Prayers in Bali" id="pic">
		</template></Card>

	<Card msg_h1="Chakra cleansing ceremony" 
		  msg_h2="An unforgettable experience" 
		  msg_p_1="Jero Mangku Tya has been guiding chakra cleansing energy purification ceremonies for years. A heart-warming experience with an energy that is felt deep in the soul. Message Nevin at the number below to book a space at the next ceremony. We're also doing this online once a week via zoom."  
		  phoneNumber="WhatsApp: +62 83119517779"><template #image>
			<img src="../../resources/anime/bright_moon.png" alt="Kitty sitting under the moonlight." id="pic">
		</template></Card>

		<Card msg_h1="Melukat" 
		  msg_h2="Water blessing for individuals or groups" 
		  msg_p_1="Jero Tya has a special connection to Sebatu water temple because her husband developed a love for it when he was experiencing heavy anxiety in 2013. He noticed that every time he went there he would feel better. Then it became apparent that the place has a very special energy force concentrated like a focused laser beam down at the bottom in the waterfall. This is where Jero Tya and her husband Nevin prefer to bring people who want to experience a powerful cleansing water blessing for releasing negative energy and anxiety. The benefit of going here is that you will leave feeling lighter and refreshed."  
		  phoneNumber="WhatsApp: +62 83119517779"><template #image>
			<img src="../../resources/img/Audreys_family.jpg" alt="Family praying with Jero Tya." id="pic">
		</template></Card>
		<Card msg_h1="Spiritual Advisor" 
		  msg_h2="Counseling to get through tough times and reach your goals" 
		  msg_p_1="Jero Tya has been guiding people with spiritual advice for years. A private consultation includes talking about what is troubling you and about your goals and where you want to be physically, mentally, spiritually, and emotionally. Please take notes.
		  You will receive recommendations for daily practices to raise your vibration."  
		  phoneNumber="WhatsApp: +62 83119517779"><template #image>
			<img src="../../resources/img/incense_burning.jpg" alt="Jero Tya's prayer offering" id="pic">
		</template></Card>

		<CardStory msg_h1="Her Story" 
		  msg_h2="Background" 
		  msg_p_1="---- It feels like an error that Jero Tya was born into this generation. Her spirit is from another time long ago.
                Tya is a native Balinese woman from a lineage of priests and healers originating from Mt Agung. Her dad is a Balian healer and taught her about Balinese culture in great detail. Her grandfather was a forest ranger in Mt Agung and taught her how to write Balinese characters and speak the polite Balinese language. Tya has been blessed with the ability to guide the spirits of the dead to the light. She does so via her direct connection and communication with the gods and her ancestors. She also has the power to fight off dark energy. 
                	---- As a child, Tya had many spiritual experiences and was already doing rituals using her intuition.
                    Her dad brought her to the Shiva temple every full moon and new moon where she absorbed high frequency energy.
                    ---- When Tya got a little older, she was faced with increasingly difficult trials. She couldn't walk for months and nobody could help. She was in a lot of pain. Her family asked help from many healers to no avail.
                    ---- Years later Tya's biggest trial presented itself. Her older brother passed away. She had to protect her parents while they were emotionally falling apart. In this time, the evil energies started getting closer. Tya got a sign in a dream. Shiva and Parvati were calling her to the temple to give her a sword. She went to the temple and was immediately consumed by a powerful surge of energy.
                    ---- On this same day there was a large ceremony at Jero Tya's house in her family temple. 50 years of dark energy had reached it's peak intensity when she confronted it during this ceremony.
                    ---- In the ceremony, there was an evil woman with dark energy in the temple. Everyone in Tya's village was afraid of this woman. The woman was sitting right next to her. Tya went to touch a prayer offering and the woman snapped at her... Don't touch that! As the words left the woman's mouth, JeroTya felt ten thousand watts of electricity flood her body as she began began channeling the god Parvati. Jero Tya lifted the woman up from her seat by her hair and began speaking ancient Balinese languange at the top of her voice to battle the old woman's evil spirits.
                   ---- She forced the woman to apologize for all the terrible things she had done in her life (poisoning and killing people in her community). This went on for nearly three hours and people from the next village over came to watch. There were so many people watching that they were standing on top of the wall to get a better look at what was happening.
                    ---- Many people tried to record video but the screen on their phones went black. No video was captured.
                    ---- After this, many people came to interview Tya and she started to become famous as a healer. Many Balinese people came to her for counseling and energy healing sessions. But her trials had not finished yet. The family of the evil woman Tya defeated were enraged. They already killed her brother over a land inheritance and Tya had to hideout for a few months with her extended family in the forest of Mt Agung. Tya heightened her spiritual practice yet again and the situation got better.
                    ---- Finally, Tya came back home. Around that same time, her community needed a new priest for their temple as the old priest had died. Everyone agreed to visit a wise woman in another village to ask who the next priest will be. When they arrived the wise woman already knew why they came. Somebody spoke up and said we need to know. Who will be our next priest? The wise woman responded, Your priest is already here. She is a woman and you need to accept that she is a woman. Don't ask again. Don't look in another place. Just make a blessing for her to become a priest in your temple.
                ---- In that time Tya lost herself and started ringing an imaginary priest bell. 
                    ---- When Tya came to she was shocked and knew deep inside her soul how heavy a responsibility it is to become a priest. What more, it was unheard of for a woman to be chosen as a priest and she would have to deal with backlash from the men. She was still young, not married yet, and thinking about her future. Becoming a hindu priest is not a hobby but rather a lifelong commitment to serve the community. Tya began to cry under the seriousness of the situation and didn't leave her house for days. Soon after, the community held another meeting and Tya accepted the responsibility to become their priest under the condition that she was allowed to marry and have children.
                ---- And so it was.
                   ---- The special thing about Tya is that she is the only woman to become a real priest in Bali chosen by god and her community. She also received certification as a priest from the council of hindu dharma in Bali to make it legal for her to run ceremonies. Normally only men are chosen to become priests in Bali, making it very unusual and special for a woman to be chosen. God has borrowed Tya's body many times to transfer knowledge of mantra and instructions in the temple. She also received a divine signal explaining how to treat people with healing energy.
                ---- Tya has a unique ritual to attract healing energy and has healed many Balinese people. She noticed that people's problems all had a common root in negativity they absorbed from other people. She was the only person in her village strong enough to battle these negative energies to the end, often taking hours or even days.
                ---- Jero Tya truly loves her Balinese culture and has a special skill to awaken the spirit of the ancient practices.">
				</CardStory>

				<Card msg_h1="Our purpose" 
		  msg_h2="What is our cause?" 
		  msg_p_1="Our goal with everything we do is to protect our quiet little farming village from getting paved over. The world needs more places full of trees and fresh air. This is our little slice of heaven, our little oasis!
                
                    We've only been able to keep it pristine in recent times due to donations from people like you.
                
                Most recently we've bought a 500 meter piece of farmland (pictured) and made a deposit on another 1200 square meter piece of forest nearby. Continued donations from our small network of friends and supporters made it all possible.
                In a world riddled with wildfires and an ongoing pandemic, fresh air has never been more important!
                Our intuition was correct, we do in fact need fresh air and trees.
                We are also passionate about preserving the ancient Balinese food culture and recipes that are deeply rooted in the old organic farming methods. In Bali, the ancient farming wisdom gives us radiant health, a clear mind, and longevity! Modern processed foods make us slow, sick, and confused. 
                Donations can be made to: 
                    Bank Central Asia -
                	NAME: Ni Komang Marantiawati - 
                	ACCOUNT: 1350424446 -
                	ADDRESS: Jl Raya Ubud - 
                	Ubud, Bali 80571 
                	Indonesia - 
                 Or via Wise using email: marantya87@gmail.com">
                 <template #image>
			<img src="../../resources/img/sawah.jpg" alt="Land conservation in east Bali." id="pic"></template></Card>
    <Collage /> 
    
		<Footer></Footer>
  </main>
</template>


<style scoped>
div #top { margin-top: 100px; }
div #bottom { margin-bottom: 100px; }
#pic {
	height: auto;
	width: 60%;
	border-radius: 1rem;
	margin: 6% 0 2% 20%;
  border: 1.5px solid black;
}

ul { padding: 0; margin: 0; list-style:circle;}
ul li { padding: 0px; margin: 0; display: list-item;}

@media(max-width: 1000px) {
#pic {
	height: auto;
	width: 80%;
	border-radius: 1rem;
	margin: 6% 10% 2% 10%;
  border: 1.5px solid black;
}}
</style>
