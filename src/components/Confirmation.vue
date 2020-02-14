<template>
    <div>
      <b-alert variant="success" show>{{message}}
        <button
          v-on:click="showConfirmation = false"
          type="button" class="close" data-dismiss="alert"
          aria-label="Close">
          <span aria-hidden="true">&times;</span>
        </button>
      </b-alert>
    </div>
</template>

<script>
export default {
  props: ['message'],
};
</script>
