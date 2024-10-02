<template>
  <DBSection width="large">
    <h1>DB UI Playground</h1>
    <p>Test the components of the DB UX Design System here.</p>
    <DBLink
      href="https://marketingportal.extranet.deutschebahn.com/marketingportal/Design-Anwendungen/db-ux-design-system"
      content="external"
    >
      Docs
    </DBLink>
  </DBSection>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import { DBSection, DBLink } from "@db-ui/v-components";

export default defineComponent({
  name: "App",
  components: { DBSection, DBLink },
});
</script>

<style>
/* add styles */
</style>
