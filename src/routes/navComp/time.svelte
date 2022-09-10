<script>
import { onMount } from "svelte";
import moment from 'moment'

let now = moment()

$: time = now.format('LT');

onMount( () => {
   const interval = setInterval(() => {
     now = moment();
   }, 1000);
 });

</script>

<div>
  {time}
</div>