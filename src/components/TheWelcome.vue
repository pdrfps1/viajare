<script setup lang="ts">
import WelcomeItem from "./WelcomeItem.vue";
import DocumentationIcon from "./icons/IconDocumentation.vue";
import ToolingIcon from "./icons/IconTooling.vue";
import EcosystemIcon from "./icons/IconEcosystem.vue";
import CommunityIcon from "./icons/IconCommunity.vue";
import SupportIcon from "./icons/IconSupport.vue";
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Viagem</template>

    Utilize essa aplicação para ter o controle de todas as suas <a>viagens</a>.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Despesas</template>

    O aplicativo utiliza das melhores ferramentas para fazer com o que sua <a>viagem</a> fique bem organizada.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Ecossistema</template>

    Compartilhe todas as suas <a>viagens</a> com os seus amigos.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Features</template>

    Faça anotações de tudo o que aconteceu na sua <a>viagem</a>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Support Vue</template>

    Em caso de qualquer duvida entre em contato com o <a>grupo 4</a>.
  </WelcomeItem>
</template>
