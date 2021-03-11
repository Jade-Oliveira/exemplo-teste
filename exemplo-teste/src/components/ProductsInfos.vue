<template>
    <div id="products">
        <div id="products1">
            <h3 class="infos">Cabo Frio - RJ</h3><br>
            <h3 class="infos">João Garcia</h3>
        </div>
        <div id="products2">
            <h3 class="infos">R$ 5,000.000</h3><br>
            <h3 class="infos">Venda</h3>
        </div>
    </div>
</template>

<script>
export default {
   name: 'ProductsInfos'
}
</script>

<style scoped>
    #products {
        margin: 15px;
        display: flex;
        justify-content: space-between;
    }

    #products2 {
    text-align: end;

    }

    .infos {
        color: rgb(43, 39, 39);
        font-weight: 400;
        font-size: 18px;
        line-height: 5px;
    }


</style>
