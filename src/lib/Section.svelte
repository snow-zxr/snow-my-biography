<script>
    export let title;
    export let item1;
    export let item2;
    export let item3;
</script>

<div>
    <h3>{title}</h3>
    <p>{item1}</p>
    <p>{item2}</p>
    <p>{item3}</p>
</div>

<style>
    div{
        background-color: #00adad;
        text-align: center;
        box-shadow: 0 4px 8px 0 rgba(0,0,0,0.5);
        padding: 2px 16px;
   	    margin: 12px 4px;
   	    border-radius: 5px;
    }

    h3{
        font-weight: bold;
        color: #e7feff;
        font-family: 'MV Boli';
        font-size: 30px;
    }

    p{
        color: lightblue;
        font-family: 'Comic Sans MS', cursive;
    }
</style>