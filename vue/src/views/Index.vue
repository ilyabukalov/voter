<template>
  <div>
    <div class="sp-container">
      <sp-sign-in />
      <sp-bank-balances />
      <sp-token-send />
      <!-- this line is used by starport scaffolding # 4 -->
     <poll-form />
     <poll-list />
    </div>
  </div>
</template>

<script>
import * as sp from "@tendermint/vue";
import PollForm from "./../components/PollForm.vue";
import PollList from "./../components/PollList.vue";


export default {
  components: { ...sp, PollForm, PollList },
};
</script>
