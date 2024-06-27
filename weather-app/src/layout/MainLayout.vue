<template>
  <q-layout view="lHr lpR lfr">
    <q-header class="bg-blue-9 text-white" height-hint="98">
      <q-toolbar>
        <q-toolbar-title class="text-white">UAS Praktikum DanangSetyo</q-toolbar-title>
        <q-tabs align="left">
          <q-route-tab to="/" label="weather" />
        </q-tabs>
      </q-toolbar>
    </q-header>
    <q-page-container>
      <router-view />
    </q-page-container>
    <q-footer class="bg-gray-2 text-black" height-hint="98">
      <q-toolbar>
        <q-toolbar-title class="text-black">
          Copyright © DanangSetyo. All rights reserved.
        </q-toolbar-title>
      </q-toolbar>
    </q-footer>
  </q-layout>
</template>
