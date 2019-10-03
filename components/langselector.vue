Vue.component('langselector', {
  data: () => ({
    langs: ['bs', 'en']
  }),
  template:`
  <div class="locale-changer">
    <v-select
      v-model="$i18n.locale"
      :items="langs"
      label="Language"
      outlined
    ></v-select>
  </div>
</template>`
});