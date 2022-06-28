<template>
  <div>
    <Change />
    <span>=================================================</span>
    <Message />
    <span>=================================================</span>
    <Imageurl />
  </div>
</template>

<script>
//引入组件
import Message from './components/Message.vue';
import Change from './components/Change.vue';
import Imageurl from './components/Imageurl.vue';

export default {
  name: 'App',
  components: {
    Change,
    Message,
    Imageurl,
  },
};
</script>
