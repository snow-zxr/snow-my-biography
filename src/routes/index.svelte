<script>
import Header from '$lib/Header. swelte';
import Section from '$lib/Section.svelte';

let myInfo = {
title: "Info",
item1: "Snow Chow",
item2: 13,
item3: "Chung Ling Private High School"
}

Let myhobby = {
title: "Hobby"
item1: "Swimming",
item2: "Listen to Music",
item3: "Watch Movies"
}

Let myPersonality = {
title: "personality".
item1: "Queit".
item2: "Humble",
item3: "Kind"
}

</script>
<Header title={"my Biography"} />
<section {...myInfo} />
<section {...myHobby} /
<section {...myPersonality} />
