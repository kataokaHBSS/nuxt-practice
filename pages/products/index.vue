<template>
  <div>
    一覧表示<br>
    <NuxtLink to="/products/create">新規作成</NuxtLink>

    <table>
        <tr>
            <th>商品番号</th>
            <th>商品名</th>
            <th>詳細</th>
            <th>編集</th>
        </tr>
        <tr>
            <td>1</td>
            <td>テスト</td>
            <td><Nuxt-Link to="/products/1/show">詳細</Nuxt-Link></td>
            <td><Nuxt-Link to="/products/1/edit">編集</Nuxt-Link></td>
        </tr>
        <tr>
            <td>2</td>
            <td>テスト</td>
            <td><Nuxt-Link to="/products/2/show">詳細</Nuxt-Link></td>
            <td><Nuxt-Link to="/products/2/edit">編集</Nuxt-Link></td>
        </tr>
        <tr>
            <td>3</td>
            <td>テスト</td>
            <td><Nuxt-Link to="/products/3/show">詳細</Nuxt-Link></td>
            <td><Nuxt-Link to="/products/3/edit">編集</Nuxt-Link></td>
        </tr>
    </table>

  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>