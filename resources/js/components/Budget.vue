<template>
                    <tr>
                      <th scope="row">{{budget.norder}}</th>
                      <td>{{ budget.ninvoice}}</td>
                      <td>{{ budget.description }}</td>
                      <td>{{ budget.date }}</td>
                      <td>{{ budget.total }}</td>
                      <td>{{ budget.desct1 }}</td>
                      <td>{{ budget.desct2 }}</td>
                    </tr>
                  
</template>

<script>
    export default {
        props: ['budget'],
        data(){
            return {
            }
        },
        mounted() {
            console.log('Component mounted.')
        }
    }
</script>
