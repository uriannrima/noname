<script lang="tsx">
import { IonApp, IonRouterOutlet } from "@ionic/vue";
import { defineComponent } from "vue";

export default defineComponent({
  name: "App",
  setup() {
    return () => (
      <IonApp>
      <div>Hi1</div>
      </IonApp>
    );
  },
});
</script>