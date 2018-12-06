<template>
  <Page>
    <ActionBar title="Welcome to NativeScript-Vue!"/>
    <StackLayout columns="*" rows="*">
      <Label class="message" :text="'test.with.dot'|L" col="0" row="0"/>
      <Label class="message" :text="'neasted.value'|L" col="0" row="0"/>
      <Label class="message" :text="'neasted.test'|L" col="0" row="0"/>
      <Label class="message" :text="'add_an_other_one'|L" col="0" row="0"/>
      <Label class="message" :text="'ho'|L" col="0" row="0"/>
      <Label class="message" :text="'neasted.doubleNeasted.value'|L" col="0" row="0"/>
      <Label class="message" :text="'(something a bit weird): but it.'|L" col="0" row="0"/>
      <Label class="message" :text="'thatWork'|L" col="0" row="0"/>
    </StackLayout>
  </Page>
</template>

<script>
export default {
  data() {
    return {
      msg: "Hello World!"
    };
  }
};
</script>

<style scoped>
ActionBar {
  background-color: #53ba82;
  color: #ffffff;
}

.message {
  vertical-align: center;
  text-align: center;
  font-size: 20;
  color: #333333;
}
</style>
