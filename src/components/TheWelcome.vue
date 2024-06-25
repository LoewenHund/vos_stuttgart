<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Dokumentation von VOS</template>

    Wichtige Unterlagen oder Artikel, mit sammt Updates zu allerlei Themen
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Tooling und wichtige Softwares</template>

    Für Kundentermine und Reparaturen: 
    <!-- Gewisse Software tools für Betankung-->
    <br> 
    -> Omnitracker Filter
    <br>
    -> Wichtige Driver 
    <br>
    -> DaSi- Tool 
    <br>
    -> SoftwareCenter Reparatur set



    <br />


  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Für Anfänger</template>

   Hier werden bald Links und oder Tipps stehen um das einarbeiten noch einfacher zu machen. 
    
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>ComputaCenter News</template>

   Willst du dich up to Date halten? dann kannst du dich hier Informieren  
    <a href="https://chat.vuejs.org" target="_blank" rel="noopener">ComputaCenter.</a>
    
   
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Support UHD</template>

    Falls irgendwelche Anliegen geben sollte, kann man sich gerne an das UHD Melden. 
    <a href="https://vuejs.org/sponsor/" target="_blank" rel="noopener">Hier Geht es zum UHD</a>.
  </WelcomeItem>
</template>
