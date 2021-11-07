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

<Header title="My Biography" />
<Section {...myInfo} />
<Section {...myHobby} />
<Section {...myPersonality} />
<p>GitHub respository<br>My Biography © All right reserved.</p>

<style>
    p{
        font-family: fantasy;
        background-color: #0d98ba;
        color: #98fb98; 
        margin: 10px;
        text-align: center;
        box-shadow: 0 4px 8px 0 rgba(0,0,0,0.5);
        padding: 2px 16px;
   	    margin: 12px 4px;
   	    border-radius: 5px;
    }
</style>