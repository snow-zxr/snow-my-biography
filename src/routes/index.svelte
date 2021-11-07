<script>
import Header from '$lib/Header.svelte';
import Section from '$lib/Section.svelte';

let myInfo = {
title: "Info",
item1: "Snow Chow",
item2: 13,
item3: "Chung Ling Private High School"
}

let myHobby = {
title: "Hobby",
item1: "Swimming",
item2: "Listen to Music",
item3: "Watch Movies"
}

let myPersonality = {
title: "Personality",
item1: "Queit",
item2: "Humble",
item3: "Kind"
}

</script>

<Header title={"My Biography"} />
<section {...myInfo} />
<section {...myHobby} />
<section {...myPersonality} />
