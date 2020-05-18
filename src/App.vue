<template>
  <app-servers></app-servers>
</template>

<script>
import Header from "./components/Shared/Header";
import Footer from "./components/Shared/Footer";
import Servers from "./components/Server/Servers";
import ServerDetails from "./components/Server/ServerDetails";

export default {
  components: {
    "app-header": Header,
    "app-footer": Footer,
    "app-servers": Servers,
    "app-server-etails": ServerDetails
  }
};
</script>

<style></style>
