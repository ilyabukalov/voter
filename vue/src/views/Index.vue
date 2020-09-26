<template>
  <div>
    <div class="sp-container">
      <sp-sign-in />
      <sp-bank-balances />
      <sp-token-send />
      <!-- this line is used by starport scaffolding # 4 -->
      <poll-form />
		<!-- <sp-type-form type="poll" :fields="['title', 'options', ]" /> -->
    </div>
  </div>
</template>

<script>
import * as sp from "@tendermint/vue";
import PollForm from "./../components/PollForm.vue";


export default {
  components: { ...sp, PollForm },
};
</script>
